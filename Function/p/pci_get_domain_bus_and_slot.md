# Function: <code>pci_get_domain_bus_and_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pci_dev * pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_domain_bus_and_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583280256,
      "name": "pci_get_domain_bus_and_slot",
      "external": true,
      "loc": "drivers/pci/search.c:220",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer/aerdrv_core.c:aer_recover_work_func",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/firmware/edd.c:edd_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583280256,
      "name": "pci_get_domain_bus_and_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
struct pci_dev * pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_domain_bus_and_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583591328,
      "name": "pci_get_domain_bus_and_slot",
      "external": true,
      "loc": "drivers/pci/search.c:224",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer/aerdrv_core.c:aer_recover_work_func",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/firmware/edd.c:edd_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583591328,
      "name": "pci_get_domain_bus_and_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
struct pci_dev * pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_domain_bus_and_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583728464,
      "name": "pci_get_domain_bus_and_slot",
      "external": true,
      "loc": "drivers/pci/search.c:224",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer/aerdrv_core.c:aer_recover_work_func",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/firmware/edd.c:edd_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583728464,
      "name": "pci_get_domain_bus_and_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
struct pci_dev * pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_domain_bus_and_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583769312,
      "name": "pci_get_domain_bus_and_slot",
      "external": true,
      "loc": "drivers/pci/search.c:228",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer/aerdrv_core.c:aer_recover_work_func",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583769312,
      "name": "pci_get_domain_bus_and_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct pci_dev * pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_domain_bus_and_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584029136,
      "name": "pci_get_domain_bus_and_slot",
      "external": true,
      "loc": "drivers/pci/search.c:228",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer/aerdrv_core.c:aer_recover_work_func",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584029136,
      "name": "pci_get_domain_bus_and_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct pci_dev * pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_domain_bus_and_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584226400,
      "name": "pci_get_domain_bus_and_slot",
      "external": true,
      "loc": "drivers/pci/search.c:229",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_gpu_hda",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/firmware/edd.c:edd_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584226400,
      "name": "pci_get_domain_bus_and_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct pci_dev * pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_domain_bus_and_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584316048,
      "name": "pci_get_domain_bus_and_slot",
      "external": true,
      "loc": "drivers/pci/search.c:229",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_gpu_hda",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/firmware/edd.c:edd_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584316048,
      "name": "pci_get_domain_bus_and_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct pci_dev * pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_domain_bus_and_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584511024,
      "name": "pci_get_domain_bus_and_slot",
      "external": true,
      "loc": "drivers/pci/search.c:225",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/firmware/edd.c:edd_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584511024,
      "name": "pci_get_domain_bus_and_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct pci_dev * pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_domain_bus_and_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584647040,
      "name": "pci_get_domain_bus_and_slot",
      "external": true,
      "loc": "drivers/pci/search.c:224",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/firmware/edd.c:edd_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584647040,
      "name": "pci_get_domain_bus_and_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct pci_dev * pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_domain_bus_and_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585330224,
      "name": "pci_get_domain_bus_and_slot",
      "external": true,
      "loc": "drivers/pci/search.c:230",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585330224,
      "name": "pci_get_domain_bus_and_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct pci_dev * pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_domain_bus_and_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585483456,
      "name": "pci_get_domain_bus_and_slot",
      "external": true,
      "loc": "drivers/pci/search.c:230",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault",
        "drivers/iommu/amd/iommu.c:amd_iommu_report_rmp_fault",
        "drivers/iommu/amd/iommu.c:amd_iommu_report_rmp_hw_error",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585483456,
      "name": "pci_get_domain_bus_and_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct pci_dev * pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_domain_bus_and_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585363024,
      "name": "pci_get_domain_bus_and_slot",
      "external": true,
      "loc": "drivers/pci/search.c:228",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pci_init",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/firmware/edd.c:edd_device_register",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585363024,
      "name": "pci_get_domain_bus_and_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
struct pci_dev * pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_domain_bus_and_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585822400,
      "name": "pci_get_domain_bus_and_slot",
      "external": true,
      "loc": "drivers/pci/search.c:228",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pci_init",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/acpi/viot.c:viot_get_iommu",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/firmware/edd.c:edd_device_register",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585822400,
      "name": "pci_get_domain_bus_and_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
struct pci_dev * pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_domain_bus_and_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587012848,
      "name": "pci_get_domain_bus_and_slot",
      "external": true,
      "loc": "drivers/pci/search.c:228",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pci_init",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/edr.c:edr_handle_event",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/vgaarb.c:vga_arb_write",
        "drivers/acpi/viot.c:viot_get_iommu",
        "drivers/clk/x86/clk-fch.c:fch_clk_remove",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/firmware/edd.c:edd_device_register",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587012848,
      "name": "pci_get_domain_bus_and_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
