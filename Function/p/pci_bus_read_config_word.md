# Function: <code>pci_bus_read_config_word</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int pci_bus_read_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 * value)
```

```json
{
  "name": "pci_bus_read_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583226624,
      "name": "pci_bus_read_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:57",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl",
        "drivers/pci/pci.c:pci_clear_mwi",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/pci.c:__pci_set_master",
        "drivers/pci/pci.c:pci_intx",
        "drivers/pci/pci.c:pcix_get_mmrbc",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_std_enable_acs",
        "drivers/pci/pci.c:pci_std_enable_acs",
        "drivers/pci/pci.c:pci_wait_for_pending",
        "drivers/pci/pci.c:pci_wait_for_pending",
        "drivers/pci/pci.c:pci_update_current_state",
        "drivers/pci/pci.c:do_pci_disable_device",
        "drivers/pci/pci.c:pci_check_pme_status",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci.c:pci_enable_device_flags",
        "drivers/pci/pci.c:pci_reset_secondary_bus",
        "drivers/pci/pci.c:pci_set_vga_state",
        "drivers/pci/pci.c:pci_set_vga_state",
        "drivers/pci/pci.c:pci_reassigndev_resource_alignment",
        "drivers/pci/setup-res.c:pci_update_resource",
        "drivers/pci/setup-res.c:pci_enable_resources",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:__dev_sort_resources",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/quirks.c:quirk_io_region",
        "drivers/pci/quirks.c:quirk_vt82c598_id",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_xio2000a",
        "drivers/pci/quirks.c:quirk_e100_interrupt",
        "drivers/pci/quirks.c:quirk_e100_interrupt",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/msi.c:pci_msi_vec_count",
        "drivers/pci/msi.c:pci_msix_vec_count",
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/pci/msi.c:pci_enable_msi_range",
        "drivers/pci/msi.c:pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_read_msi_msg",
        "drivers/pci/msi.c:__pci_read_msi_msg",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/ats.c:pci_ats_queue_depth",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_pasid_features",
        "drivers/pci/ats.c:pci_max_pasids",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_disable_sriov",
        "drivers/pci/iov.c:pci_disable_sriov",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup",
        "drivers/char/agp/generic.c:agp3_generic_fetch_size",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:intel_fetch_size",
        "drivers/char/agp/intel-agp.c:intel_cleanup",
        "drivers/char/agp/intel-agp.c:intel_8xx_cleanup",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-gtt.c:intel_enable_gtt",
        "drivers/char/agp/intel-gtt.c:intel_enable_gtt",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/via-agp.c:via_fetch_size_agp3",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:quirk_calpella_no_shadow_gtt",
        "drivers/ata/libata-core.c:pci_test_config_bits",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/pata_sis.c:sis_133_cable_detect",
        "drivers/ata/pata_sis.c:sis_old_set_dmamode",
        "drivers/ata/pata_sis.c:sis_66_set_dmamode",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "arch/x86/pci/i386.c:pcibios_allocate_resources",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583226624,
      "name": "pci_bus_read_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int pci_bus_read_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 * value)
```

```json
{
  "name": "pci_bus_read_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583534736,
      "name": "pci_bus_read_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:57",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/pci.c:pci_reassigndev_resource_alignment",
        "drivers/pci/pci.c:pci_set_vga_state",
        "drivers/pci/pci.c:pci_set_vga_state",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pcix_get_mmrbc",
        "drivers/pci/pci.c:pci_reset_secondary_bus",
        "drivers/pci/pci.c:pci_intx",
        "drivers/pci/pci.c:pci_clear_mwi",
        "drivers/pci/pci.c:__pci_set_master",
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_std_enable_acs",
        "drivers/pci/pci.c:pci_std_enable_acs",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci.c:pci_check_pme_status",
        "drivers/pci/pci.c:do_pci_disable_device",
        "drivers/pci/pci.c:pci_enable_device_flags",
        "drivers/pci/pci.c:pci_update_current_state",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/pci.c:pci_wait_for_pending",
        "drivers/pci/pci.c:pci_wait_for_pending",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl",
        "drivers/pci/setup-res.c:pci_enable_resources",
        "drivers/pci/setup-res.c:pci_update_resource",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:__dev_sort_resources",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_e100_interrupt",
        "drivers/pci/quirks.c:quirk_e100_interrupt",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_vt82c598_id",
        "drivers/pci/quirks.c:quirk_xio2000a",
        "drivers/pci/quirks.c:quirk_io_region",
        "drivers/pci/pcie/pcie-dpc.c:dpc_remove",
        "drivers/pci/pcie/pcie-dpc.c:dpc_probe",
        "drivers/pci/pcie/pcie-dpc.c:dpc_probe",
        "drivers/pci/pcie/pcie-dpc.c:dpc_irq",
        "drivers/pci/pcie/pcie-dpc.c:dpc_irq",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_msix_vec_count",
        "drivers/pci/msi.c:pci_msi_vec_count",
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi.c:__pci_read_msi_msg",
        "drivers/pci/msi.c:__pci_read_msi_msg",
        "drivers/pci/ats.c:pci_max_pasids",
        "drivers/pci/ats.c:pci_pasid_features",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_ats_queue_depth",
        "drivers/pci/iov.c:pci_disable_sriov",
        "drivers/pci/iov.c:pci_disable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup",
        "drivers/char/agp/generic.c:agp3_generic_fetch_size",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-agp.c:intel_8xx_cleanup",
        "drivers/char/agp/intel-agp.c:intel_cleanup",
        "drivers/char/agp/intel-agp.c:intel_fetch_size",
        "drivers/char/agp/intel-gtt.c:intel_enable_gtt",
        "drivers/char/agp/intel-gtt.c:intel_enable_gtt",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/via-agp.c:via_fetch_size_agp3",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:quirk_calpella_no_shadow_gtt",
        "drivers/ata/libata-core.c:pci_test_config_bits",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_66_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_dmamode",
        "drivers/ata/pata_sis.c:sis_133_cable_detect",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "arch/x86/pci/i386.c:pcibios_allocate_resources",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583534736,
      "name": "pci_bus_read_config_word",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int pci_bus_read_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 * value)
```

```json
{
  "name": "pci_bus_read_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583670944,
      "name": "pci_bus_read_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:57",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/pci.c:pci_reassigndev_resource_alignment",
        "drivers/pci/pci.c:pci_set_vga_state",
        "drivers/pci/pci.c:pci_set_vga_state",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pcix_get_mmrbc",
        "drivers/pci/pci.c:pci_reset_secondary_bus",
        "drivers/pci/pci.c:pci_intx",
        "drivers/pci/pci.c:pci_clear_mwi",
        "drivers/pci/pci.c:__pci_set_master",
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_std_enable_acs",
        "drivers/pci/pci.c:pci_std_enable_acs",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci.c:pci_check_pme_status",
        "drivers/pci/pci.c:do_pci_disable_device",
        "drivers/pci/pci.c:pci_enable_device_flags",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/pci.c:pci_wait_for_pending",
        "drivers/pci/pci.c:pci_wait_for_pending",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl",
        "drivers/pci/setup-res.c:pci_enable_resources",
        "drivers/pci/setup-res.c:pci_update_resource",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:__dev_sort_resources",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_e100_interrupt",
        "drivers/pci/quirks.c:quirk_e100_interrupt",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_vt82c598_id",
        "drivers/pci/quirks.c:quirk_xio2000a",
        "drivers/pci/quirks.c:quirk_io_region",
        "drivers/pci/pcie/pcie-dpc.c:dpc_remove",
        "drivers/pci/pcie/pcie-dpc.c:dpc_probe",
        "drivers/pci/pcie/pcie-dpc.c:dpc_probe",
        "drivers/pci/pcie/pcie-dpc.c:dpc_irq",
        "drivers/pci/pcie/pcie-dpc.c:dpc_irq",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_msix_vec_count",
        "drivers/pci/msi.c:pci_msi_vec_count",
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi.c:__pci_read_msi_msg",
        "drivers/pci/msi.c:__pci_read_msi_msg",
        "drivers/pci/ats.c:pci_max_pasids",
        "drivers/pci/ats.c:pci_pasid_features",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_ats_queue_depth",
        "drivers/pci/iov.c:pci_disable_sriov",
        "drivers/pci/iov.c:pci_disable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup",
        "drivers/char/agp/generic.c:agp3_generic_fetch_size",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-agp.c:intel_8xx_cleanup",
        "drivers/char/agp/intel-agp.c:intel_cleanup",
        "drivers/char/agp/intel-agp.c:intel_fetch_size",
        "drivers/char/agp/intel-gtt.c:intel_enable_gtt",
        "drivers/char/agp/intel-gtt.c:intel_enable_gtt",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/via-agp.c:via_fetch_size_agp3",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:quirk_calpella_no_shadow_gtt",
        "drivers/ata/libata-core.c:pci_test_config_bits",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_66_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_dmamode",
        "drivers/ata/pata_sis.c:sis_133_cable_detect",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "arch/x86/pci/i386.c:pcibios_allocate_resources",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583670944,
      "name": "pci_bus_read_config_word",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_bus_read_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 * value)
```

```json
{
  "name": "pci_bus_read_config_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583710896,
      "name": "pci_bus_read_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:65",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pci_find_next_cap_ttl",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583710896,
      "name": "pci_bus_read_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int pci_bus_read_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 * value)
```

```json
{
  "name": "pci_bus_read_config_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583968288,
      "name": "pci_bus_read_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:65",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pci_find_next_cap_ttl",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583968288,
      "name": "pci_bus_read_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int pci_bus_read_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 * value)
```

```json
{
  "name": "pci_bus_read_config_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584165569,
      "name": "pci_bus_read_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:64",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_read_config_word"
      ],
      "caller_func": [
        "drivers/pci/pci.c:__pci_find_next_cap_ttl",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584164480,
      "name": "pci_bus_read_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int pci_bus_read_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 * value)
```

```json
{
  "name": "pci_bus_read_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584252640,
      "name": "pci_bus_read_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:64",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pci_find_next_cap_ttl",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584252640,
      "name": "pci_bus_read_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int pci_bus_read_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 * value)
```

```json
{
  "name": "pci_bus_read_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584445808,
      "name": "pci_bus_read_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:64",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pci_find_next_cap_ttl",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584445808,
      "name": "pci_bus_read_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int pci_bus_read_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 * value)
```

```json
{
  "name": "pci_bus_read_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584582560,
      "name": "pci_bus_read_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:64",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pci_find_next_cap_ttl",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584582560,
      "name": "pci_bus_read_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int pci_bus_read_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 * value)
```

```json
{
  "name": "pci_bus_read_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585258416,
      "name": "pci_bus_read_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:64",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_read_word",
        "drivers/pci/pci.c:pci_find_ht_capability",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:pci_find_capability",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585258416,
      "name": "pci_bus_read_config_word",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int pci_bus_read_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 * value)
```

```json
{
  "name": "pci_bus_read_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585416144,
      "name": "pci_bus_read_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:64",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_read_word",
        "drivers/pci/pci.c:pci_find_ht_capability",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:pci_find_capability",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585416144,
      "name": "pci_bus_read_config_word",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int pci_bus_read_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 * value)
```

```json
{
  "name": "pci_bus_read_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585296688,
      "name": "pci_bus_read_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:64",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_read_word",
        "drivers/pci/pci.c:pci_find_ht_capability",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:pci_find_capability",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585296688,
      "name": "pci_bus_read_config_word",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int pci_bus_read_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 * value)
```

```json
{
  "name": "pci_bus_read_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585753600,
      "name": "pci_bus_read_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:64",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_read_word",
        "drivers/pci/pci.c:pci_find_ht_capability",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:pci_find_capability",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585753600,
      "name": "pci_bus_read_config_word",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int pci_bus_read_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 * value)
```

```json
{
  "name": "pci_bus_read_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586937168,
      "name": "pci_bus_read_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:67",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:quirk_intel_irqbalance",
        "drivers/pci/access.c:pcie_capability_read_word",
        "drivers/pci/pci.c:pci_find_ht_capability",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:pci_find_capability",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586937168,
      "name": "pci_bus_read_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int pci_bus_read_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 * value)
```

```json
{
  "name": "pci_bus_read_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588094272,
      "name": "pci_bus_read_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:67",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:quirk_intel_irqbalance",
        "drivers/pci/access.c:pcie_capability_read_word",
        "drivers/pci/pci.c:pci_find_ht_capability",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:pci_find_capability",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588094272,
      "name": "pci_bus_read_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int pci_bus_read_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 * value)
```

```json
{
  "name": "pci_bus_read_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588368704,
      "name": "pci_bus_read_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:67",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:quirk_intel_irqbalance",
        "drivers/pci/access.c:pcie_capability_read_word",
        "drivers/pci/pci.c:pci_find_ht_capability",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:pci_find_capability",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588368704,
      "name": "pci_bus_read_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int pci_bus_read_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 * value)
```

```json
{
  "name": "pci_bus_read_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588663472,
      "name": "pci_bus_read_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:67",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:quirk_intel_irqbalance",
        "drivers/pci/access.c:pcie_capability_read_word",
        "drivers/pci/pci.c:pci_find_ht_capability",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:pci_find_capability",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588663472,
      "name": "pci_bus_read_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int pci_bus_read_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 * value)
```

```json
{
  "name": "pci_bus_read_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496823896,
      "name": "pci_bus_read_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:64",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pci_find_next_cap_ttl",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496823896,
      "name": "pci_bus_read_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
int pci_bus_read_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 * value)
```

```json
{
  "name": "pci_bus_read_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230100724,
      "name": "pci_bus_read_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:64",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pci_find_next_cap_ttl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230100724,
      "name": "pci_bus_read_config_word",
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
int pci_bus_read_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 * value)
```

```json
{
  "name": "pci_bus_read_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290888480,
      "name": "pci_bus_read_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:64",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/pci-common.c:early_read_config_word",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290888480,
      "name": "pci_bus_read_config_word",
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
int pci_bus_read_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 * value)
```

```json
{
  "name": "pci_bus_read_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275527200,
      "name": "pci_bus_read_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:64",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pci_find_next_cap_ttl",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275527200,
      "name": "pci_bus_read_config_word",
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
int pci_bus_read_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 * value)
```

```json
{
  "name": "pci_bus_read_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584534720,
      "name": "pci_bus_read_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:64",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pci_find_next_cap_ttl",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584534720,
      "name": "pci_bus_read_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int pci_bus_read_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 * value)
```

```json
{
  "name": "pci_bus_read_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584462896,
      "name": "pci_bus_read_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:64",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pci_find_next_cap_ttl",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584462896,
      "name": "pci_bus_read_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int pci_bus_read_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 * value)
```

```json
{
  "name": "pci_bus_read_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584532720,
      "name": "pci_bus_read_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:64",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pci_find_next_cap_ttl",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584532720,
      "name": "pci_bus_read_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int pci_bus_read_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 * value)
```

```json
{
  "name": "pci_bus_read_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584640496,
      "name": "pci_bus_read_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:64",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pci_find_next_cap_ttl",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584640496,
      "name": "pci_bus_read_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
