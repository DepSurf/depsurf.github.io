# Function: <code>pci_bus_write_config_dword</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_bus_write_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 value)
```

```json
{
  "name": "pci_bus_write_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583228400,
      "name": "pci_bus_write_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:61",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pcie_capability_write_dword"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_disable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_pci_init_box",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_irp_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_irp_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:knl_uncore_imc_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:knl_uncore_imc_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:knl_uncore_imc_enable_box",
        "arch/x86/kernel/quirks.c:old_ich_force_enable_hpet",
        "arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub",
        "arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub",
        "arch/x86/kernel/quirks.c:vt8237_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:force_hpet_resume",
        "arch/x86/kernel/quirks.c:force_hpet_resume",
        "arch/x86/kernel/quirks.c:force_hpet_resume",
        "arch/x86/kernel/quirks.c:force_hpet_resume",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr",
        "drivers/pci/access.c:pcie_capability_write_dword",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/pci.c:pci_restore_config_dword",
        "drivers/pci/rom.c:pci_enable_rom",
        "drivers/pci/rom.c:pci_disable_rom",
        "drivers/pci/setup-res.c:pci_update_resource",
        "drivers/pci/setup-res.c:pci_update_resource",
        "drivers/pci/setup-res.c:pci_disable_bridge_window",
        "drivers/pci/setup-res.c:pci_disable_bridge_window",
        "drivers/pci/setup-res.c:pci_disable_bridge_window",
        "drivers/pci/setup-res.c:pci_disable_bridge_window",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
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
        "drivers/pci/quirks.c:quirk_cardbus_legacy",
        "drivers/pci/quirks.c:quirk_amd_ordering",
        "drivers/pci/quirks.c:quirk_amd_ordering",
        "drivers/pci/quirks.c:quirk_jmicron_ata",
        "drivers/pci/quirks.c:quirk_jmicron_ata",
        "drivers/pci/quirks.c:vtd_mask_spec_errors",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_uncorrect_error_status",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs",
        "drivers/pci/pcie/aer/aerdrv_core.c:aer_isr",
        "drivers/pci/pcie/aer/aerdrv_core.c:aer_isr",
        "drivers/pci/pcie/aer/aerdrv.c:aer_irq",
        "drivers/pci/pcie/aer/aerdrv.c:aer_root_reset",
        "drivers/pci/pcie/aer/aerdrv.c:aer_root_reset",
        "drivers/pci/pcie/aer/aerdrv.c:aer_root_reset",
        "drivers/pci/pcie/aer/aerdrv.c:aer_error_resume",
        "drivers/pci/pcie/aer/aerdrv.c:aer_remove",
        "drivers/pci/pcie/aer/aerdrv.c:aer_remove",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup",
        "drivers/pci/msi.c:__pci_msi_desc_mask_irq",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/htirq.c:write_ht_irq_msg",
        "drivers/pci/htirq.c:write_ht_irq_msg",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/generic.c:agp3_generic_tlbflush",
        "drivers/char/agp/generic.c:agp3_generic_tlbflush",
        "drivers/char/agp/generic.c:agp3_generic_cleanup",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/generic.c:agp_generic_enable",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
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
        "drivers/char/agp/intel-agp.c:intel_tlbflush",
        "drivers/char/agp/intel-agp.c:intel_tlbflush",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_8xx_tlbflush",
        "drivers/char/agp/intel-agp.c:intel_8xx_tlbflush",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/via-agp.c:via_tlbflush",
        "drivers/char/agp/via-agp.c:via_tlbflush",
        "drivers/char/agp/via-agp.c:via_tlbflush_agp3",
        "drivers/char/agp/via-agp.c:via_tlbflush_agp3",
        "drivers/char/agp/via-agp.c:via_configure_agp3",
        "drivers/char/agp/via-agp.c:via_configure_agp3",
        "drivers/char/agp/via-agp.c:via_configure",
        "drivers/char/agp/via-agp.c:via_configure",
        "drivers/iommu/amd_iommu_init.c:iommu_write_l2",
        "drivers/iommu/amd_iommu_init.c:iommu_write_l2",
        "drivers/iommu/amd_iommu_init.c:iommu_read_l2",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/ata/ata_piix.c:piix_remove_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/pata_sis.c:sis_133_set_dmamode",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports",
        "drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports",
        "arch/x86/pci/i386.c:pcibios_allocate_resources",
        "arch/x86/pci/fixup.c:pci_fixup_nforce2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583228400,
      "name": "pci_bus_write_config_dword.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071583228512,
      "name": "pci_bus_write_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_bus_write_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 value)
```

```json
{
  "name": "pci_bus_write_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583537562,
      "name": "pci_bus_write_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:61",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pcie_capability_write_dword"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snbep.c:knl_uncore_imc_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:knl_uncore_imc_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:knl_uncore_imc_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_irp_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_irp_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_pci_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_disable_box",
        "arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub",
        "arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub",
        "arch/x86/kernel/quirks.c:force_hpet_resume",
        "arch/x86/kernel/quirks.c:force_hpet_resume",
        "arch/x86/kernel/quirks.c:force_hpet_resume",
        "arch/x86/kernel/quirks.c:force_hpet_resume",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:vt8237_force_enable_hpet",
        "arch/x86/kernel/quirks.c:old_ich_force_enable_hpet",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr",
        "drivers/pci/access.c:pcie_capability_write_dword",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/pci.c:pci_restore_config_dword",
        "drivers/pci/rom.c:pci_enable_rom",
        "drivers/pci/setup-res.c:pci_disable_bridge_window",
        "drivers/pci/setup-res.c:pci_disable_bridge_window",
        "drivers/pci/setup-res.c:pci_disable_bridge_window",
        "drivers/pci/setup-res.c:pci_disable_bridge_window",
        "drivers/pci/setup-res.c:pci_update_resource",
        "drivers/pci/setup-res.c:pci_update_resource",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_save_restore_dwords",
        "drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs",
        "drivers/pci/quirks.c:vtd_mask_spec_errors",
        "drivers/pci/quirks.c:quirk_jmicron_ata",
        "drivers/pci/quirks.c:quirk_jmicron_ata",
        "drivers/pci/quirks.c:quirk_amd_ordering",
        "drivers/pci/quirks.c:quirk_amd_ordering",
        "drivers/pci/quirks.c:quirk_cardbus_legacy",
        "drivers/pci/pcie/aer/aerdrv_core.c:aer_isr",
        "drivers/pci/pcie/aer/aerdrv_core.c:aer_isr",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_uncorrect_error_status",
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
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi.c:__pci_msi_desc_mask_irq",
        "drivers/pci/htirq.c:write_ht_irq_msg",
        "drivers/pci/htirq.c:write_ht_irq_msg",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/char/agp/generic.c:agp3_generic_cleanup",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/generic.c:agp3_generic_tlbflush",
        "drivers/char/agp/generic.c:agp3_generic_tlbflush",
        "drivers/char/agp/generic.c:agp_generic_enable",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-agp.c:intel_8xx_tlbflush",
        "drivers/char/agp/intel-agp.c:intel_8xx_tlbflush",
        "drivers/char/agp/intel-agp.c:intel_tlbflush",
        "drivers/char/agp/intel-agp.c:intel_tlbflush",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/via-agp.c:via_tlbflush_agp3",
        "drivers/char/agp/via-agp.c:via_tlbflush_agp3",
        "drivers/char/agp/via-agp.c:via_configure_agp3",
        "drivers/char/agp/via-agp.c:via_configure_agp3",
        "drivers/char/agp/via-agp.c:via_tlbflush",
        "drivers/char/agp/via-agp.c:via_tlbflush",
        "drivers/char/agp/via-agp.c:via_configure",
        "drivers/char/agp/via-agp.c:via_configure",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:iommu_write_l2",
        "drivers/iommu/amd_iommu_init.c:iommu_write_l2",
        "drivers/iommu/amd_iommu_init.c:iommu_read_l2",
        "drivers/ata/ata_piix.c:piix_remove_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_133_set_dmamode",
        "drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports",
        "drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "arch/x86/pci/i386.c:pcibios_allocate_resources",
        "arch/x86/pci/fixup.c:pci_fixup_nforce2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583537088,
      "name": "pci_bus_write_config_dword.part.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071583537200,
      "name": "pci_bus_write_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_bus_write_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 value)
```

```json
{
  "name": "pci_bus_write_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583673898,
      "name": "pci_bus_write_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:61",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pcie_capability_write_dword"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box",
        "arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box",
        "arch/x86/events/intel/uncore_snbep.c:knl_uncore_imc_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:knl_uncore_imc_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:knl_uncore_imc_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_irp_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_irp_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_pci_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_disable_box",
        "arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub",
        "arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub",
        "arch/x86/kernel/quirks.c:force_hpet_resume",
        "arch/x86/kernel/quirks.c:force_hpet_resume",
        "arch/x86/kernel/quirks.c:force_hpet_resume",
        "arch/x86/kernel/quirks.c:force_hpet_resume",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:vt8237_force_enable_hpet",
        "arch/x86/kernel/quirks.c:old_ich_force_enable_hpet",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_df_indirect_read",
        "arch/x86/kernel/amd_nb.c:__amd_smn_rw",
        "arch/x86/kernel/amd_nb.c:__amd_smn_rw",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr",
        "drivers/pci/access.c:pcie_capability_write_dword",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/pci.c:pci_restore_config_dword",
        "drivers/pci/rom.c:pci_enable_rom",
        "drivers/pci/setup-res.c:pci_disable_bridge_window",
        "drivers/pci/setup-res.c:pci_disable_bridge_window",
        "drivers/pci/setup-res.c:pci_disable_bridge_window",
        "drivers/pci/setup-res.c:pci_disable_bridge_window",
        "drivers/pci/setup-res.c:pci_update_resource",
        "drivers/pci/setup-res.c:pci_update_resource",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_save_restore_dwords",
        "drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs",
        "drivers/pci/quirks.c:vtd_mask_spec_errors",
        "drivers/pci/quirks.c:quirk_jmicron_ata",
        "drivers/pci/quirks.c:quirk_jmicron_ata",
        "drivers/pci/quirks.c:quirk_amd_ordering",
        "drivers/pci/quirks.c:quirk_amd_ordering",
        "drivers/pci/quirks.c:quirk_cardbus_legacy",
        "drivers/pci/pcie/aer/aerdrv_core.c:aer_isr",
        "drivers/pci/pcie/aer/aerdrv_core.c:aer_isr",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_uncorrect_error_status",
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
        "drivers/pci/pcie/ptm.c:pci_enable_ptm",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi.c:__pci_msi_desc_mask_irq",
        "drivers/pci/htirq.c:write_ht_irq_msg",
        "drivers/pci/htirq.c:write_ht_irq_msg",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/char/agp/generic.c:agp3_generic_cleanup",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/generic.c:agp3_generic_tlbflush",
        "drivers/char/agp/generic.c:agp3_generic_tlbflush",
        "drivers/char/agp/generic.c:agp_generic_enable",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-agp.c:intel_8xx_tlbflush",
        "drivers/char/agp/intel-agp.c:intel_8xx_tlbflush",
        "drivers/char/agp/intel-agp.c:intel_tlbflush",
        "drivers/char/agp/intel-agp.c:intel_tlbflush",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/via-agp.c:via_tlbflush_agp3",
        "drivers/char/agp/via-agp.c:via_tlbflush_agp3",
        "drivers/char/agp/via-agp.c:via_configure_agp3",
        "drivers/char/agp/via-agp.c:via_configure_agp3",
        "drivers/char/agp/via-agp.c:via_tlbflush",
        "drivers/char/agp/via-agp.c:via_tlbflush",
        "drivers/char/agp/via-agp.c:via_configure",
        "drivers/char/agp/via-agp.c:via_configure",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_write_l2",
        "drivers/iommu/amd_iommu_init.c:iommu_write_l2",
        "drivers/iommu/amd_iommu_init.c:iommu_read_l2",
        "drivers/ata/ata_piix.c:piix_remove_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_133_set_dmamode",
        "drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports",
        "drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "arch/x86/pci/i386.c:pcibios_allocate_resources",
        "arch/x86/pci/fixup.c:pci_fixup_nforce2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583673424,
      "name": "pci_bus_write_config_dword.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071583673536,
      "name": "pci_bus_write_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
int pci_bus_write_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 value)
```

```json
{
  "name": "pci_bus_write_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583711200,
      "name": "pci_bus_write_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:69",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583711200,
      "name": "pci_bus_write_config_dword",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_bus_write_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 value)
```

```json
{
  "name": "pci_bus_write_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583968608,
      "name": "pci_bus_write_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:69",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583968608,
      "name": "pci_bus_write_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int pci_bus_write_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 value)
```

```json
{
  "name": "pci_bus_write_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584166846,
      "name": "pci_bus_write_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:68",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pcie_capability_write_dword"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584164800,
      "name": "pci_bus_write_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int pci_bus_write_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 value)
```

```json
{
  "name": "pci_bus_write_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584252960,
      "name": "pci_bus_write_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:68",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_write_dword"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584252960,
      "name": "pci_bus_write_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int pci_bus_write_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 value)
```

```json
{
  "name": "pci_bus_write_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584446128,
      "name": "pci_bus_write_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:68",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584446128,
      "name": "pci_bus_write_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int pci_bus_write_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 value)
```

```json
{
  "name": "pci_bus_write_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584582880,
      "name": "pci_bus_write_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:68",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584582880,
      "name": "pci_bus_write_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int pci_bus_write_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 value)
```

```json
{
  "name": "pci_bus_write_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585258736,
      "name": "pci_bus_write_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:68",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_write_dword"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585258736,
      "name": "pci_bus_write_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int pci_bus_write_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 value)
```

```json
{
  "name": "pci_bus_write_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585416464,
      "name": "pci_bus_write_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:68",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_write_dword"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585416464,
      "name": "pci_bus_write_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int pci_bus_write_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 value)
```

```json
{
  "name": "pci_bus_write_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585297008,
      "name": "pci_bus_write_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:68",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_write_dword"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585297008,
      "name": "pci_bus_write_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int pci_bus_write_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 value)
```

```json
{
  "name": "pci_bus_write_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585753920,
      "name": "pci_bus_write_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:68",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_write_dword"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585753920,
      "name": "pci_bus_write_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int pci_bus_write_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 value)
```

```json
{
  "name": "pci_bus_write_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586937600,
      "name": "pci_bus_write_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:71",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586937600,
      "name": "pci_bus_write_config_dword",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int pci_bus_write_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 value)
```

```json
{
  "name": "pci_bus_write_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588094768,
      "name": "pci_bus_write_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:71",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/platform/x86/p2sb.c:p2sb_bar",
        "drivers/platform/x86/p2sb.c:p2sb_bar",
        "drivers/platform/x86/p2sb.c:p2sb_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588094768,
      "name": "pci_bus_write_config_dword",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int pci_bus_write_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 value)
```

```json
{
  "name": "pci_bus_write_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588369200,
      "name": "pci_bus_write_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:71",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/platform/x86/p2sb.c:p2sb_bar",
        "drivers/platform/x86/p2sb.c:p2sb_bar",
        "drivers/platform/x86/p2sb.c:p2sb_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588369200,
      "name": "pci_bus_write_config_dword",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int pci_bus_write_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 value)
```

```json
{
  "name": "pci_bus_write_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588663968,
      "name": "pci_bus_write_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:71",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_clear_and_set_config_dword"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588663968,
      "name": "pci_bus_write_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int pci_bus_write_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 value)
```

```json
{
  "name": "pci_bus_write_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496822728,
      "name": "pci_bus_write_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:68",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_write_dword"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496822728,
      "name": "pci_bus_write_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int pci_bus_write_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 value)
```

```json
{
  "name": "pci_bus_write_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230101392,
      "name": "pci_bus_write_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:68",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_write_dword"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230101392,
      "name": "pci_bus_write_config_dword",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int pci_bus_write_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 value)
```

```json
{
  "name": "pci_bus_write_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290889472,
      "name": "pci_bus_write_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:68",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/pci-common.c:early_write_config_dword"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290889472,
      "name": "pci_bus_write_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int pci_bus_write_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 value)
```

```json
{
  "name": "pci_bus_write_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275527710,
      "name": "pci_bus_write_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:68",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_write_dword"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275527710,
      "name": "pci_bus_write_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int pci_bus_write_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 value)
```

```json
{
  "name": "pci_bus_write_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584535040,
      "name": "pci_bus_write_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:68",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584535040,
      "name": "pci_bus_write_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int pci_bus_write_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 value)
```

```json
{
  "name": "pci_bus_write_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584463216,
      "name": "pci_bus_write_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:68",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584463216,
      "name": "pci_bus_write_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int pci_bus_write_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 value)
```

```json
{
  "name": "pci_bus_write_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584533040,
      "name": "pci_bus_write_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:68",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584533040,
      "name": "pci_bus_write_config_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int pci_bus_write_config_dword(struct pci_bus * bus, unsigned int devfn, int pos, u32 value)
```

```json
{
  "name": "pci_bus_write_config_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584640816,
      "name": "pci_bus_write_config_dword",
      "external": true,
      "loc": "drivers/pci/access.c:68",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584640816,
      "name": "pci_bus_write_config_dword",
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
