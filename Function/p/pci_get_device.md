# Function: <code>pci_get_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pci_dev * pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev * from)
```

```json
{
  "name": "pci_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583280144,
      "name": "pci_get_device",
      "external": true,
      "loc": "drivers/pci/search.c:323",
      "file": "drivers/pci/search.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/kernel/amd_nb.c:next_northbridge",
        "arch/x86/kernel/sysfb_efi.c:efifb_set_system",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/atom/pmc_atom.c:pmc_atom_init",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/proc.c:pci_seq_next",
        "drivers/pci/proc.c:pci_seq_start",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/iommu/iommu.c:get_pci_function_alias_group",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/core/hcd-pci.c:for_each_companion",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "arch/x86/pci/acpi.c:pci_acpi_init",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583280144,
      "name": "pci_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
struct pci_dev * pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev * from)
```

```json
{
  "name": "pci_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583591353,
      "name": "pci_get_device",
      "external": true,
      "loc": "drivers/pci/search.c:327",
      "file": "drivers/pci/search.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/kernel/amd_nb.c:next_northbridge",
        "arch/x86/kernel/sysfb_efi.c:efifb_set_system",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/atom/pmc_atom.c:pmc_atom_init",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_seq_next",
        "drivers/pci/proc.c:pci_seq_start",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/iommu/iommu.c:get_pci_function_alias_group",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/core/hcd-pci.c:for_each_companion",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "arch/x86/pci/acpi.c:pci_acpi_init",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583591216,
      "name": "pci_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
struct pci_dev * pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev * from)
```

```json
{
  "name": "pci_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583728489,
      "name": "pci_get_device",
      "external": true,
      "loc": "drivers/pci/search.c:327",
      "file": "drivers/pci/search.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/kernel/amd_nb.c:next_northbridge",
        "arch/x86/kernel/sysfb_efi.c:efifb_set_system",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/atom/pmc_atom.c:pmc_atom_init",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_seq_next",
        "drivers/pci/proc.c:pci_seq_start",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/iommu/iommu.c:get_pci_function_alias_group",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/core/hcd-pci.c:for_each_companion",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "arch/x86/pci/acpi.c:pci_acpi_init",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583728352,
      "name": "pci_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
struct pci_dev * pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev * from)
```

```json
{
  "name": "pci_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583769336,
      "name": "pci_get_device",
      "external": true,
      "loc": "drivers/pci/search.c:331",
      "file": "drivers/pci/search.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/kernel/amd_nb.c:next_northbridge",
        "arch/x86/kernel/sysfb_efi.c:efifb_set_system",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/setup-irq.c:pci_fixup_irqs",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_seq_next",
        "drivers/pci/proc.c:pci_seq_start",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/core/hcd-pci.c:for_each_companion",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "arch/x86/pci/acpi.c:pci_acpi_init",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583769216,
      "name": "pci_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct pci_dev * pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev * from)
```

```json
{
  "name": "pci_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584029160,
      "name": "pci_get_device",
      "external": true,
      "loc": "drivers/pci/search.c:331",
      "file": "drivers/pci/search.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/kernel/amd_nb.c:next_northbridge",
        "arch/x86/kernel/sysfb_efi.c:efifb_set_system",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_seq_next",
        "drivers/pci/proc.c:pci_seq_start",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/core/hcd-pci.c:for_each_companion",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/acpi.c:pci_acpi_init",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584029040,
      "name": "pci_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct pci_dev * pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev * from)
```

```json
{
  "name": "pci_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584226450,
      "name": "pci_get_device",
      "external": true,
      "loc": "drivers/pci/search.c:332",
      "file": "drivers/pci/search.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/kernel/amd_nb.c:next_northbridge",
        "arch/x86/kernel/sysfb_efi.c:efifb_set_system",
        "arch/x86/kernel/pci-calgary_64.c:calgary_fixup_tce_spaces",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_seq_next",
        "drivers/pci/proc.c:pci_seq_start",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/core/hcd-pci.c:for_each_companion",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_probe",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/acpi.c:pci_acpi_init",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584226304,
      "name": "pci_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct pci_dev * pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev * from)
```

```json
{
  "name": "pci_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584316098,
      "name": "pci_get_device",
      "external": true,
      "loc": "drivers/pci/search.c:332",
      "file": "drivers/pci/search.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/kernel/amd_nb.c:next_northbridge",
        "arch/x86/kernel/sysfb_efi.c:efifb_set_system",
        "arch/x86/kernel/pci-calgary_64.c:calgary_fixup_tce_spaces",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_seq_next",
        "drivers/pci/proc.c:pci_seq_start",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/core/hcd-pci.c:for_each_companion",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/acpi.c:pci_acpi_init",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584315952,
      "name": "pci_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct pci_dev * pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev * from)
```

```json
{
  "name": "pci_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584511067,
      "name": "pci_get_device",
      "external": true,
      "loc": "drivers/pci/search.c:328",
      "file": "drivers/pci/search.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box",
        "arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/kernel/amd_nb.c:next_northbridge",
        "arch/x86/kernel/sysfb_efi.c:efifb_set_system",
        "arch/x86/kernel/pci-calgary_64.c:calgary_fixup_tce_spaces",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_seq_next",
        "drivers/pci/proc.c:pci_seq_start",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/core/hcd-pci.c:for_each_companion",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/acpi.c:pci_acpi_init",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584510928,
      "name": "pci_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct pci_dev * pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev * from)
```

```json
{
  "name": "pci_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584647083,
      "name": "pci_get_device",
      "external": true,
      "loc": "drivers/pci/search.c:327",
      "file": "drivers/pci/search.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box",
        "arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/kernel/amd_nb.c:next_northbridge",
        "arch/x86/kernel/sysfb_efi.c:efifb_set_system",
        "arch/x86/kernel/pci-calgary_64.c:calgary_fixup_tce_spaces",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_seq_next",
        "drivers/pci/proc.c:pci_seq_start",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:has_untrusted_dev",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/core/hcd-pci.c:for_each_companion",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/acpi.c:pci_acpi_init",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584646944,
      "name": "pci_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct pci_dev * pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev * from)
```

```json
{
  "name": "pci_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585330267,
      "name": "pci_get_device",
      "external": true,
      "loc": "drivers/pci/search.c:333",
      "file": "drivers/pci/search.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:setup_ibs_ctl",
        "arch/x86/events/intel/uncore_snb.c:tgl_uncore_imc_freerunning_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:icx_count_chabox",
        "arch/x86/events/intel/uncore_snbep.c:__snr_uncore_mmio_init_box",
        "arch/x86/events/intel/uncore_snbep.c:skx_count_chabox",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/kernel/sysfb_efi.c:efifb_set_system",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_seq_next",
        "drivers/pci/proc.c:pci_seq_start",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/iommu/iommu.c:get_pci_alias_group",
        "drivers/iommu/intel/dmar.c:dmar_dev_scope_init",
        "drivers/iommu/intel/iommu.c:platform_optin_force_iommu",
        "drivers/iommu/intel/iommu.c:dmar_init_reserved_ranges",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/core/hcd-pci.c:for_each_companion",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:amd_chipset_sb_type_init",
        "drivers/usb/host/pci-quirks.c:amd_chipset_sb_type_init",
        "drivers/usb/host/pci-quirks.c:amd_chipset_sb_type_init",
        "drivers/hwmon/hwmon.c:hwmon_pci_quirks",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/acpi.c:pci_acpi_init",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585329920,
      "name": "pci_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct pci_dev * pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev * from)
```

```json
{
  "name": "pci_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585483499,
      "name": "pci_get_device",
      "external": true,
      "loc": "drivers/pci/search.c:333",
      "file": "drivers/pci/search.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:setup_ibs_ctl",
        "arch/x86/events/intel/uncore.c:uncore_pci_sub_driver_init",
        "arch/x86/events/intel/uncore_snb.c:tgl_uncore_imc_freerunning_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:icx_count_chabox",
        "arch/x86/events/intel/uncore_snbep.c:__snr_uncore_mmio_init_box",
        "arch/x86/events/intel/uncore_snbep.c:skx_count_chabox",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/kernel/sysfb_efi.c:efifb_set_system",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_seq_next",
        "drivers/pci/proc.c:pci_seq_start",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/iommu/intel/dmar.c:dmar_dev_scope_init",
        "drivers/iommu/intel/iommu.c:platform_optin_force_iommu",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/iommu.c:get_pci_alias_group",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/core/hcd-pci.c:for_each_companion",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:amd_chipset_sb_type_init",
        "drivers/usb/host/pci-quirks.c:amd_chipset_sb_type_init",
        "drivers/usb/host/pci-quirks.c:amd_chipset_sb_type_init",
        "drivers/hwmon/hwmon.c:hwmon_pci_quirks",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/acpi.c:pci_acpi_init",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585483152,
      "name": "pci_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct pci_dev * pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev * from)
```

```json
{
  "name": "pci_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585363074,
      "name": "pci_get_device",
      "external": true,
      "loc": "drivers/pci/search.c:330",
      "file": "drivers/pci/search.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore.c:uncore_pci_init",
        "arch/x86/events/intel/uncore_snb.c:tgl_uncore_imc_freerunning_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:icx_count_chabox",
        "arch/x86/events/intel/uncore_snbep.c:__snr_uncore_mmio_init_box",
        "arch/x86/events/intel/uncore_snbep.c:skx_count_chabox",
        "arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables",
        "arch/x86/kernel/sysfb_efi.c:efifb_set_system",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_seq_next",
        "drivers/pci/proc.c:pci_seq_start",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/iommu/intel/dmar.c:dmar_dev_scope_init",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/iommu.c:get_pci_alias_group",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/core/hcd-pci.c:for_each_companion",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/acpi.c:pci_acpi_init",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585363440,
      "name": "pci_get_device",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pci_dev * pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev * from)
```

```json
{
  "name": "pci_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585822450,
      "name": "pci_get_device",
      "external": true,
      "loc": "drivers/pci/search.c:330",
      "file": "drivers/pci/search.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore.c:uncore_pci_init",
        "arch/x86/events/intel/uncore_snb.c:tgl_uncore_imc_freerunning_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:icx_count_chabox",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map",
        "arch/x86/events/intel/uncore_snbep.c:skx_count_chabox",
        "arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_seq_next",
        "drivers/pci/proc.c:pci_seq_start",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/iommu/intel/dmar.c:dmar_dev_scope_init",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/iommu.c:get_pci_alias_group",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/core/hcd-pci.c:for_each_companion",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early",
        "drivers/firmware/efi/sysfb_efi.c:efifb_set_system",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/acpi.c:pci_acpi_init",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585822832,
      "name": "pci_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
struct pci_dev * pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev * from)
```

```json
{
  "name": "pci_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587012897,
      "name": "pci_get_device",
      "external": true,
      "loc": "drivers/pci/search.c:330",
      "file": "drivers/pci/search.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore.c:uncore_pci_init",
        "arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:icx_count_chabox",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map",
        "arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology",
        "arch/x86/events/intel/uncore_snbep.c:skx_count_chabox",
        "arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables",
        "arch/x86/kernel/amd_nb.c:next_northbridge",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_seq_next",
        "drivers/pci/proc.c:pci_seq_start",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/iommu/intel/dmar.c:dmar_dev_scope_init",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/iommu.c:get_pci_alias_group",
        "drivers/iommu/iommu.c:get_pci_function_alias_group",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/core/hcd-pci.c:for_each_companion",
        "drivers/usb/host/pci-quirks.c:usb_enable_intel_xhci_ports",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early",
        "drivers/firmware/efi/sysfb_efi.c:efifb_set_system",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/acpi.c:pci_acpi_init",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587013328,
      "name": "pci_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
struct pci_dev * pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev * from)
```

```json
{
  "name": "pci_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588182993,
      "name": "pci_get_device",
      "external": true,
      "loc": "drivers/pci/search.c:330",
      "file": "drivers/pci/search.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore.c:uncore_pci_init",
        "arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:discover_upi_topology",
        "arch/x86/events/intel/uncore_snbep.c:icx_count_chabox",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map",
        "arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology",
        "arch/x86/events/intel/uncore_snbep.c:skx_count_chabox",
        "arch/x86/events/intel/uncore_snbep.c:hswep_has_limit_sbox",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_seq_next",
        "drivers/pci/proc.c:pci_seq_start",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pci/p2pdma.c:pci_p2pmem_find_many",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/iommu/intel/dmar.c:dmar_dev_scope_init",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/iommu.c:get_pci_alias_group",
        "drivers/iommu/iommu.c:get_pci_function_alias_group",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/core/hcd-pci.c:for_each_companion",
        "drivers/usb/host/pci-quirks.c:usb_enable_intel_xhci_ports",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early",
        "drivers/firmware/efi/sysfb_efi.c:efifb_set_system",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/acpi.c:pci_acpi_init",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588183456,
      "name": "pci_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
struct pci_dev * pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev * from)
```

```json
{
  "name": "pci_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588458995,
      "name": "pci_get_device",
      "external": true,
      "loc": "drivers/pci/search.c:330",
      "file": "drivers/pci/search.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore.c:uncore_pci_init",
        "arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:spr_update_device_location",
        "arch/x86/events/intel/uncore_snbep.c:discover_upi_topology",
        "arch/x86/events/intel/uncore_snbep.c:icx_count_chabox",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map",
        "arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology",
        "arch/x86/events/intel/uncore_snbep.c:skx_count_chabox",
        "arch/x86/events/intel/uncore_snbep.c:hswep_has_limit_sbox",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_seq_next",
        "drivers/pci/proc.c:pci_seq_start",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pci/p2pdma.c:pci_p2pmem_find_many",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/iommu/intel/dmar.c:dmar_dev_scope_init",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/iommu.c:get_pci_alias_group",
        "drivers/iommu/iommu.c:get_pci_function_alias_group",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/core/hcd-pci.c:for_each_companion",
        "drivers/usb/host/pci-quirks.c:usb_enable_intel_xhci_ports",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early",
        "drivers/firmware/efi/sysfb_efi.c:efifb_set_system",
        "drivers/platform/x86/intel/pmc/mtl.c:mtl_set_device_d3",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/acpi.c:pci_acpi_init",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588459440,
      "name": "pci_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
struct pci_dev * pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev * from)
```

```json
{
  "name": "pci_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588756083,
      "name": "pci_get_device",
      "external": true,
      "loc": "drivers/pci/search.c:330",
      "file": "drivers/pci/search.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore.c:uncore_pci_init",
        "arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:spr_update_device_location",
        "arch/x86/events/intel/uncore_snbep.c:discover_upi_topology",
        "arch/x86/events/intel/uncore_snbep.c:icx_count_chabox",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map",
        "arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology",
        "arch/x86/events/intel/uncore_snbep.c:skx_count_chabox",
        "arch/x86/events/intel/uncore_snbep.c:hswep_has_limit_sbox",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_seq_next",
        "drivers/pci/proc.c:pci_seq_start",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pci/p2pdma.c:pci_p2pmem_find_many",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/iommu/intel/dmar.c:dmar_dev_scope_init",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/iommu.c:get_pci_alias_group",
        "drivers/iommu/iommu.c:get_pci_function_alias_group",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/core/hcd-pci.c:for_each_companion",
        "drivers/usb/host/pci-quirks.c:usb_enable_intel_xhci_ports",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early",
        "drivers/firmware/efi/sysfb_efi.c:efifb_set_system",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/acpi.c:pci_acpi_init",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588756320,
      "name": "pci_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
struct pci_dev * pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev * from)
```

```json
{
  "name": "pci_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496893264,
      "name": "pci_get_device",
      "external": true,
      "loc": "drivers/pci/search.c:327",
      "file": "drivers/pci/search.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot"
      ],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_seq_next",
        "drivers/pci/proc.c:pci_seq_start",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/usb/core/hcd-pci.c:for_each_companion",
        "drivers/usb/core/hcd-pci.c:for_each_companion",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496893080,
      "name": "pci_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct pci_dev * pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev * from)
```

```json
{
  "name": "pci_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230171084,
      "name": "pci_get_device",
      "external": true,
      "loc": "drivers/pci/search.c:327",
      "file": "drivers/pci/search.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot"
      ],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_seq_next",
        "drivers/pci/proc.c:pci_seq_start",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/usb/core/hcd-pci.c:for_each_companion",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230170880,
      "name": "pci_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct pci_dev * pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev * from)
```

```json
{
  "name": "pci_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290981392,
      "name": "pci_get_device",
      "external": true,
      "loc": "drivers/pci/search.c:327",
      "file": "drivers/pci/search.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot"
      ],
      "caller_func": [
        "arch/powerpc/kernel/pci-common.c:pcibios_allocate_resources",
        "arch/powerpc/kernel/pci-common.c:pci_phys_mem_access_prot",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_seq_next",
        "drivers/pci/proc.c:pci_seq_start",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/video/fbdev/offb.c:offb_init_nodriver",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/usb/core/hcd-pci.c:for_each_companion",
        "drivers/usb/core/hcd-pci.c:for_each_companion",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290981152,
      "name": "pci_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct pci_dev * pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev * from)
```

```json
{
  "name": "pci_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275585976,
      "name": "pci_get_device",
      "external": true,
      "loc": "drivers/pci/search.c:327",
      "file": "drivers/pci/search.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot"
      ],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_seq_next",
        "drivers/pci/proc.c:pci_seq_start",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/usb/core/hcd-pci.c:for_each_companion",
        "drivers/usb/core/hcd-pci.c:for_each_companion",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275585864,
      "name": "pci_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct pci_dev * pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev * from)
```

```json
{
  "name": "pci_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584597563,
      "name": "pci_get_device",
      "external": true,
      "loc": "drivers/pci/search.c:327",
      "file": "drivers/pci/search.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box",
        "arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/kernel/amd_nb.c:next_northbridge",
        "arch/x86/kernel/sysfb_efi.c:efifb_set_system",
        "arch/x86/kernel/pci-calgary_64.c:calgary_fixup_tce_spaces",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_seq_next",
        "drivers/pci/proc.c:pci_seq_start",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:has_untrusted_dev",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/core/hcd-pci.c:for_each_companion",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/acpi.c:pci_acpi_init",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584597424,
      "name": "pci_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct pci_dev * pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev * from)
```

```json
{
  "name": "pci_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584527371,
      "name": "pci_get_device",
      "external": true,
      "loc": "drivers/pci/search.c:327",
      "file": "drivers/pci/search.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box",
        "arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/kernel/amd_nb.c:next_northbridge",
        "arch/x86/kernel/sysfb_efi.c:efifb_set_system",
        "arch/x86/kernel/pci-calgary_64.c:calgary_fixup_tce_spaces",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_seq_next",
        "drivers/pci/proc.c:pci_seq_start",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:has_untrusted_dev",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/core/hcd-pci.c:for_each_companion",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/acpi.c:pci_acpi_init",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584527232,
      "name": "pci_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct pci_dev * pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev * from)
```

```json
{
  "name": "pci_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584597243,
      "name": "pci_get_device",
      "external": true,
      "loc": "drivers/pci/search.c:327",
      "file": "drivers/pci/search.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box",
        "arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/kernel/amd_nb.c:next_northbridge",
        "arch/x86/kernel/sysfb_efi.c:efifb_set_system",
        "arch/x86/kernel/pci-calgary_64.c:calgary_fixup_tce_spaces",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_seq_next",
        "drivers/pci/proc.c:pci_seq_start",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:has_untrusted_dev",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/core/hcd-pci.c:for_each_companion",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/acpi.c:pci_acpi_init",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584597104,
      "name": "pci_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct pci_dev * pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev * from)
```

```json
{
  "name": "pci_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584704939,
      "name": "pci_get_device",
      "external": true,
      "loc": "drivers/pci/search.c:327",
      "file": "drivers/pci/search.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box",
        "arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/kernel/amd_nb.c:next_northbridge",
        "arch/x86/kernel/sysfb_efi.c:efifb_set_system",
        "arch/x86/kernel/pci-calgary_64.c:calgary_fixup_tce_spaces",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_seq_next",
        "drivers/pci/proc.c:pci_seq_start",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:has_untrusted_dev",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/core/hcd-pci.c:for_each_companion",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/acpi.c:pci_acpi_init",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584704800,
      "name": "pci_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