struct pci_dev * pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_domain_bus_and_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588182944,
      "name": "pci_get_domain_bus_and_slot",
      "external": true,
      "loc": "drivers/pci/search.c:228",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pci_init",
        "arch/x86/events/intel/uncore_snbep.c:discover_upi_topology",
        "arch/x86/events/intel/uncore_snbep.c:skx_upi_topology_cb",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/edr.c:edr_handle_event",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/vgaarb.c:vga_arb_write",
        "drivers/acpi/viot.c:viot_get_iommu",
        "drivers/clk/x86/clk-fch.c:fch_clk_remove",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe",
        "drivers/iommu/amd/iommu.c:iommu_print_event",
        "drivers/iommu/amd/iommu.c:iommu_print_event",
        "drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/intel/svm.c:prq_event_thread",
        "drivers/firmware/edd.c:edd_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588182944,
      "name": "pci_get_domain_bus_and_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
struct pci_dev * pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_domain_bus_and_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588458944,
      "name": "pci_get_domain_bus_and_slot",
      "external": true,
      "loc": "drivers/pci/search.c:228",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pci_init",
        "arch/x86/events/intel/uncore_snbep.c:discover_upi_topology",
        "arch/x86/events/intel/uncore_snbep.c:skx_upi_topology_cb",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/edr.c:edr_handle_event",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/vgaarb.c:vga_arb_write",
        "drivers/acpi/viot.c:viot_get_iommu",
        "drivers/clk/x86/clk-fch.c:fch_clk_remove",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe",
        "drivers/iommu/amd/iommu.c:iommu_print_event",
        "drivers/iommu/amd/iommu.c:iommu_print_event",
        "drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/intel/svm.c:prq_event_thread",
        "drivers/firmware/edd.c:edd_init",
        "drivers/platform/x86/intel/pmc/core_ssram.c:pmc_core_ssram_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588458944,
      "name": "pci_get_domain_bus_and_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
struct pci_dev * pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_domain_bus_and_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588756032,
      "name": "pci_get_domain_bus_and_slot",
      "external": true,
      "loc": "drivers/pci/search.c:228",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pci_init",
        "arch/x86/events/intel/uncore_snbep.c:discover_upi_topology",
        "arch/x86/events/intel/uncore_snbep.c:skx_upi_topology_cb",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/edr.c:edr_handle_event",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/vgaarb.c:vga_arb_write",
        "drivers/acpi/viot.c:viot_get_iommu",
        "drivers/clk/x86/clk-fch.c:fch_clk_remove",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe",
        "drivers/iommu/amd/iommu.c:iommu_print_event",
        "drivers/iommu/amd/iommu.c:iommu_print_event",
        "drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/intel/svm.c:prq_event_thread",
        "drivers/firmware/edd.c:edd_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588756032,
      "name": "pci_get_domain_bus_and_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
struct pci_dev * pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_domain_bus_and_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496893200,
      "name": "pci_get_domain_bus_and_slot",
      "external": true,
      "loc": "drivers/pci/search.c:224",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/syscall.c:__arm64_sys_pciconfig_write",
        "drivers/pci/syscall.c:__arm64_sys_pciconfig_read",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496893200,
      "name": "pci_get_domain_bus_and_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
struct pci_dev * pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_domain_bus_and_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230171016,
      "name": "pci_get_domain_bus_and_slot",
      "external": true,
      "loc": "drivers/pci/search.c:224",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/syscall.c:__se_sys_pciconfig_write",
        "drivers/pci/syscall.c:__se_sys_pciconfig_read",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230171016,
      "name": "pci_get_domain_bus_and_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct pci_dev * pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_domain_bus_and_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290981296,
      "name": "pci_get_domain_bus_and_slot",
      "external": true,
      "loc": "drivers/pci/search.c:224",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/eeh.c:eeh_dev_break_write",
        "arch/powerpc/kernel/eeh.c:eeh_dev_check_write",
        "arch/powerpc/kernel/pci_dn.c:pci_remove_device_node_info",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/syscall.c:__se_sys_pciconfig_write",
        "drivers/pci/syscall.c:__se_sys_pciconfig_read",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290981296,
      "name": "pci_get_domain_bus_and_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
struct pci_dev * pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_domain_bus_and_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275585944,
      "name": "pci_get_domain_bus_and_slot",
      "external": true,
      "loc": "drivers/pci/search.c:224",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275585944,
      "name": "pci_get_domain_bus_and_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct pci_dev * pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_domain_bus_and_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584597520,
      "name": "pci_get_domain_bus_and_slot",
      "external": true,
      "loc": "drivers/pci/search.c:224",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/firmware/edd.c:edd_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584597520,
      "name": "pci_get_domain_bus_and_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct pci_dev * pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_domain_bus_and_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584527328,
      "name": "pci_get_domain_bus_and_slot",
      "external": true,
      "loc": "drivers/pci/search.c:224",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/firmware/edd.c:edd_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584527328,
      "name": "pci_get_domain_bus_and_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct pci_dev * pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_domain_bus_and_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584597200,
      "name": "pci_get_domain_bus_and_slot",
      "external": true,
      "loc": "drivers/pci/search.c:224",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/firmware/edd.c:edd_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584597200,
      "name": "pci_get_domain_bus_and_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct pci_dev * pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_domain_bus_and_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584704896,
      "name": "pci_get_domain_bus_and_slot",
      "external": true,
      "loc": "drivers/pci/search.c:224",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/firmware/edd.c:edd_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584704896,
      "name": "pci_get_domain_bus_and_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
