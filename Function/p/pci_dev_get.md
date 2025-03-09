# Function: <code>pci_dev_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pci_dev * pci_dev_get(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583272480,
      "name": "pci_dev_get",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1375",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/search.c:pci_get_slot",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device",
        "arch/x86/pci/i386.c:pcibios_allocate_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583272480,
      "name": "pci_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct pci_dev * pci_dev_get(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583590142,
      "name": "pci_dev_get",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1372",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/pci.c:pci_bridge_d3_update",
        "drivers/pci/search.c:pci_get_slot",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device",
        "arch/x86/pci/i386.c:pcibios_allocate_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583583472,
      "name": "pci_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct pci_dev * pci_dev_get(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583727294,
      "name": "pci_dev_get",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1381",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/search.c:pci_get_slot",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device",
        "arch/x86/pci/i386.c:pcibios_allocate_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583720560,
      "name": "pci_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pci_dev * pci_dev_get(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583768171,
      "name": "pci_dev_get",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1399",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "drivers/pci/search.c:pci_get_slot",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device",
        "arch/x86/pci/i386.c:pcibios_allocate_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583761424,
      "name": "pci_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pci_dev * pci_dev_get(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584027979,
      "name": "pci_dev_get",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1468",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "drivers/pci/search.c:pci_get_slot",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device",
        "arch/x86/pci/i386.c:pcibios_allocate_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584020816,
      "name": "pci_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pci_dev * pci_dev_get(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584225099,
      "name": "pci_dev_get",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1489",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/search.c:pci_get_slot",
        "drivers/pci/pcie/err.c:pcie_do_fatal_recovery",
        "drivers/pci/pcie/err.c:pcie_do_fatal_recovery",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device",
        "arch/x86/pci/i386.c:pcibios_allocate_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584217488,
      "name": "pci_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pci_dev * pci_dev_get(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584314747,
      "name": "pci_dev_get",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1486",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/search.c:pci_get_slot",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device",
        "arch/x86/pci/i386.c:pcibios_allocate_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584307104,
      "name": "pci_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pci_dev * pci_dev_get(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584509653,
      "name": "pci_dev_get",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1520",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/search.c:pci_get_slot",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device",
        "arch/x86/pci/i386.c:pcibios_allocate_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584502096,
      "name": "pci_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pci_dev * pci_dev_get(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584645685,
      "name": "pci_dev_get",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1533",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/search.c:pci_get_slot",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device",
        "arch/x86/pci/i386.c:pcibios_allocate_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584638096,
      "name": "pci_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pci_dev * pci_dev_get(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585328993,
      "name": "pci_dev_get",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1498",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/search.c:pci_get_slot",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arbiter_del_pci_device",
        "arch/x86/pci/i386.c:pcibios_save_fw_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585320928,
      "name": "pci_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pci_dev * pci_dev_get(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585482273,
      "name": "pci_dev_get",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1477",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/search.c:pci_get_slot",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arbiter_del_pci_device",
        "arch/x86/pci/i386.c:pcibios_save_fw_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585474256,
      "name": "pci_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pci_dev * pci_dev_get(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585361893,
      "name": "pci_dev_get",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1477",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/search.c:pci_get_slot",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/gpu/vga/vgaarb.c:pci_notify",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "arch/x86/pci/i386.c:pcibios_allocate_dev_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585354128,
      "name": "pci_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct pci_dev * pci_dev_get(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585821236,
      "name": "pci_dev_get",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1491",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/search.c:pci_get_slot",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/gpu/vga/vgaarb.c:pci_notify",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "arch/x86/pci/i386.c:pcibios_allocate_dev_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585813248,
      "name": "pci_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pci_dev * pci_dev_get(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587011742,
      "name": "pci_dev_get",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1520",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/search.c:pci_get_slot",
        "drivers/pci/pcie/aer.c:find_device_iter",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_from_pci_bridge",
        "drivers/pci/pcie/edr.c:edr_handle_event",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/pci/vgaarb.c:pci_notify",
        "drivers/pci/vgaarb.c:vga_arb_write",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "arch/x86/pci/i386.c:pcibios_allocate_dev_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587002704,
      "name": "pci_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct pci_dev * pci_dev_get(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588181726,
      "name": "pci_dev_get",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1526",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/search.c:pci_get_slot",
        "drivers/pci/pcie/aer.c:find_device_iter",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_from_pci_bridge",
        "drivers/pci/pcie/edr.c:edr_handle_event",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/pci/p2pdma.c:pci_p2pmem_find_many",
        "drivers/pci/p2pdma.c:pci_p2pmem_find_many",
        "drivers/pci/vgaarb.c:pci_notify",
        "drivers/pci/vgaarb.c:vga_arb_write",
        "drivers/pci/vgaarb.c:vga_arbiter_add_pci_device",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "arch/x86/pci/i386.c:pcibios_allocate_dev_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588171904,
      "name": "pci_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct pci_dev * pci_dev_get(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588457726,
      "name": "pci_dev_get",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1527",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/search.c:pci_get_slot",
        "drivers/pci/pcie/aer.c:find_device_iter",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_from_pci_bridge",
        "drivers/pci/pcie/edr.c:edr_handle_event",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/pci/p2pdma.c:pci_p2pmem_find_many",
        "drivers/pci/p2pdma.c:pci_p2pmem_find_many",
        "drivers/pci/vgaarb.c:pci_notify",
        "drivers/pci/vgaarb.c:vga_arb_write",
        "drivers/pci/vgaarb.c:vga_arbiter_add_pci_device",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "arch/x86/pci/i386.c:pcibios_allocate_dev_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588447936,
      "name": "pci_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct pci_dev * pci_dev_get(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588754830,
      "name": "pci_dev_get",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1540",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/search.c:pci_get_slot",
        "drivers/pci/pcie/aer.c:find_device_iter",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_from_pci_bridge",
        "drivers/pci/pcie/edr.c:edr_handle_event",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/pci/p2pdma.c:pci_p2pmem_find_many",
        "drivers/pci/p2pdma.c:pci_p2pmem_find_many",
        "drivers/pci/vgaarb.c:pci_notify",
        "drivers/pci/vgaarb.c:vga_arb_write",
        "drivers/pci/vgaarb.c:vga_arbiter_add_pci_device",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "arch/x86/pci/i386.c:pcibios_allocate_dev_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588744880,
      "name": "pci_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct pci_dev * pci_dev_get(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496891456,
      "name": "pci_dev_get",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1533",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "drivers/pci/search.c:pci_get_slot",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496884432,
      "name": "pci_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct pci_dev * pci_dev_get(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230169412,
      "name": "pci_dev_get",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1533",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "drivers/pci/search.c:pci_get_slot",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230161328,
      "name": "pci_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct pci_dev * pci_dev_get(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290979008,
      "name": "pci_dev_get",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1533",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_fixup",
        "drivers/pci/search.c:pci_get_slot",
        "drivers/pci/search.c:pci_get_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290969488,
      "name": "pci_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct pci_dev * pci_dev_get(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275584712,
      "name": "pci_dev_get",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1533",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "drivers/pci/search.c:pci_get_slot",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275581406,
      "name": "pci_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct pci_dev * pci_dev_get(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584596165,
      "name": "pci_dev_get",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1533",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/search.c:pci_get_slot",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device",
        "arch/x86/pci/i386.c:pcibios_allocate_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584590256,
      "name": "pci_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct pci_dev * pci_dev_get(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584525973,
      "name": "pci_dev_get",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1533",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/search.c:pci_get_slot",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device",
        "arch/x86/pci/i386.c:pcibios_allocate_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584518384,
      "name": "pci_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct pci_dev * pci_dev_get(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584595845,
      "name": "pci_dev_get",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1533",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/search.c:pci_get_slot",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device",
        "arch/x86/pci/i386.c:pcibios_allocate_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584588256,
      "name": "pci_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct pci_dev * pci_dev_get(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584703541,
      "name": "pci_dev_get",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1533",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/search.c:pci_get_slot",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device",
        "arch/x86/pci/i386.c:pcibios_allocate_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584696304,
      "name": "pci_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
