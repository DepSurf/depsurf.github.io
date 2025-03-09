# Function: <code>pci_bus_read_config_dword</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int pci_bus_read_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 * value)
```

```json
{
  "name": "pci_bus_read_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583226800,
      "name": "pci_bus_read_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:58",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_read_counter",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_read_counter",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_irp_read_counter",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_irp_read_counter",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_irp_read_counter",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_irp_read_counter",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_disable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_cpu_init",
        "arch/x86/kernel/quirks.c:ich_force_enable_hpet",
        "arch/x86/kernel/quirks.c:old_ich_force_enable_hpet",
        "arch/x86/kernel/quirks.c:old_ich_force_enable_hpet",
        "arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub",
        "arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub",
        "arch/x86/kernel/quirks.c:vt8237_force_enable_hpet",
        "arch/x86/kernel/quirks.c:vt8237_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "arch/x86/kernel/quirks.c:force_hpet_resume",
        "arch/x86/kernel/quirks.c:force_hpet_resume",
        "arch/x86/kernel/quirks.c:force_hpet_resume",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/platform/atom/pmc_atom.c:pmc_atom_init",
        "arch/x86/platform/atom/pmc_atom.c:pmc_atom_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr",
        "drivers/pci/probe.c:pci_bus_read_dev_vendor_id",
        "drivers/pci/probe.c:pci_bus_read_dev_vendor_id",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_cfg_space_size",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/pci.c:pci_restore_config_dword",
        "drivers/pci/pci.c:pci_restore_config_dword",
        "drivers/pci/pci.c:pcix_get_max_mmrbc",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/rom.c:pci_enable_rom",
        "drivers/pci/rom.c:pci_disable_rom",
        "drivers/pci/setup-res.c:pci_update_resource",
        "drivers/pci/setup-res.c:pci_update_resource",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/vc.c:pci_vc_save_restore_dwords",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/quirks.c:quirk_tigerpoint_bm_sts",
        "drivers/pci/quirks.c:piix4_io_quirk",
        "drivers/pci/quirks.c:ich6_lpc_generic_decode",
        "drivers/pci/quirks.c:ich7_lpc_generic_decode",
        "drivers/pci/quirks.c:quirk_io",
        "drivers/pci/quirks.c:quirk_amd_ordering",
        "drivers/pci/quirks.c:quirk_amd_ordering",
        "drivers/pci/quirks.c:quirk_jmicron_ata",
        "drivers/pci/quirks.c:quirk_jmicron_ata",
        "drivers/pci/quirks.c:quirk_jmicron_ata",
        "drivers/pci/quirks.c:vtd_mask_spec_errors",
        "drivers/pci/quirks.c:quirk_piix4_acpi",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info",
        "drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info",
        "drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info",
        "drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info",
        "drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info",
        "drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info",
        "drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info",
        "drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info",
        "drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_uncorrect_error_status",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs",
        "drivers/pci/pcie/aer/aerdrv.c:aer_irq",
        "drivers/pci/pcie/aer/aerdrv.c:aer_irq",
        "drivers/pci/pcie/aer/aerdrv.c:aer_root_reset",
        "drivers/pci/pcie/aer/aerdrv.c:aer_root_reset",
        "drivers/pci/pcie/aer/aerdrv.c:aer_root_reset",
        "drivers/pci/pcie/aer/aerdrv.c:aer_error_resume",
        "drivers/pci/pcie/aer/aerdrv.c:aer_error_resume",
        "drivers/pci/pcie/aer/aerdrv.c:aer_remove",
        "drivers/pci/pcie/aer/aerdrv.c:aer_remove",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup",
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/pci/msi.c:__pci_read_msi_msg",
        "drivers/pci/msi.c:__pci_read_msi_msg",
        "drivers/pci/htirq.c:__ht_create_irq",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/virtio/virtio_pci_modern.c:map_capability",
        "drivers/virtio/virtio_pci_modern.c:map_capability",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/generic.c:agp3_generic_tlbflush",
        "drivers/char/agp/generic.c:agp3_generic_cleanup",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/generic.c:agp_generic_enable",
        "drivers/char/agp/generic.c:agp_generic_enable",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/amd64-agp.c:amd64_fetch_size",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/char/agp/intel-agp.c:intel_8xx_tlbflush",
        "drivers/char/agp/intel-agp.c:intel_8xx_tlbflush",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/via-agp.c:via_tlbflush",
        "drivers/char/agp/via-agp.c:via_tlbflush_agp3",
        "drivers/char/agp/via-agp.c:via_configure_agp3",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/iommu/amd_iommu_init.c:iommu_read_l2",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/ata/libata-core.c:pci_test_config_bits",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/pata_sis.c:sis_133_mode_filter",
        "drivers/ata/pata_sis.c:sis_133_set_dmamode",
        "drivers/ata/pata_sis.c:sis_133_set_piomode",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "arch/x86/pci/i386.c:pcibios_allocate_resources",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/fixup.c:pci_fixup_nforce2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583226800,
      "name": "pci_bus_read_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int pci_bus_read_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 * value)
```

```json
{
  "name": "pci_bus_read_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583534912,
      "name": "pci_bus_read_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:58",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_irp_read_counter",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_irp_read_counter",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_irp_read_counter",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_irp_read_counter",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_read_counter",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_read_counter",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_disable_box",
        "arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub",
        "arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub",
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "arch/x86/kernel/quirks.c:force_hpet_resume",
        "arch/x86/kernel/quirks.c:force_hpet_resume",
        "arch/x86/kernel/quirks.c:force_hpet_resume",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:vt8237_force_enable_hpet",
        "arch/x86/kernel/quirks.c:vt8237_force_enable_hpet",
        "arch/x86/kernel/quirks.c:old_ich_force_enable_hpet",
        "arch/x86/kernel/quirks.c:old_ich_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ich_force_enable_hpet",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/platform/atom/pmc_atom.c:pmc_atom_init",
        "arch/x86/platform/atom/pmc_atom.c:pmc_atom_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr",
        "drivers/pci/probe.c:pci_bus_read_dev_vendor_id",
        "drivers/pci/probe.c:pci_bus_read_dev_vendor_id",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pcix_get_max_mmrbc",
        "drivers/pci/pci.c:pci_flr_wait",
        "drivers/pci/pci.c:pci_flr_wait",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_restore_config_dword",
        "drivers/pci/pci.c:pci_restore_config_dword",
        "drivers/pci/rom.c:pci_enable_rom",
        "drivers/pci/setup-res.c:pci_update_resource",
        "drivers/pci/setup-res.c:pci_update_resource",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_save_restore_dwords",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs",
        "drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs",
        "drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs",
        "drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs",
        "drivers/pci/quirks.c:vtd_mask_spec_errors",
        "drivers/pci/quirks.c:quirk_jmicron_ata",
        "drivers/pci/quirks.c:quirk_jmicron_ata",
        "drivers/pci/quirks.c:quirk_jmicron_ata",
        "drivers/pci/quirks.c:quirk_amd_ordering",
        "drivers/pci/quirks.c:quirk_amd_ordering",
        "drivers/pci/quirks.c:ich7_lpc_generic_decode",
        "drivers/pci/quirks.c:ich6_lpc_generic_decode",
        "drivers/pci/quirks.c:quirk_piix4_acpi",
        "drivers/pci/quirks.c:piix4_io_quirk",
        "drivers/pci/quirks.c:quirk_io",
        "drivers/pci/quirks.c:quirk_tigerpoint_bm_sts",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info",
        "drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info",
        "drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info",
        "drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info",
        "drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info",
        "drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info",
        "drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info",
        "drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info",
        "drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_uncorrect_error_status",
        "drivers/pci/pcie/aer/aerdrv.c:aer_error_resume",
        "drivers/pci/pcie/aer/aerdrv.c:aer_error_resume",
        "drivers/pci/pcie/aer/aerdrv.c:aer_root_reset",
        "drivers/pci/pcie/aer/aerdrv.c:aer_root_reset",
        "drivers/pci/pcie/aer/aerdrv.c:aer_root_reset",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/pcie/aer/aerdrv.c:aer_remove",
        "drivers/pci/pcie/aer/aerdrv.c:aer_remove",
        "drivers/pci/pcie/aer/aerdrv.c:aer_irq",
        "drivers/pci/pcie/aer/aerdrv.c:aer_irq",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup",
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/pci/msi.c:__pci_read_msi_msg",
        "drivers/pci/msi.c:__pci_read_msi_msg",
        "drivers/pci/htirq.c:__ht_create_irq",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:map_capability",
        "drivers/virtio/virtio_pci_modern.c:map_capability",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/char/agp/generic.c:agp3_generic_cleanup",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/generic.c:agp3_generic_tlbflush",
        "drivers/char/agp/generic.c:agp_generic_enable",
        "drivers/char/agp/generic.c:agp_generic_enable",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure",
        "drivers/char/agp/amd64-agp.c:amd64_fetch_size",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_8xx_tlbflush",
        "drivers/char/agp/intel-agp.c:intel_8xx_tlbflush",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/char/agp/via-agp.c:via_tlbflush_agp3",
        "drivers/char/agp/via-agp.c:via_configure_agp3",
        "drivers/char/agp/via-agp.c:via_tlbflush",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:iommu_read_l2",
        "drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/ata/libata-core.c:pci_test_config_bits",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_133_mode_filter",
        "drivers/ata/pata_sis.c:sis_133_set_dmamode",
        "drivers/ata/pata_sis.c:sis_133_set_piomode",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "arch/x86/pci/i386.c:pcibios_allocate_resources",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/fixup.c:pci_fixup_nforce2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583534912,
      "name": "pci_bus_read_config_dword",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int pci_bus_read_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 * value)
```

```json
{
  "name": "pci_bus_read_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583671120,
      "name": "pci_bus_read_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:58",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_irp_read_counter",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_irp_read_counter",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_irp_read_counter",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_irp_read_counter",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_read_counter",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_read_counter",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_disable_box",
        "arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap",
        "arch/x86/kernel/quirks.c:quirk_intel_brickland_xeon_ras_cap",
        "arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub",
        "arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub",
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "arch/x86/kernel/quirks.c:force_hpet_resume",
        "arch/x86/kernel/quirks.c:force_hpet_resume",
        "arch/x86/kernel/quirks.c:force_hpet_resume",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:vt8237_force_enable_hpet",
        "arch/x86/kernel/quirks.c:vt8237_force_enable_hpet",
        "arch/x86/kernel/quirks.c:old_ich_force_enable_hpet",
        "arch/x86/kernel/quirks.c:old_ich_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ich_force_enable_hpet",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_df_indirect_read",
        "arch/x86/kernel/amd_nb.c:__amd_smn_rw",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/platform/atom/pmc_atom.c:pmc_atom_init",
        "arch/x86/platform/atom/pmc_atom.c:pmc_atom_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr",
        "drivers/pci/probe.c:pci_bus_read_dev_vendor_id",
        "drivers/pci/probe.c:pci_bus_read_dev_vendor_id",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pcix_get_max_mmrbc",
        "drivers/pci/pci.c:pci_flr_wait",
        "drivers/pci/pci.c:pci_flr_wait",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_restore_config_dword",
        "drivers/pci/pci.c:pci_restore_config_dword",
        "drivers/pci/rom.c:pci_enable_rom",
        "drivers/pci/setup-res.c:pci_update_resource",
        "drivers/pci/setup-res.c:pci_update_resource",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_save_restore_dwords",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs",
        "drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs",
        "drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs",
        "drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs",
        "drivers/pci/quirks.c:vtd_mask_spec_errors",
        "drivers/pci/quirks.c:quirk_jmicron_ata",
        "drivers/pci/quirks.c:quirk_jmicron_ata",
        "drivers/pci/quirks.c:quirk_jmicron_ata",
        "drivers/pci/quirks.c:quirk_amd_ordering",
        "drivers/pci/quirks.c:quirk_amd_ordering",
        "drivers/pci/quirks.c:ich7_lpc_generic_decode",
        "drivers/pci/quirks.c:ich6_lpc_generic_decode",
        "drivers/pci/quirks.c:quirk_piix4_acpi",
        "drivers/pci/quirks.c:piix4_io_quirk",
        "drivers/pci/quirks.c:quirk_io",
        "drivers/pci/quirks.c:quirk_tigerpoint_bm_sts",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info",
        "drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info",
        "drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info",
        "drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info",
        "drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info",
        "drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info",
        "drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info",
        "drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info",
        "drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_uncorrect_error_status",
        "drivers/pci/pcie/aer/aerdrv.c:aer_error_resume",
        "drivers/pci/pcie/aer/aerdrv.c:aer_error_resume",
        "drivers/pci/pcie/aer/aerdrv.c:aer_root_reset",
        "drivers/pci/pcie/aer/aerdrv.c:aer_root_reset",
        "drivers/pci/pcie/aer/aerdrv.c:aer_root_reset",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/pcie/aer/aerdrv.c:aer_remove",
        "drivers/pci/pcie/aer/aerdrv.c:aer_remove",
        "drivers/pci/pcie/aer/aerdrv.c:aer_irq",
        "drivers/pci/pcie/aer/aerdrv.c:aer_irq",
        "drivers/pci/pcie/ptm.c:pci_enable_ptm",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup",
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/pci/msi.c:__pci_read_msi_msg",
        "drivers/pci/msi.c:__pci_read_msi_msg",
        "drivers/pci/htirq.c:__ht_create_irq",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/pnp/quirks.c:quirk_intel_mch",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:map_capability",
        "drivers/virtio/virtio_pci_modern.c:map_capability",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/char/agp/generic.c:agp3_generic_cleanup",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/generic.c:agp3_generic_tlbflush",
        "drivers/char/agp/generic.c:agp_generic_enable",
        "drivers/char/agp/generic.c:agp_generic_enable",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure",
        "drivers/char/agp/amd64-agp.c:amd64_fetch_size",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_8xx_tlbflush",
        "drivers/char/agp/intel-agp.c:intel_8xx_tlbflush",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/char/agp/via-agp.c:via_tlbflush_agp3",
        "drivers/char/agp/via-agp.c:via_configure_agp3",
        "drivers/char/agp/via-agp.c:via_tlbflush",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_read_l2",
        "drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/ata/libata-core.c:pci_test_config_bits",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_133_mode_filter",
        "drivers/ata/pata_sis.c:sis_133_set_dmamode",
        "drivers/ata/pata_sis.c:sis_133_set_piomode",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "arch/x86/pci/i386.c:pcibios_allocate_resources",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/fixup.c:pci_fixup_nforce2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583671120,
      "name": "pci_bus_read_config_dword",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_bus_read_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 * value)
```

```json
{
  "name": "pci_bus_read_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583711008,
      "name": "pci_bus_read_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:66",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_bus_read_dev_vendor_id",
        "drivers/pci/probe.c:pci_bus_read_dev_vendor_id",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583711008,
      "name": "pci_bus_read_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int pci_bus_read_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 * value)
```

```json
{
  "name": "pci_bus_read_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583968400,
      "name": "pci_bus_read_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:66",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583968400,
      "name": "pci_bus_read_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int pci_bus_read_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 * value)
```

```json
{
  "name": "pci_bus_read_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584165729,
      "name": "pci_bus_read_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:65",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_read_config_dword"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584164592,
      "name": "pci_bus_read_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int pci_bus_read_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 * value)
```

```json
{
  "name": "pci_bus_read_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584252752,
      "name": "pci_bus_read_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:65",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584252752,
      "name": "pci_bus_read_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int pci_bus_read_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 * value)
```

```json
{
  "name": "pci_bus_read_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584445920,
      "name": "pci_bus_read_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:65",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584445920,
      "name": "pci_bus_read_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int pci_bus_read_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 * value)
```

```json
{
  "name": "pci_bus_read_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584582672,
      "name": "pci_bus_read_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:65",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584582672,
      "name": "pci_bus_read_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int pci_bus_read_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 * value)
```

```json
{
  "name": "pci_bus_read_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585258528,
      "name": "pci_bus_read_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:65",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_read_dword",
        "drivers/iommu/intel/iommu.c:quirk_ioat_snb_local_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585258528,
      "name": "pci_bus_read_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int pci_bus_read_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 * value)
```

```json
{
  "name": "pci_bus_read_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585416256,
      "name": "pci_bus_read_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:65",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_read_dword",
        "drivers/iommu/intel/iommu.c:device_to_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585416256,
      "name": "pci_bus_read_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int pci_bus_read_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 * value)
```

```json
{
  "name": "pci_bus_read_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585296800,
      "name": "pci_bus_read_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:65",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_read_dword",
        "drivers/iommu/intel/iommu.c:device_to_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585296800,
      "name": "pci_bus_read_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int pci_bus_read_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 * value)
```

```json
{
  "name": "pci_bus_read_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585753712,
      "name": "pci_bus_read_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:65",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_read_dword",
        "drivers/iommu/intel/iommu.c:device_to_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585753712,
      "name": "pci_bus_read_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int pci_bus_read_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 * value)
```

```json
{
  "name": "pci_bus_read_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586937312,
      "name": "pci_bus_read_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:68",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_read_dword",
        "drivers/iommu/intel/iommu.c:device_to_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586937312,
      "name": "pci_bus_read_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int pci_bus_read_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 * value)
```

```json
{
  "name": "pci_bus_read_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588094432,
      "name": "pci_bus_read_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:68",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_read_dword",
        "drivers/pci/quirks.c:pci_quirk_enable_intel_pch_acs",
        "drivers/iommu/intel/iommu.c:device_to_iommu",
        "drivers/platform/x86/p2sb.c:p2sb_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588094432,
      "name": "pci_bus_read_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int pci_bus_read_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 * value)
```

```json
{
  "name": "pci_bus_read_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588368864,
      "name": "pci_bus_read_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:68",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_read_dword",
        "drivers/pci/quirks.c:pci_quirk_enable_intel_pch_acs",
        "drivers/iommu/intel/iommu.c:device_to_iommu",
        "drivers/platform/x86/p2sb.c:p2sb_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588368864,
      "name": "pci_bus_read_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int pci_bus_read_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 * value)
```

```json
{
  "name": "pci_bus_read_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588663632,
      "name": "pci_bus_read_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:68",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_clear_and_set_config_dword",
        "drivers/pci/access.c:pcie_capability_read_dword",
        "drivers/pci/quirks.c:pci_quirk_enable_intel_pch_acs",
        "drivers/iommu/intel/iommu.c:device_lookup_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588663632,
      "name": "pci_bus_read_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int pci_bus_read_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 * value)
```

```json
{
  "name": "pci_bus_read_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496820744,
      "name": "pci_bus_read_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:65",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496820744,
      "name": "pci_bus_read_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int pci_bus_read_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 * value)
```

```json
{
  "name": "pci_bus_read_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230100928,
      "name": "pci_bus_read_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:65",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230100928,
      "name": "pci_bus_read_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int pci_bus_read_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 * value)
```

```json
{
  "name": "pci_bus_read_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290888784,
      "name": "pci_bus_read_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:65",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/pci-common.c:early_read_config_dword"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290888784,
      "name": "pci_bus_read_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int pci_bus_read_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 * value)
```

```json
{
  "name": "pci_bus_read_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275527338,
      "name": "pci_bus_read_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:65",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275527338,
      "name": "pci_bus_read_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int pci_bus_read_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 * value)
```

```json
{
  "name": "pci_bus_read_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584534832,
      "name": "pci_bus_read_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:65",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584534832,
      "name": "pci_bus_read_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int pci_bus_read_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 * value)
```

```json
{
  "name": "pci_bus_read_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584463008,
      "name": "pci_bus_read_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:65",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584463008,
      "name": "pci_bus_read_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int pci_bus_read_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 * value)
```

```json
{
  "name": "pci_bus_read_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584532832,
      "name": "pci_bus_read_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:65",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584532832,
      "name": "pci_bus_read_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int pci_bus_read_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 * value)
```

```json
{
  "name": "pci_bus_read_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584640608,
      "name": "pci_bus_read_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:65",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584640608,
      "name": "pci_bus_read_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
