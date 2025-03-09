# Function: <code>pci_for_each_dma_alias</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev * pdev, int (*)(struct pci_dev *, u16, void *) fn, void * data)
```

```json
{
  "name": "pci_for_each_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583280656,
      "name": "pci_for_each_dma_alias",
      "external": true,
      "loc": "drivers/pci/search.c:28",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_msi_domain_get_msi_rid",
        "drivers/pci/msi.c:pci_msi_get_device_domain",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583280656,
      "name": "pci_for_each_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev * pdev, int (*)(struct pci_dev *, u16, void *) fn, void * data)
```

```json
{
  "name": "pci_for_each_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583591728,
      "name": "pci_for_each_dma_alias",
      "external": true,
      "loc": "drivers/pci/search.c:28",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_msi_get_device_domain",
        "drivers/pci/msi.c:pci_msi_domain_get_msi_rid",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/amd_iommu.c:get_alias",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583591728,
      "name": "pci_for_each_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev * pdev, int (*)(struct pci_dev *, u16, void *) fn, void * data)
```

```json
{
  "name": "pci_for_each_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583728864,
      "name": "pci_for_each_dma_alias",
      "external": true,
      "loc": "drivers/pci/search.c:28",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_msi_get_device_domain",
        "drivers/pci/msi.c:pci_msi_domain_get_msi_rid",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/amd_iommu.c:get_alias",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel-iommu.c:set_domain_for_dev",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583728864,
      "name": "pci_for_each_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev * pdev, int (*)(struct pci_dev *, u16, void *) fn, void * data)
```

```json
{
  "name": "pci_for_each_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583769664,
      "name": "pci_for_each_dma_alias",
      "external": true,
      "loc": "drivers/pci/search.c:28",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_msi_get_device_domain",
        "drivers/pci/msi.c:pci_msi_domain_get_msi_rid",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/amd_iommu.c:get_alias",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel-iommu.c:set_domain_for_dev",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583769664,
      "name": "pci_for_each_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev * pdev, int (*)(struct pci_dev *, u16, void *) fn, void * data)
```

```json
{
  "name": "pci_for_each_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584029488,
      "name": "pci_for_each_dma_alias",
      "external": true,
      "loc": "drivers/pci/search.c:28",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_msi_get_device_domain",
        "drivers/pci/msi.c:pci_msi_domain_get_msi_rid",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/amd_iommu.c:get_alias",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel-iommu.c:set_domain_for_dev",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584029488,
      "name": "pci_for_each_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev * pdev, int (*)(struct pci_dev *, u16, void *) fn, void * data)
```

```json
{
  "name": "pci_for_each_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584226752,
      "name": "pci_for_each_dma_alias",
      "external": true,
      "loc": "drivers/pci/search.c:29",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_msi_get_device_domain",
        "drivers/pci/msi.c:pci_msi_domain_get_msi_rid",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/amd_iommu.c:get_alias",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel-iommu.c:set_domain_for_dev",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584226752,
      "name": "pci_for_each_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev * pdev, int (*)(struct pci_dev *, u16, void *) fn, void * data)
```

```json
{
  "name": "pci_for_each_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584316400,
      "name": "pci_for_each_dma_alias",
      "external": true,
      "loc": "drivers/pci/search.c:29",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_msi_get_device_domain",
        "drivers/pci/msi.c:pci_msi_domain_get_msi_rid",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/amd_iommu.c:get_alias",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel-iommu.c:set_domain_for_dev",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_table",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584316400,
      "name": "pci_for_each_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev * pdev, int (*)(struct pci_dev *, u16, void *) fn, void * data)
```

```json
{
  "name": "pci_for_each_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584511376,
      "name": "pci_for_each_dma_alias",
      "external": true,
      "loc": "drivers/pci/search.c:29",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_msi_get_device_domain",
        "drivers/pci/msi.c:pci_msi_domain_get_msi_rid",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/amd_iommu.c:get_alias",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_table",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584511376,
      "name": "pci_for_each_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev * pdev, int (*)(struct pci_dev *, u16, void *) fn, void * data)
```

```json
{
  "name": "pci_for_each_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584647392,
      "name": "pci_for_each_dma_alias",
      "external": true,
      "loc": "drivers/pci/search.c:28",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_msi_get_device_domain",
        "drivers/pci/msi.c:pci_msi_domain_get_msi_rid",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/amd_iommu.c:alloc_irq_table",
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_table",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584647392,
      "name": "pci_for_each_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev * pdev, int (*)(struct pci_dev *, u16, void *) fn, void * data)
```

```json
{
  "name": "pci_for_each_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585331280,
      "name": "pci_for_each_dma_alias",
      "external": true,
      "loc": "drivers/pci/search.c:28",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_msi_get_device_domain",
        "drivers/pci/msi.c:pci_msi_domain_get_msi_rid",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:update_device_table",
        "drivers/iommu/amd/iommu.c:do_detach",
        "drivers/iommu/amd/iommu.c:do_attach",
        "drivers/iommu/amd/iommu.c:setup_aliases",
        "drivers/iommu/intel/iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel/pasid.c:intel_pasid_alloc_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585331280,
      "name": "pci_for_each_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int pci_for_each_dma_alias(struct pci_dev * pdev, int (*)(struct pci_dev *, u16, void *) fn, void * data)
```

```json
{
  "name": "pci_for_each_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585484512,
      "name": "pci_for_each_dma_alias",
      "external": true,
      "loc": "drivers/pci/search.c:28",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_msi_get_device_domain",
        "drivers/pci/msi.c:pci_msi_domain_get_msi_rid",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:update_device_table",
        "drivers/iommu/amd/iommu.c:do_detach",
        "drivers/iommu/amd/iommu.c:do_attach",
        "drivers/iommu/amd/iommu.c:setup_aliases",
        "drivers/iommu/intel/iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel/pasid.c:intel_pasid_alloc_table",
        "drivers/iommu/iommu.c:pci_device_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585484512,
      "name": "pci_for_each_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int pci_for_each_dma_alias(struct pci_dev * pdev, int (*)(struct pci_dev *, u16, void *) fn, void * data)
```

```json
{
  "name": "pci_for_each_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585364576,
      "name": "pci_for_each_dma_alias",
      "external": true,
      "loc": "drivers/pci/search.c:28",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id",
        "drivers/pci/msi.c:pci_msi_get_device_domain",
        "drivers/pci/msi.c:pci_msi_domain_get_msi_rid",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:update_device_table",
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/amd/iommu.c:do_detach",
        "drivers/iommu/amd/iommu.c:setup_aliases",
        "drivers/iommu/intel/iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel/pasid.c:intel_pasid_alloc_table",
        "drivers/iommu/iommu.c:pci_device_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585364576,
      "name": "pci_for_each_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
int pci_for_each_dma_alias(struct pci_dev * pdev, int (*)(struct pci_dev *, u16, void *) fn, void * data)
```

```json
{
  "name": "pci_for_each_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585823984,
      "name": "pci_for_each_dma_alias",
      "external": true,
      "loc": "drivers/pci/search.c:28",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id",
        "drivers/pci/msi.c:pci_msi_get_device_domain",
        "drivers/pci/msi.c:pci_msi_domain_get_msi_rid",
        "drivers/acpi/viot.c:viot_iommu_configure",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:update_device_table",
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/amd/iommu.c:do_detach",
        "drivers/iommu/amd/iommu.c:setup_aliases",
        "drivers/iommu/intel/iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel/pasid.c:intel_pasid_alloc_table",
        "drivers/iommu/iommu.c:pci_device_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585823984,
      "name": "pci_for_each_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
int pci_for_each_dma_alias(struct pci_dev * pdev, int (*)(struct pci_dev *, u16, void *) fn, void * data)
```

```json
{
  "name": "pci_for_each_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587014624,
      "name": "pci_for_each_dma_alias",
      "external": true,
      "loc": "drivers/pci/search.c:28",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id",
        "drivers/pci/msi/irqdomain.c:pci_msi_get_device_domain",
        "drivers/pci/msi/irqdomain.c:pci_msi_domain_get_msi_rid",
        "drivers/acpi/viot.c:viot_iommu_configure",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:update_device_table",
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/amd/iommu.c:do_detach",
        "drivers/iommu/amd/iommu.c:setup_aliases",
        "drivers/iommu/intel/iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel/iommu.c:domain_add_dev_info",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/iommu.c:pci_device_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587014624,
      "name": "pci_for_each_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
int pci_for_each_dma_alias(struct pci_dev * pdev, int (*)(struct pci_dev *, u16, void *) fn, void * data)
```

```json
{
  "name": "pci_for_each_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588184800,
      "name": "pci_for_each_dma_alias",
      "external": true,
      "loc": "drivers/pci/search.c:28",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id",
        "drivers/pci/msi/irqdomain.c:pci_msi_get_device_domain",
        "drivers/pci/msi/irqdomain.c:pci_msi_domain_get_msi_rid",
        "drivers/acpi/viot.c:viot_iommu_configure",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/intel/iommu.c:intel_iommu_release_device",
        "drivers/iommu/intel/iommu.c:device_block_translation",
        "drivers/iommu/intel/iommu.c:dmar_domain_attach_device",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/iommu.c:pci_device_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588184800,
      "name": "pci_for_each_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
int pci_for_each_dma_alias(struct pci_dev * pdev, int (*)(struct pci_dev *, u16, void *) fn, void * data)
```

```json
{
  "name": "pci_for_each_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588460784,
      "name": "pci_for_each_dma_alias",
      "external": true,
      "loc": "drivers/pci/search.c:28",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id",
        "drivers/pci/msi/irqdomain.c:pci_msi_get_device_domain",
        "drivers/pci/msi/irqdomain.c:pci_msi_domain_get_msi_rid",
        "drivers/acpi/viot.c:viot_iommu_configure",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/intel/iommu.c:intel_iommu_release_device",
        "drivers/iommu/intel/iommu.c:device_block_translation",
        "drivers/iommu/intel/iommu.c:dmar_domain_attach_device",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/iommu.c:pci_device_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588460784,
      "name": "pci_for_each_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
int pci_for_each_dma_alias(struct pci_dev * pdev, int (*)(struct pci_dev *, u16, void *) fn, void * data)
```

```json
{
  "name": "pci_for_each_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588758080,
      "name": "pci_for_each_dma_alias",
      "external": true,
      "loc": "drivers/pci/search.c:28",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id",
        "drivers/pci/msi/irqdomain.c:pci_msi_get_device_domain",
        "drivers/pci/msi/irqdomain.c:pci_msi_domain_get_msi_rid",
        "drivers/acpi/viot.c:viot_iommu_configure",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/intel/iommu.c:intel_iommu_release_device",
        "drivers/iommu/intel/iommu.c:device_block_translation",
        "drivers/iommu/intel/iommu.c:dmar_domain_attach_device",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/iommu.c:pci_device_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588758080,
      "name": "pci_for_each_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev * pdev, int (*)(struct pci_dev *, u16, void *) fn, void * data)
```

```json
{
  "name": "pci_for_each_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496893616,
      "name": "pci_for_each_dma_alias",
      "external": true,
      "loc": "drivers/pci/search.c:28",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_prepare",
        "drivers/pci/msi.c:pci_msi_get_device_domain",
        "drivers/pci/msi.c:pci_msi_domain_get_msi_rid",
        "drivers/acpi/arm64/iort.c:iort_iommu_configure",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/of_iommu.c:of_iommu_configure",
        "drivers/iommu/arm-smmu.c:arm_smmu_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496893616,
      "name": "pci_for_each_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev * pdev, int (*)(struct pci_dev *, u16, void *) fn, void * data)
```

```json
{
  "name": "pci_for_each_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230171504,
      "name": "pci_for_each_dma_alias",
      "external": true,
      "loc": "drivers/pci/search.c:28",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_prepare",
        "drivers/pci/msi.c:pci_msi_get_device_domain",
        "drivers/pci/msi.c:pci_msi_domain_get_msi_rid",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/of_iommu.c:of_iommu_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230171504,
      "name": "pci_for_each_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev * pdev, int (*)(struct pci_dev *, u16, void *) fn, void * data)
```

```json
{
  "name": "pci_for_each_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290981888,
      "name": "pci_for_each_dma_alias",
      "external": true,
      "loc": "drivers/pci/search.c:28",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/of_iommu.c:of_iommu_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290981888,
      "name": "pci_for_each_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev * pdev, int (*)(struct pci_dev *, u16, void *) fn, void * data)
```

```json
{
  "name": "pci_for_each_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275586236,
      "name": "pci_for_each_dma_alias",
      "external": true,
      "loc": "drivers/pci/search.c:28",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_msi_get_device_domain",
        "drivers/pci/msi.c:pci_msi_domain_get_msi_rid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275586236,
      "name": "pci_for_each_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev * pdev, int (*)(struct pci_dev *, u16, void *) fn, void * data)
```

```json
{
  "name": "pci_for_each_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584597872,
      "name": "pci_for_each_dma_alias",
      "external": true,
      "loc": "drivers/pci/search.c:28",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_msi_get_device_domain",
        "drivers/pci/msi.c:pci_msi_domain_get_msi_rid",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/amd_iommu.c:alloc_irq_table",
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_table",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584597872,
      "name": "pci_for_each_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev * pdev, int (*)(struct pci_dev *, u16, void *) fn, void * data)
```

```json
{
  "name": "pci_for_each_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584527680,
      "name": "pci_for_each_dma_alias",
      "external": true,
      "loc": "drivers/pci/search.c:28",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_msi_get_device_domain",
        "drivers/pci/msi.c:pci_msi_domain_get_msi_rid",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/amd_iommu.c:alloc_irq_table",
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_table",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584527680,
      "name": "pci_for_each_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev * pdev, int (*)(struct pci_dev *, u16, void *) fn, void * data)
```

```json
{
  "name": "pci_for_each_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584597552,
      "name": "pci_for_each_dma_alias",
      "external": true,
      "loc": "drivers/pci/search.c:28",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_msi_get_device_domain",
        "drivers/pci/msi.c:pci_msi_domain_get_msi_rid",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/amd_iommu.c:alloc_irq_table",
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_table",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584597552,
      "name": "pci_for_each_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev * pdev, int (*)(struct pci_dev *, u16, void *) fn, void * data)
```

```json
{
  "name": "pci_for_each_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584705248,
      "name": "pci_for_each_dma_alias",
      "external": true,
      "loc": "drivers/pci/search.c:28",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_msi_get_device_domain",
        "drivers/pci/msi.c:pci_msi_domain_get_msi_rid",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/amd_iommu.c:alloc_irq_table",
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_table",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584705248,
      "name": "pci_for_each_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
    }
  ]
}
```
</details>
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
