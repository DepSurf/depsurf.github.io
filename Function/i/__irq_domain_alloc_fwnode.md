# Function: <code>__irq_domain_alloc_fwnode</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct fwnode_handle * __irq_domain_alloc_fwnode(unsigned int type, int id, const char * name, void * data)
```

```json
{
  "name": "__irq_domain_alloc_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579814288,
      "name": "__irq_domain_alloc_fwnode",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:60",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain",
        "arch/x86/kernel/apic/msi.c:arch_init_msi_domain",
        "arch/x86/kernel/apic/htirq.c:arch_init_htirq_domain",
        "drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579814288,
      "name": "__irq_domain_alloc_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
struct fwnode_handle * __irq_domain_alloc_fwnode(unsigned int type, int id, const char * name, void * data)
```

```json
{
  "name": "__irq_domain_alloc_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579849216,
      "name": "__irq_domain_alloc_fwnode",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:62",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain",
        "arch/x86/kernel/apic/msi.c:arch_init_msi_domain",
        "drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579849216,
      "name": "__irq_domain_alloc_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
struct fwnode_handle * __irq_domain_alloc_fwnode(unsigned int type, int id, const char * name, void * data)
```

```json
{
  "name": "__irq_domain_alloc_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579882960,
      "name": "__irq_domain_alloc_fwnode",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:64",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain",
        "arch/x86/kernel/apic/msi.c:arch_init_msi_domain",
        "drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579882960,
      "name": "__irq_domain_alloc_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
struct fwnode_handle * __irq_domain_alloc_fwnode(unsigned int type, int id, const char * name, void * data)
```

```json
{
  "name": "__irq_domain_alloc_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579926144,
      "name": "__irq_domain_alloc_fwnode",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:64",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain",
        "arch/x86/kernel/apic/msi.c:arch_init_msi_domain",
        "drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579926144,
      "name": "__irq_domain_alloc_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
struct fwnode_handle * __irq_domain_alloc_fwnode(unsigned int type, int id, const char * name, void * data)
```

```json
{
  "name": "__irq_domain_alloc_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579964272,
      "name": "__irq_domain_alloc_fwnode",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:64",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain",
        "arch/x86/kernel/apic/msi.c:arch_init_msi_domain",
        "drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain",
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579964272,
      "name": "__irq_domain_alloc_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
struct fwnode_handle * __irq_domain_alloc_fwnode(unsigned int type, int id, const char * name, phys_addr_t * pa)
```

```json
{
  "name": "__irq_domain_alloc_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580014032,
      "name": "__irq_domain_alloc_fwnode",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:64",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain",
        "arch/x86/kernel/apic/msi.c:arch_init_msi_domain",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain",
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014032,
      "name": "__irq_domain_alloc_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
struct fwnode_handle * __irq_domain_alloc_fwnode(unsigned int type, int id, const char * name, phys_addr_t * pa)
```

```json
{
  "name": "__irq_domain_alloc_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580065584,
      "name": "__irq_domain_alloc_fwnode",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:64",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain",
        "arch/x86/kernel/apic/msi.c:arch_init_msi_domain",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain",
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580065584,
      "name": "__irq_domain_alloc_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
struct fwnode_handle * __irq_domain_alloc_fwnode(unsigned int type, int id, const char * name, phys_addr_t * pa)
```

```json
{
  "name": "__irq_domain_alloc_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580047600,
      "name": "__irq_domain_alloc_fwnode",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:73",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain",
        "arch/x86/kernel/apic/msi.c:native_create_pci_msi_domain",
        "arch/x86/kernel/hpet.c:hpet_create_irq_domain",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain",
        "drivers/iommu/amd/init.c:iommu_setup_intcapxt",
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping",
        "arch/x86/pci/xen.c:xen_create_pci_msi_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580047600,
      "name": "__irq_domain_alloc_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
struct fwnode_handle * __irq_domain_alloc_fwnode(unsigned int type, int id, const char * name, phys_addr_t * pa)
```

```json
{
  "name": "__irq_domain_alloc_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580048352,
      "name": "__irq_domain_alloc_fwnode",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:73",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_create_pci_msi_domain",
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain",
        "arch/x86/kernel/apic/msi.c:native_create_pci_msi_domain",
        "arch/x86/kernel/hpet.c:hpet_select_clockevents",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts",
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping",
        "arch/x86/pci/xen.c:xen_create_pci_msi_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580048352,
      "name": "__irq_domain_alloc_fwnode",
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
struct fwnode_handle * __irq_domain_alloc_fwnode(unsigned int type, int id, const char * name, phys_addr_t * pa)
```

```json
{
  "name": "__irq_domain_alloc_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580181376,
      "name": "__irq_domain_alloc_fwnode",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:73",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_create_pci_msi_domain",
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain",
        "arch/x86/kernel/apic/msi.c:native_create_pci_msi_domain",
        "arch/x86/kernel/hpet.c:hpet_select_clockevents",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts",
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping",
        "arch/x86/pci/xen.c:xen_create_pci_msi_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580181376,
      "name": "__irq_domain_alloc_fwnode",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct fwnode_handle * __irq_domain_alloc_fwnode(unsigned int type, int id, const char * name, phys_addr_t * pa)
```

```json
{
  "name": "__irq_domain_alloc_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580329536,
      "name": "__irq_domain_alloc_fwnode",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:73",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_create_pci_msi_domain",
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain",
        "arch/x86/kernel/apic/msi.c:native_create_pci_msi_domain",
        "arch/x86/kernel/hpet.c:hpet_select_clockevents",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts",
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping",
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping",
        "arch/x86/pci/xen.c:xen_create_pci_msi_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580329536,
      "name": "__irq_domain_alloc_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
struct fwnode_handle * __irq_domain_alloc_fwnode(unsigned int type, int id, const char * name, phys_addr_t * pa)
```

```json
{
  "name": "__irq_domain_alloc_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580545520,
      "name": "__irq_domain_alloc_fwnode",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:76",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_create_pci_msi_domain",
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/hpet.c:hpet_select_clockevents",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "kernel/irq/msi.c:msi_create_device_irq_domain",
        "drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts",
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping",
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping",
        "arch/x86/pci/xen.c:xen_create_pci_msi_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580545520,
      "name": "__irq_domain_alloc_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
struct fwnode_handle * __irq_domain_alloc_fwnode(unsigned int type, int id, const char * name, phys_addr_t * pa)
```

```json
{
  "name": "__irq_domain_alloc_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580618976,
      "name": "__irq_domain_alloc_fwnode",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:76",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_create_pci_msi_domain",
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/hpet.c:hpet_select_clockevents",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "kernel/irq/msi.c:msi_create_device_irq_domain",
        "drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts",
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping",
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping",
        "arch/x86/pci/xen.c:xen_create_pci_msi_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580618976,
      "name": "__irq_domain_alloc_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
struct fwnode_handle * __irq_domain_alloc_fwnode(unsigned int type, int id, const char * name, phys_addr_t * pa)
```

```json
{
  "name": "__irq_domain_alloc_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580683872,
      "name": "__irq_domain_alloc_fwnode",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:76",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_create_pci_msi_domain",
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/hpet.c:hpet_select_clockevents",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "kernel/irq/msi.c:msi_create_device_irq_domain",
        "drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain",
        "drivers/iommu/amd/init.c:__iommu_setup_intcapxt",
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping",
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping",
        "arch/x86/pci/xen.c:xen_create_pci_msi_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580683872,
      "name": "__irq_domain_alloc_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
struct fwnode_handle * __irq_domain_alloc_fwnode(unsigned int type, int id, const char * name, phys_addr_t * pa)
```

```json
{
  "name": "__irq_domain_alloc_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491215096,
      "name": "__irq_domain_alloc_fwnode",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:64",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-gic.c:gic_v2_acpi_init",
        "drivers/irqchip/irq-gic-v2m.c:acpi_parse_madt_msi",
        "drivers/irqchip/irq-gic-v3.c:gic_acpi_init",
        "drivers/irqchip/irq-gic-v3-its.c:gic_acpi_parse_madt_its",
        "drivers/irqchip/irq-gic-v4.c:its_alloc_vcpu_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491215096,
      "name": "__irq_domain_alloc_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
struct fwnode_handle * __irq_domain_alloc_fwnode(unsigned int type, int id, const char * name, phys_addr_t * pa)
```

```json
{
  "name": "__irq_domain_alloc_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225230540,
      "name": "__irq_domain_alloc_fwnode",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:64",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-gic-v4.c:its_alloc_vcpu_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225230540,
      "name": "__irq_domain_alloc_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
struct fwnode_handle * __irq_domain_alloc_fwnode(unsigned int type, int id, const char * name, phys_addr_t * pa)
```

```json
{
  "name": "__irq_domain_alloc_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284123840,
      "name": "__irq_domain_alloc_fwnode",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:64",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284123840,
      "name": "__irq_domain_alloc_fwnode",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct fwnode_handle * __irq_domain_alloc_fwnode(unsigned int type, int id, const char * name, phys_addr_t * pa)
```

```json
{
  "name": "__irq_domain_alloc_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271752798,
      "name": "__irq_domain_alloc_fwnode",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:64",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271752798,
      "name": "__irq_domain_alloc_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
struct fwnode_handle * __irq_domain_alloc_fwnode(unsigned int type, int id, const char * name, phys_addr_t * pa)
```

```json
{
  "name": "__irq_domain_alloc_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579982768,
      "name": "__irq_domain_alloc_fwnode",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:64",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain",
        "arch/x86/kernel/apic/msi.c:arch_init_msi_domain",
        "drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain",
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579982768,
      "name": "__irq_domain_alloc_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
struct fwnode_handle * __irq_domain_alloc_fwnode(unsigned int type, int id, const char * name, phys_addr_t * pa)
```

```json
{
  "name": "__irq_domain_alloc_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579920544,
      "name": "__irq_domain_alloc_fwnode",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:64",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain",
        "arch/x86/kernel/apic/msi.c:arch_init_msi_domain",
        "drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain",
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579920544,
      "name": "__irq_domain_alloc_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
struct fwnode_handle * __irq_domain_alloc_fwnode(unsigned int type, int id, const char * name, phys_addr_t * pa)
```

```json
{
  "name": "__irq_domain_alloc_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579974304,
      "name": "__irq_domain_alloc_fwnode",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:64",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain",
        "arch/x86/kernel/apic/msi.c:arch_init_msi_domain",
        "drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain",
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579974304,
      "name": "__irq_domain_alloc_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
struct fwnode_handle * __irq_domain_alloc_fwnode(unsigned int type, int id, const char * name, phys_addr_t * pa)
```

```json
{
  "name": "__irq_domain_alloc_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580020928,
      "name": "__irq_domain_alloc_fwnode",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:64",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain",
        "arch/x86/kernel/apic/msi.c:arch_init_msi_domain",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain",
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580020928,
      "name": "__irq_domain_alloc_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct fwnode_handle * __irq_domain_alloc_fwnode(unsigned int type, int id, const char * name, void * data)
```
</details>
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>phys_addr_t * pa</code>
</li>
<li>
<b>Param removed. </b>
<code>void * data</code>
</li>
</ul>
</details>
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
