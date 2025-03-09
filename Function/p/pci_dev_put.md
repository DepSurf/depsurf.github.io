# Function: <code>pci_dev_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_dev_put(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583272528,
      "name": "pci_dev_put",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1390",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_close",
        "drivers/pci/access.c:pci_vpd_f0_write",
        "drivers/pci/access.c:pci_vpd_f0_read",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/proc.c:pci_seq_stop",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_f0_vpd_link",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap",
        "drivers/pci/pcie/aer/aerdrv_core.c:aer_recover_work_func",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:release_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_iov_release",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:acpi_ioapic_remove",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/iommu/iommu.c:get_pci_function_alias_group",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/firmware/edd.c:edd_init",
        "arch/x86/pci/i386.c:pcibios_assign_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583272528,
      "name": "pci_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void pci_dev_put(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583590024,
      "name": "pci_dev_put",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1387",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_close",
        "drivers/pci/access.c:pci_vpd_f0_set_size",
        "drivers/pci/access.c:pci_vpd_f0_write",
        "drivers/pci/access.c:pci_vpd_f0_read",
        "drivers/pci/pci.c:pci_bridge_d3_update",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/proc.c:pci_seq_stop",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_f0_vpd_link",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/pcie/aer/aerdrv_core.c:aer_recover_work_func",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler",
        "drivers/pci/hotplug/cpci_hotplug_core.c:release_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_iov_release",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/ioapic.c:acpi_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/iommu/iommu.c:get_pci_function_alias_group",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/firmware/edd.c:edd_init",
        "arch/x86/pci/i386.c:pcibios_assign_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583583520,
      "name": "pci_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void pci_dev_put(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583727176,
      "name": "pci_dev_put",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1396",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_close",
        "drivers/pci/access.c:pci_vpd_f0_set_size",
        "drivers/pci/access.c:pci_vpd_f0_write",
        "drivers/pci/access.c:pci_vpd_f0_read",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/proc.c:pci_seq_stop",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_f0_vpd_link",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/pcie/aer/aerdrv_core.c:aer_recover_work_func",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler",
        "drivers/pci/hotplug/cpci_hotplug_core.c:release_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_iov_release",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/ioapic.c:acpi_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/iommu/iommu.c:get_pci_function_alias_group",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/firmware/edd.c:edd_init",
        "arch/x86/pci/i386.c:pcibios_assign_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583720608,
      "name": "pci_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void pci_dev_put(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583768050,
      "name": "pci_dev_put",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1414",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_close",
        "drivers/pci/access.c:pci_vpd_f0_set_size",
        "drivers/pci/access.c:pci_vpd_f0_write",
        "drivers/pci/access.c:pci_vpd_f0_read",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/proc.c:pci_seq_stop",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_f0_vpd_link",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/pcie/aer/aerdrv_core.c:aer_recover_work_func",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler",
        "drivers/pci/hotplug/cpci_hotplug_core.c:release_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_iov_release",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "arch/x86/pci/i386.c:pcibios_assign_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583761472,
      "name": "pci_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void pci_dev_put(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584027863,
      "name": "pci_dev_put",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1483",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_close",
        "drivers/pci/access.c:pci_vpd_f0_set_size",
        "drivers/pci/access.c:pci_vpd_f0_write",
        "drivers/pci/access.c:pci_vpd_f0_read",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/proc.c:pci_seq_stop",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_f0_vpd_link",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/pcie/aer/aerdrv_core.c:aer_recover_work_func",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler",
        "drivers/pci/hotplug/cpci_hotplug_core.c:release_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_iov_release",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "arch/x86/pci/i386.c:pcibios_assign_resources",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584020864,
      "name": "pci_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void pci_dev_put(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584224968,
      "name": "pci_dev_put",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1504",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_close",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_vpd_f0_set_size",
        "drivers/pci/vpd.c:pci_vpd_f0_write",
        "drivers/pci/vpd.c:pci_vpd_f0_read",
        "drivers/pci/proc.c:pci_seq_stop",
        "drivers/pci/quirks.c:quirk_gpu_hda",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/pcie/err.c:pcie_do_fatal_recovery",
        "drivers/pci/pcie/err.c:pcie_do_fatal_recovery",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:release_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/iov.c:pci_iov_release",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/firmware/edd.c:edd_init",
        "arch/x86/pci/i386.c:pcibios_assign_resources",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584217536,
      "name": "pci_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void pci_dev_put(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584314616,
      "name": "pci_dev_put",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1501",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_close",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_vpd_f0_set_size",
        "drivers/pci/vpd.c:pci_vpd_f0_write",
        "drivers/pci/vpd.c:pci_vpd_f0_read",
        "drivers/pci/proc.c:pci_seq_stop",
        "drivers/pci/quirks.c:quirk_gpu_hda",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/iov.c:pci_iov_release",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/firmware/edd.c:edd_init",
        "arch/x86/pci/i386.c:pcibios_assign_resources",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584307152,
      "name": "pci_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void pci_dev_put(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584509521,
      "name": "pci_dev_put",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1535",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_close",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_vpd_f0_set_size",
        "drivers/pci/vpd.c:pci_vpd_f0_write",
        "drivers/pci/vpd.c:pci_vpd_f0_read",
        "drivers/pci/proc.c:pci_seq_stop",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/iov.c:pci_iov_release",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/firmware/edd.c:edd_init",
        "arch/x86/pci/i386.c:pcibios_assign_resources",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584502144,
      "name": "pci_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void pci_dev_put(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584645553,
      "name": "pci_dev_put",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1548",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_close",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_vpd_f0_set_size",
        "drivers/pci/vpd.c:pci_vpd_f0_write",
        "drivers/pci/vpd.c:pci_vpd_f0_read",
        "drivers/pci/proc.c:pci_seq_stop",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/iov.c:pci_iov_release",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_release",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/firmware/edd.c:edd_init",
        "arch/x86/pci/i386.c:pcibios_assign_resources",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584638144,
      "name": "pci_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void pci_dev_put(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585328881,
      "name": "pci_dev_put",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1513",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:setup_ibs_ctl",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:icx_count_chabox",
        "arch/x86/events/intel/uncore_snbep.c:skx_count_chabox",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_close",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_vpd_f0_set_size",
        "drivers/pci/vpd.c:pci_vpd_f0_write",
        "drivers/pci/vpd.c:pci_vpd_f0_read",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/proc.c:pci_seq_stop",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/iov.c:pci_iov_release",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:uli_agp_init",
        "drivers/iommu/iommu.c:get_pci_alias_group",
        "drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arbiter_del_pci_device",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_release",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/hwmon/hwmon.c:hwmon_pci_quirks",
        "arch/x86/pci/i386.c:pcibios_assign_resources",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585320976,
      "name": "pci_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void pci_dev_put(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585482161,
      "name": "pci_dev_put",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1492",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:setup_ibs_ctl",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:icx_count_chabox",
        "arch/x86/events/intel/uncore_snbep.c:skx_count_chabox",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_close",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_vpd_f0_set_size",
        "drivers/pci/vpd.c:pci_vpd_f0_write",
        "drivers/pci/vpd.c:pci_vpd_f0_read",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/proc.c:pci_seq_stop",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/iov.c:pci_iov_release",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:uli_agp_init",
        "drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault",
        "drivers/iommu/amd/iommu.c:amd_iommu_report_rmp_fault",
        "drivers/iommu/amd/iommu.c:amd_iommu_report_rmp_hw_error",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/iommu.c:get_pci_alias_group",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arbiter_del_pci_device",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_release",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/hwmon/hwmon.c:hwmon_pci_quirks",
        "arch/x86/pci/i386.c:pcibios_assign_resources",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585474304,
      "name": "pci_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void pci_dev_put(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585361761,
      "name": "pci_dev_put",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1492",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:icx_count_chabox",
        "arch/x86/events/intel/uncore_snbep.c:skx_count_chabox",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables",
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_close",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_get_class",
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_vpd_f0_write",
        "drivers/pci/vpd.c:pci_vpd_f0_read",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/proc.c:pci_seq_stop",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/iov.c:pci_iov_release",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/iommu.c:get_pci_alias_group",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/gpu/vga/vgaarb.c:pci_notify",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_release",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/firmware/edd.c:edd_device_register",
        "arch/x86/pci/i386.c:pcibios_assign_resources",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585354176,
      "name": "pci_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void pci_dev_put(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585821089,
      "name": "pci_dev_put",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1506",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:icx_count_chabox",
        "arch/x86/events/intel/uncore_snbep.c:skx_count_chabox",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables",
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_close",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_get_class",
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:vpd_write",
        "drivers/pci/vpd.c:vpd_read",
        "drivers/pci/vpd.c:pci_vpd_size",
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/proc.c:pci_seq_stop",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/iov.c:pci_iov_release",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/viot.c:viot_get_iommu",
        "drivers/acpi/viot.c:viot_get_iommu",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/iommu.c:get_pci_alias_group",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/gpu/vga/vgaarb.c:pci_notify",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_decode",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_release",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/firmware/edd.c:edd_device_register",
        "arch/x86/pci/i386.c:pcibios_assign_resources",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585813296,
      "name": "pci_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void pci_dev_put(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587011619,
      "name": "pci_dev_put",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1535",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:icx_count_chabox",
        "arch/x86/events/intel/uncore_snbep.c:skx_count_chabox",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables",
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_close",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_get_class",
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_write_vpd_any",
        "drivers/pci/vpd.c:vpd_write",
        "drivers/pci/vpd.c:vpd_read",
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_from_pci_bridge",
        "drivers/pci/pcie/edr.c:edr_handle_event",
        "drivers/pci/proc.c:pci_seq_stop",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/iov.c:pci_iov_release",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/pci/vgaarb.c:pci_notify",
        "drivers/pci/vgaarb.c:vga_arb_write",
        "drivers/pci/vgaarb.c:vga_arb_write",
        "drivers/pci/vgaarb.c:vga_arb_write",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/viot.c:viot_get_iommu",
        "drivers/acpi/viot.c:viot_get_iommu",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/clk/x86/clk-fch.c:fch_clk_remove",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/iommu.c:get_pci_alias_group",
        "drivers/iommu/iommu.c:get_pci_function_alias_group",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_decode",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_release",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/firmware/edd.c:edd_device_register",
        "arch/x86/pci/i386.c:pcibios_assign_resources",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587002752,
      "name": "pci_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void pci_dev_put(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588181587,
      "name": "pci_dev_put",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1541",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:discover_upi_topology",
        "arch/x86/events/intel/uncore_snbep.c:discover_upi_topology",
        "arch/x86/events/intel/uncore_snbep.c:icx_count_chabox",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map",
        "arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology",
        "arch/x86/events/intel/uncore_snbep.c:skx_upi_topology_cb",
        "arch/x86/events/intel/uncore_snbep.c:skx_count_chabox",
        "arch/x86/events/intel/uncore_snbep.c:hswep_has_limit_sbox",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables",
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_close",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_get_class",
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_write_vpd_any",
        "drivers/pci/vpd.c:vpd_write",
        "drivers/pci/vpd.c:vpd_read",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_from_pci_bridge",
        "drivers/pci/pcie/edr.c:edr_handle_event",
        "drivers/pci/proc.c:pci_seq_stop",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/iov.c:pci_iov_release",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/pci/p2pdma.c:pci_p2pdma_enable_store",
        "drivers/pci/p2pdma.c:pci_p2pmem_find_many",
        "drivers/pci/p2pdma.c:pci_p2pmem_find_many",
        "drivers/pci/p2pdma.c:pci_p2pdma_distance_many",
        "drivers/pci/vgaarb.c:pci_notify",
        "drivers/pci/vgaarb.c:vga_arb_write",
        "drivers/pci/vgaarb.c:vga_arb_write",
        "drivers/pci/vgaarb.c:vga_arb_write",
        "drivers/pci/vgaarb.c:vga_arbiter_add_pci_device",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/viot.c:viot_get_iommu",
        "drivers/acpi/viot.c:viot_get_iommu",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/clk/x86/clk-fch.c:fch_clk_remove",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/iommu/amd/iommu.c:iommu_print_event",
        "drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault",
        "drivers/iommu/intel/dmar.c:dmar_dev_scope_init",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/svm.c:prq_event_thread",
        "drivers/iommu/iommu.c:get_pci_alias_group",
        "drivers/iommu/iommu.c:get_pci_function_alias_group",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/firmware/edd.c:edd_init",
        "arch/x86/pci/i386.c:pcibios_assign_resources",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588171968,
      "name": "pci_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void pci_dev_put(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588457587,
      "name": "pci_dev_put",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1542",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:discover_upi_topology",
        "arch/x86/events/intel/uncore_snbep.c:discover_upi_topology",
        "arch/x86/events/intel/uncore_snbep.c:icx_count_chabox",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map",
        "arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology",
        "arch/x86/events/intel/uncore_snbep.c:skx_upi_topology_cb",
        "arch/x86/events/intel/uncore_snbep.c:skx_count_chabox",
        "arch/x86/events/intel/uncore_snbep.c:hswep_has_limit_sbox",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables",
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_close",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_get_class",
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_write_vpd_any",
        "drivers/pci/vpd.c:vpd_write",
        "drivers/pci/vpd.c:vpd_read",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_from_pci_bridge",
        "drivers/pci/pcie/edr.c:edr_handle_event",
        "drivers/pci/proc.c:pci_seq_stop",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/iov.c:pci_iov_release",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/pci/p2pdma.c:pci_p2pdma_enable_store",
        "drivers/pci/p2pdma.c:pci_p2pmem_find_many",
        "drivers/pci/p2pdma.c:pci_p2pmem_find_many",
        "drivers/pci/p2pdma.c:pci_p2pdma_distance_many",
        "drivers/pci/vgaarb.c:pci_notify",
        "drivers/pci/vgaarb.c:vga_arb_write",
        "drivers/pci/vgaarb.c:vga_arb_write",
        "drivers/pci/vgaarb.c:vga_arb_write",
        "drivers/pci/vgaarb.c:vga_arbiter_add_pci_device",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/viot.c:viot_get_iommu",
        "drivers/acpi/viot.c:viot_get_iommu",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/clk/x86/clk-fch.c:fch_clk_remove",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/iommu/amd/iommu.c:iommu_print_event",
        "drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault",
        "drivers/iommu/intel/dmar.c:dmar_dev_scope_init",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/svm.c:prq_event_thread",
        "drivers/iommu/iommu.c:get_pci_alias_group",
        "drivers/iommu/iommu.c:get_pci_function_alias_group",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/firmware/edd.c:edd_init",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_clean_structure",
        "drivers/platform/x86/intel/pmc/core_ssram.c:pmc_core_ssram_init",
        "drivers/platform/x86/intel/pmc/mtl.c:mtl_set_device_d3",
        "arch/x86/pci/i386.c:pcibios_assign_resources",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588448000,
      "name": "pci_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void pci_dev_put(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588754691,
      "name": "pci_dev_put",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1555",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:discover_upi_topology",
        "arch/x86/events/intel/uncore_snbep.c:discover_upi_topology",
        "arch/x86/events/intel/uncore_snbep.c:icx_count_chabox",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map",
        "arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology",
        "arch/x86/events/intel/uncore_snbep.c:skx_upi_topology_cb",
        "arch/x86/events/intel/uncore_snbep.c:skx_count_chabox",
        "arch/x86/events/intel/uncore_snbep.c:hswep_has_limit_sbox",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables",
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_close",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_get_base_class",
        "drivers/pci/search.c:pci_get_class",
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_write_vpd_any",
        "drivers/pci/vpd.c:vpd_write",
        "drivers/pci/vpd.c:vpd_read",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_from_pci_bridge",
        "drivers/pci/pcie/edr.c:edr_handle_event",
        "drivers/pci/proc.c:pci_seq_stop",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/iov.c:pci_iov_release",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/pci/p2pdma.c:pci_p2pdma_enable_store",
        "drivers/pci/p2pdma.c:pci_p2pmem_find_many",
        "drivers/pci/p2pdma.c:pci_p2pmem_find_many",
        "drivers/pci/p2pdma.c:pci_p2pdma_distance_many",
        "drivers/pci/vgaarb.c:pci_notify",
        "drivers/pci/vgaarb.c:vga_arb_write",
        "drivers/pci/vgaarb.c:vga_arb_write",
        "drivers/pci/vgaarb.c:vga_arb_write",
        "drivers/pci/vgaarb.c:vga_arbiter_add_pci_device",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/viot.c:viot_get_iommu",
        "drivers/acpi/viot.c:viot_get_iommu",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/clk/x86/clk-fch.c:fch_clk_remove",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/iommu/amd/iommu.c:iommu_print_event",
        "drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault",
        "drivers/iommu/intel/dmar.c:dmar_dev_scope_init",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/svm.c:prq_event_thread",
        "drivers/iommu/iommu.c:get_pci_alias_group",
        "drivers/iommu/iommu.c:get_pci_function_alias_group",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/firmware/edd.c:edd_init",
        "arch/x86/pci/i386.c:pcibios_assign_resources",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588744944,
      "name": "pci_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void pci_dev_put(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496891292,
      "name": "pci_dev_put",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1548",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_vpd_f0_set_size",
        "drivers/pci/vpd.c:pci_vpd_f0_write",
        "drivers/pci/vpd.c:pci_vpd_f0_read",
        "drivers/pci/proc.c:pci_seq_stop",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/iov.c:pci_iov_release",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/pci/syscall.c:__arm64_sys_pciconfig_write",
        "drivers/pci/syscall.c:__arm64_sys_pciconfig_read",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496884488,
      "name": "pci_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void pci_dev_put(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230169300,
      "name": "pci_dev_put",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1548",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_vpd_f0_set_size",
        "drivers/pci/vpd.c:pci_vpd_f0_write",
        "drivers/pci/vpd.c:pci_vpd_f0_read",
        "drivers/pci/proc.c:pci_seq_stop",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/iov.c:pci_iov_release",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/pci/syscall.c:__se_sys_pciconfig_write",
        "drivers/pci/syscall.c:__se_sys_pciconfig_read",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230161372,
      "name": "pci_dev_put",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void pci_dev_put(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290978800,
      "name": "pci_dev_put",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1548",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/powerpc/kernel/eeh.c:eeh_dev_break_write",
        "arch/powerpc/kernel/eeh.c:eeh_dev_break_write",
        "arch/powerpc/kernel/eeh.c:eeh_dev_check_write",
        "arch/powerpc/kernel/eeh.c:eeh_dev_check_write",
        "arch/powerpc/kernel/pci_dn.c:pci_remove_device_node_info",
        "arch/powerpc/kernel/pci-common.c:pci_phys_mem_access_prot",
        "arch/powerpc/kernel/pci_of_scan.c:__of_scan_bus",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_vpd_f0_set_size",
        "drivers/pci/vpd.c:pci_vpd_f0_write",
        "drivers/pci/vpd.c:pci_vpd_f0_read",
        "drivers/pci/proc.c:pci_seq_stop",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/iov.c:pci_iov_release",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/pci/syscall.c:__se_sys_pciconfig_write",
        "drivers/pci/syscall.c:__se_sys_pciconfig_read",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290969568,
      "name": "pci_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void pci_dev_put(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275584584,
      "name": "pci_dev_put",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1548",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_vpd_f0_set_size",
        "drivers/pci/vpd.c:pci_vpd_f0_write",
        "drivers/pci/vpd.c:pci_vpd_f0_read",
        "drivers/pci/proc.c:pci_seq_stop",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/iov.c:pci_iov_release",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275581454,
      "name": "pci_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void pci_dev_put(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584596033,
      "name": "pci_dev_put",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1548",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_close",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_vpd_f0_set_size",
        "drivers/pci/vpd.c:pci_vpd_f0_write",
        "drivers/pci/vpd.c:pci_vpd_f0_read",
        "drivers/pci/proc.c:pci_seq_stop",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/iov.c:pci_iov_release",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/firmware/edd.c:edd_init",
        "arch/x86/pci/i386.c:pcibios_assign_resources",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584590304,
      "name": "pci_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void pci_dev_put(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584525841,
      "name": "pci_dev_put",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1548",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_close",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_vpd_f0_set_size",
        "drivers/pci/vpd.c:pci_vpd_f0_write",
        "drivers/pci/vpd.c:pci_vpd_f0_read",
        "drivers/pci/proc.c:pci_seq_stop",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/iov.c:pci_iov_release",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_release",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/firmware/edd.c:edd_init",
        "arch/x86/pci/i386.c:pcibios_assign_resources",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584518432,
      "name": "pci_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void pci_dev_put(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584595713,
      "name": "pci_dev_put",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1548",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_close",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_vpd_f0_set_size",
        "drivers/pci/vpd.c:pci_vpd_f0_write",
        "drivers/pci/vpd.c:pci_vpd_f0_read",
        "drivers/pci/proc.c:pci_seq_stop",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/iov.c:pci_iov_release",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_release",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/firmware/edd.c:edd_init",
        "arch/x86/pci/i386.c:pcibios_assign_resources",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584588304,
      "name": "pci_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void pci_dev_put(struct pci_dev * dev)
```

```json
{
  "name": "pci_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584703409,
      "name": "pci_dev_put",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1548",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_close",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/pci/pci-sysfs.c:pci_sysfs_init",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_vpd_f0_set_size",
        "drivers/pci/vpd.c:pci_vpd_f0_write",
        "drivers/pci/vpd.c:pci_vpd_f0_read",
        "drivers/pci/proc.c:pci_seq_stop",
        "drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/iov.c:pci_iov_release",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_set_default_device",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_release",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/firmware/edd.c:edd_init",
        "arch/x86/pci/i386.c:pcibios_assign_resources",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584696352,
      "name": "pci_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
