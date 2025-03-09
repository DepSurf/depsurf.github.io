# Function: <code>ioremap_nocache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * ioremap_nocache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579286752,
      "name": "ioremap_nocache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:229",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box",
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom",
        "arch/x86/kernel/quirks.c:ich_force_enable_hpet",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/atom/pmc_atom.c:pmc_atom_init",
        "arch/x86/platform/efi/efi_64.c:efi_ioremap",
        "kernel/memremap.c:ioremap_cache",
        "lib/pci_iomap.c:pci_iomap_range",
        "lib/devres.c:devm_ioremap",
        "lib/devres.c:devm_ioremap_nocache",
        "drivers/pci/pci.c:pci_ioremap_bar",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/quirks.c:quirk_e100_interrupt",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/char/hpet.c:hpet_resources",
        "drivers/char/hpet.c:hpet_resources",
        "drivers/char/agp/intel-gtt.c:i830_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map",
        "arch/x86/pci/common.c:pcibios_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579286752,
      "name": "ioremap_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void * ioremap_nocache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579286416,
      "name": "ioremap_nocache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:228",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box",
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom",
        "arch/x86/kernel/quirks.c:ich_force_enable_hpet",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/atom/pmc_atom.c:pmc_atom_init",
        "arch/x86/platform/efi/efi_64.c:efi_ioremap",
        "kernel/memremap.c:ioremap_cache",
        "lib/pci_iomap.c:pci_iomap_range",
        "lib/devres.c:devm_ioremap_nocache",
        "drivers/pci/pci.c:pci_ioremap_bar",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/quirks.c:quirk_e100_interrupt",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init",
        "drivers/char/hpet.c:hpet_resources",
        "drivers/char/hpet.c:hpet_resources",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i830_setup",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map",
        "arch/x86/pci/common.c:pcibios_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579286416,
      "name": "ioremap_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void * ioremap_nocache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579301808,
      "name": "ioremap_nocache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:228",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box",
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom",
        "arch/x86/kernel/quirks.c:ich_force_enable_hpet",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/atom/pmc_atom.c:pmc_atom_init",
        "arch/x86/platform/efi/efi_64.c:efi_ioremap",
        "kernel/memremap.c:ioremap_cache",
        "lib/pci_iomap.c:pci_iomap_range",
        "lib/devres.c:devm_ioremap_nocache",
        "drivers/pci/pci.c:pci_ioremap_bar",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/quirks.c:quirk_e100_interrupt",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init",
        "drivers/char/hpet.c:hpet_resources",
        "drivers/char/hpet.c:hpet_resources",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i830_setup",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map",
        "arch/x86/pci/common.c:pcibios_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579301808,
      "name": "ioremap_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void * ioremap_nocache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579299552,
      "name": "ioremap_nocache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:229",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box",
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom",
        "arch/x86/kernel/quirks.c:ich_force_enable_hpet",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/efi/efi_64.c:efi_ioremap",
        "kernel/memremap.c:ioremap_cache",
        "lib/pci_iomap.c:pci_iomap_range",
        "lib/devres.c:devm_ioremap",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:pci_ioremap_bar",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/quirks.c:quirk_e100_interrupt",
        "drivers/pci/msi.c:__pci_enable_msix",
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i830_setup",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map",
        "arch/x86/pci/common.c:pcibios_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579299552,
      "name": "ioremap_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void * ioremap_nocache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579320272,
      "name": "ioremap_nocache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:281",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box",
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom",
        "arch/x86/kernel/quirks.c:ich_force_enable_hpet",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/efi/efi_64.c:efi_ioremap",
        "lib/pci_iomap.c:pci_iomap_range",
        "lib/devres.c:devm_ioremap",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:pci_ioremap_bar",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/quirks.c:quirk_e100_interrupt",
        "drivers/pci/msi.c:__pci_enable_msix",
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i830_setup",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579320272,
      "name": "ioremap_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void * ioremap_nocache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579331040,
      "name": "ioremap_nocache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:281",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box",
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom",
        "arch/x86/kernel/quirks.c:ich_force_enable_hpet",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/efi/efi_64.c:efi_ioremap",
        "arch/x86/platform/efi/early_printk.c:early_efi_map_fb",
        "lib/pci_iomap.c:pci_iomap_range",
        "lib/devres.c:__devm_ioremap",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:pci_ioremap_bar",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/quirks.c:quirk_e100_interrupt",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/msi.c:__pci_enable_msix",
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i830_setup",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579331040,
      "name": "ioremap_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void * ioremap_nocache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579357264,
      "name": "ioremap_nocache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:282",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box",
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom",
        "arch/x86/kernel/quirks.c:ich_force_enable_hpet",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/eisa.c:eisa_bus_probe",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/efi/efi_64.c:efi_ioremap",
        "arch/x86/platform/efi/early_printk.c:early_efi_map_fb",
        "lib/pci_iomap.c:pci_iomap_range",
        "lib/devres.c:__devm_ioremap",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:pci_ioremap_bar",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/quirks.c:quirk_e100_interrupt",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i830_setup",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579357264,
      "name": "ioremap_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void * ioremap_nocache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579371424,
      "name": "ioremap_nocache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:302",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box",
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom",
        "arch/x86/kernel/quirks.c:ich_force_enable_hpet",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/eisa.c:eisa_bus_probe",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/efi/efi_64.c:efi_ioremap",
        "lib/pci_iomap.c:pci_iomap_range",
        "lib/devres.c:__devm_ioremap",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:pci_ioremap_bar",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/quirks.c:quirk_e100_interrupt",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i830_setup",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371424,
      "name": "ioremap_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void * ioremap_nocache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579376032,
      "name": "ioremap_nocache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:324",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box",
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom",
        "arch/x86/kernel/quirks.c:ich_force_enable_hpet",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/eisa.c:eisa_bus_probe",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/efi/efi_64.c:efi_ioremap",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_init",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_init",
        "lib/pci_iomap.c:pci_iomap_range",
        "lib/devres.c:__devm_ioremap",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:pci_ioremap_bar",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/quirks.c:quirk_e100_interrupt",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i830_setup",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579376032,
      "name": "ioremap_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void * ioremap_nocache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579371936,
      "name": "ioremap_nocache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:324",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box",
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom",
        "arch/x86/kernel/quirks.c:ich_force_enable_hpet",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/eisa.c:eisa_bus_probe",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/efi/efi_64.c:efi_ioremap",
        "lib/pci_iomap.c:pci_iomap_range",
        "lib/devres.c:__devm_ioremap",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:pci_ioremap_bar",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/quirks.c:quirk_e100_interrupt",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i830_setup",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvme/host/pci.c:nvme_remap_bar",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371936,
      "name": "ioremap_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void * ioremap_nocache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579302128,
      "name": "ioremap_nocache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:324",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box",
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom",
        "arch/x86/kernel/quirks.c:ich_force_enable_hpet",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/eisa.c:eisa_bus_probe",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/efi/efi_64.c:efi_ioremap",
        "lib/pci_iomap.c:pci_iomap_range",
        "lib/devres.c:__devm_ioremap",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:pci_ioremap_bar",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/quirks.c:quirk_e100_interrupt",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i830_setup",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvme/host/pci.c:nvme_remap_bar",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579302128,
      "name": "ioremap_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void * ioremap_nocache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579371856,
      "name": "ioremap_nocache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:324",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box",
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom",
        "arch/x86/kernel/quirks.c:ich_force_enable_hpet",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/eisa.c:eisa_bus_probe",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/efi/efi_64.c:efi_ioremap",
        "lib/pci_iomap.c:pci_iomap_range",
        "lib/devres.c:__devm_ioremap",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:pci_ioremap_bar",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/quirks.c:quirk_e100_interrupt",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i830_setup",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371856,
      "name": "ioremap_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void * ioremap_nocache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579380336,
      "name": "ioremap_nocache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:324",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box",
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom",
        "arch/x86/kernel/quirks.c:ich_force_enable_hpet",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/eisa.c:eisa_bus_probe",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/efi/efi_64.c:efi_ioremap",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_init",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_init",
        "lib/pci_iomap.c:pci_iomap_range",
        "lib/devres.c:__devm_ioremap",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:pci_ioremap_bar",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/quirks.c:quirk_e100_interrupt",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i830_setup",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579380336,
      "name": "ioremap_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void * ioremap_nocache(resource_size_t phys_addr, long unsigned int size)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void * ioremap_nocache(resource_size_t phys_addr, long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void * ioremap_nocache(resource_size_t phys_addr, long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void * ioremap_nocache(resource_size_t phys_addr, long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void * ioremap_nocache(resource_size_t phys_addr, long unsigned int size)
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
