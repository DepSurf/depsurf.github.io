# Function: <code>read_pci_config</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586162736,
      "name": "read_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:10",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:early_dump_pci_device",
        "arch/x86/pci/early.c:early_dump_pci_devices"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/early-quirks.c:intel_stolen_base",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_bus_has_devices",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586162736,
      "name": "read_pci_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586576805,
      "name": "read_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:10",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:early_dump_pci_devices",
        "arch/x86/pci/early.c:early_dump_pci_device"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_base",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_bus_has_devices",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586576048,
      "name": "read_pci_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586758373,
      "name": "read_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:10",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:early_dump_pci_devices",
        "arch/x86/pci/early.c:early_dump_pci_device"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_base",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_bus_has_devices",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586757616,
      "name": "read_pci_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586885238,
      "name": "read_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:10",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:early_dump_pci_devices",
        "arch/x86/pci/early.c:early_dump_pci_device"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_base",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_bus_has_devices",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586884528,
      "name": "read_pci_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587373926,
      "name": "read_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:11",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:early_dump_pci_devices",
        "arch/x86/pci/early.c:early_dump_pci_device"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_base",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_bus_has_devices",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587373216,
      "name": "read_pci_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587677572,
      "name": "read_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:11",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:early_dump_pci_devices",
        "arch/x86/pci/early.c:early_dump_pci_device"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:gen11_stolen_base",
        "arch/x86/kernel/early-quirks.c:gen11_stolen_base",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_base",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/pci-calgary_64.c:detect_calgary",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_bus_has_devices",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587677040,
      "name": "read_pci_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587808336,
      "name": "read_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:11",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:gen11_stolen_base",
        "arch/x86/kernel/early-quirks.c:gen11_stolen_base",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_base",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/pci-calgary_64.c:detect_calgary",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_bus_has_devices",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587808336,
      "name": "read_pci_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588113808,
      "name": "read_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:11",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:gen11_stolen_base",
        "arch/x86/kernel/early-quirks.c:gen11_stolen_base",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_base",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/pci-calgary_64.c:detect_calgary",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_bus_has_devices",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588113808,
      "name": "read_pci_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588319504,
      "name": "read_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:11",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:gen11_stolen_base",
        "arch/x86/kernel/early-quirks.c:gen11_stolen_base",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_base",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/pci-calgary_64.c:detect_calgary",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_bus_has_devices",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588319504,
      "name": "read_pci_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591139840,
      "name": "read_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:11",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:gen11_stolen_base",
        "arch/x86/kernel/early-quirks.c:gen11_stolen_base",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_base",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:read_agp",
        "arch/x86/kernel/aperture_64.c:read_agp",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_cap_cpus",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/iommu/amd/init.c:early_amd_iommu_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff",
        "drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "arch/x86/pci/amd_bus.c:pci_enable_pci_io_ecs",
        "arch/x86/pci/amd_bus.c:pci_enable_pci_io_ecs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591139840,
      "name": "read_pci_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591224064,
      "name": "read_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:11",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:gen11_stolen_base",
        "arch/x86/kernel/early-quirks.c:gen11_stolen_base",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_base",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:read_agp",
        "arch/x86/kernel/aperture_64.c:read_agp",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_cap_cpus",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/iommu/amd/init.c:detect_ivrs",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff",
        "drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "arch/x86/pci/amd_bus.c:pci_enable_pci_io_ecs",
        "arch/x86/pci/amd_bus.c:pci_enable_pci_io_ecs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591224064,
      "name": "read_pci_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591173312,
      "name": "read_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:11",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:gen11_stolen_base",
        "arch/x86/kernel/early-quirks.c:gen11_stolen_base",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_base",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:read_agp",
        "arch/x86/kernel/aperture_64.c:read_agp",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff",
        "drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591173312,
      "name": "read_pci_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592026832,
      "name": "read_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:11",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:gen11_stolen_base",
        "arch/x86/kernel/early-quirks.c:gen11_stolen_base",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_base",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:read_agp",
        "arch/x86/kernel/aperture_64.c:read_agp",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff",
        "drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592026832,
      "name": "read_pci_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593793872,
      "name": "read_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:11",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:gen11_stolen_base",
        "arch/x86/kernel/early-quirks.c:gen11_stolen_base",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_base",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:read_agp",
        "arch/x86/kernel/aperture_64.c:read_agp",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff",
        "drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593793872,
      "name": "read_pci_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595737056,
      "name": "read_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:11",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:gen11_stolen_base",
        "arch/x86/kernel/early-quirks.c:gen11_stolen_base",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_base",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:read_agp",
        "arch/x86/kernel/aperture_64.c:read_agp",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff",
        "drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595737056,
      "name": "read_pci_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596263040,
      "name": "read_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:11",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:gen11_stolen_base",
        "arch/x86/kernel/early-quirks.c:gen11_stolen_base",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_base",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:read_agp",
        "arch/x86/kernel/aperture_64.c:read_agp",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff",
        "drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596263040,
      "name": "read_pci_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597145696,
      "name": "read_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:11",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:gen11_stolen_base",
        "arch/x86/kernel/early-quirks.c:gen11_stolen_base",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_base",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:read_agp",
        "arch/x86/kernel/aperture_64.c:read_agp",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff",
        "drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597145696,
      "name": "read_pci_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587923152,
      "name": "read_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:11",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:gen11_stolen_base",
        "arch/x86/kernel/early-quirks.c:gen11_stolen_base",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_base",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/pci-calgary_64.c:detect_calgary",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_bus_has_devices",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587923152,
      "name": "read_pci_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587639008,
      "name": "read_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:11",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:gen11_stolen_base",
        "arch/x86/kernel/early-quirks.c:gen11_stolen_base",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_base",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/pci-calgary_64.c:detect_calgary",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_bus_has_devices",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587639008,
      "name": "read_pci_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588256560,
      "name": "read_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:11",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:gen11_stolen_base",
        "arch/x86/kernel/early-quirks.c:gen11_stolen_base",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_base",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/pci-calgary_64.c:detect_calgary",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_bus_has_devices",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588256560,
      "name": "read_pci_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588392080,
      "name": "read_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:11",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:gen11_stolen_base",
        "arch/x86/kernel/early-quirks.c:gen11_stolen_base",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_base",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs_contd",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/pci-calgary_64.c:detect_calgary",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_bus_has_devices",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588392080,
      "name": "read_pci_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset)
```
</details>
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
