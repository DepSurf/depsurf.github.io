# Function: <code>pci_bus_write_config_word</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_bus_write_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 value)
```

```json
{
  "name": "pci_bus_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583228256,
      "name": "pci_bus_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:60",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pcie_capability_write_word"
      ],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_write_word",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/pci.c:pci_clear_mwi",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/pci.c:__pci_set_master",
        "drivers/pci/pci.c:pci_intx",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pci_std_enable_acs",
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:do_pci_disable_device",
        "drivers/pci/pci.c:pci_check_pme_status",
        "drivers/pci/pci.c:pci_reset_secondary_bus",
        "drivers/pci/pci.c:pci_reset_secondary_bus",
        "drivers/pci/pci.c:pci_set_vga_state",
        "drivers/pci/pci.c:pci_set_vga_state",
        "drivers/pci/pci.c:pci_reassigndev_resource_alignment",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/setup-res.c:pci_update_resource",
        "drivers/pci/setup-res.c:pci_update_resource",
        "drivers/pci/setup-res.c:pci_enable_resources",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:__pci_setup_bridge",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/quirks.c:quirk_xio2000a",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/msi.c:pci_enable_msi_range",
        "drivers/pci/msi.c:pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/ats.c:pci_enable_ats",
        "drivers/pci/ats.c:pci_disable_pasid",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_enable_pri",
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
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/intel-agp.c:intel_cleanup",
        "drivers/char/agp/intel-agp.c:intel_cleanup",
        "drivers/char/agp/intel-agp.c:intel_8xx_cleanup",
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
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-gtt.c:intel_enable_gtt",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/pata_sis.c:sis_old_set_dmamode",
        "drivers/ata/pata_sis.c:sis_66_set_dmamode",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/pci-quirks.c:uhci_reset_hc",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/hwmon/hwmon.c:hwmon_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583228256,
      "name": "pci_bus_write_config_word.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071583228368,
      "name": "pci_bus_write_config_word",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_bus_write_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 value)
```

```json
{
  "name": "pci_bus_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583537434,
      "name": "pci_bus_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:60",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pcie_capability_write_word"
      ],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_write_word",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/pci.c:pci_reassigndev_resource_alignment",
        "drivers/pci/pci.c:pci_set_vga_state",
        "drivers/pci/pci.c:pci_set_vga_state",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_reset_secondary_bus",
        "drivers/pci/pci.c:pci_reset_secondary_bus",
        "drivers/pci/pci.c:pci_intx",
        "drivers/pci/pci.c:pci_clear_mwi",
        "drivers/pci/pci.c:__pci_set_master",
        "drivers/pci/pci.c:pci_std_enable_acs",
        "drivers/pci/pci.c:pci_check_pme_status",
        "drivers/pci/pci.c:do_pci_disable_device",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/setup-res.c:pci_enable_resources",
        "drivers/pci/setup-res.c:pci_update_resource",
        "drivers/pci/setup-res.c:pci_update_resource",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_setup_bridge",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/quirks.c:quirk_xio2000a",
        "drivers/pci/pcie/pcie-dpc.c:dpc_remove",
        "drivers/pci/pcie/pcie-dpc.c:dpc_probe",
        "drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/ats.c:pci_disable_pasid",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_enable_ats",
        "drivers/pci/iov.c:pci_disable_sriov",
        "drivers/pci/iov.c:pci_disable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-agp.c:intel_8xx_cleanup",
        "drivers/char/agp/intel-agp.c:intel_cleanup",
        "drivers/char/agp/intel-agp.c:intel_cleanup",
        "drivers/char/agp/intel-gtt.c:intel_enable_gtt",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_66_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_dmamode",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/usb/host/pci-quirks.c:uhci_reset_hc",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/hwmon/hwmon.c:hwmon_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583536944,
      "name": "pci_bus_write_config_word.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071583537056,
      "name": "pci_bus_write_config_word",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_bus_write_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 value)
```

```json
{
  "name": "pci_bus_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583673770,
      "name": "pci_bus_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:60",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pcie_capability_write_word"
      ],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_write_word",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/pci.c:pci_reassigndev_resource_alignment",
        "drivers/pci/pci.c:pci_set_vga_state",
        "drivers/pci/pci.c:pci_set_vga_state",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_reset_secondary_bus",
        "drivers/pci/pci.c:pci_reset_secondary_bus",
        "drivers/pci/pci.c:pci_intx",
        "drivers/pci/pci.c:pci_clear_mwi",
        "drivers/pci/pci.c:__pci_set_master",
        "drivers/pci/pci.c:pci_std_enable_acs",
        "drivers/pci/pci.c:pci_check_pme_status",
        "drivers/pci/pci.c:do_pci_disable_device",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/setup-res.c:pci_enable_resources",
        "drivers/pci/setup-res.c:pci_update_resource",
        "drivers/pci/setup-res.c:pci_update_resource",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_setup_bridge",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/quirks.c:quirk_xio2000a",
        "drivers/pci/pcie/pcie-dpc.c:dpc_remove",
        "drivers/pci/pcie/pcie-dpc.c:dpc_probe",
        "drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/ats.c:pci_disable_pasid",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_enable_ats",
        "drivers/pci/iov.c:pci_disable_sriov",
        "drivers/pci/iov.c:pci_disable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-agp.c:intel_8xx_cleanup",
        "drivers/char/agp/intel-agp.c:intel_cleanup",
        "drivers/char/agp/intel-agp.c:intel_cleanup",
        "drivers/char/agp/intel-gtt.c:intel_enable_gtt",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_66_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_dmamode",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/usb/host/pci-quirks.c:uhci_reset_hc",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/hwmon/hwmon.c:hwmon_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583673280,
      "name": "pci_bus_write_config_word.part.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071583673392,
      "name": "pci_bus_write_config_word",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_bus_write_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 value)
```

```json
{
  "name": "pci_bus_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583711152,
      "name": "pci_bus_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:68",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583711152,
      "name": "pci_bus_write_config_word",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_bus_write_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 value)
```

```json
{
  "name": "pci_bus_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583968560,
      "name": "pci_bus_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:68",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583968560,
      "name": "pci_bus_write_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int pci_bus_write_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 value)
```

```json
{
  "name": "pci_bus_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584166686,
      "name": "pci_bus_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:67",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pcie_capability_write_word"
      ],
      "caller_func": [
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584164752,
      "name": "pci_bus_write_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int pci_bus_write_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 value)
```

```json
{
  "name": "pci_bus_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584252912,
      "name": "pci_bus_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:67",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_write_word",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584252912,
      "name": "pci_bus_write_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int pci_bus_write_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 value)
```

```json
{
  "name": "pci_bus_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584446080,
      "name": "pci_bus_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:67",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584446080,
      "name": "pci_bus_write_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int pci_bus_write_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 value)
```

```json
{
  "name": "pci_bus_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584582832,
      "name": "pci_bus_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:67",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584582832,
      "name": "pci_bus_write_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int pci_bus_write_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 value)
```

```json
{
  "name": "pci_bus_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585258688,
      "name": "pci_bus_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:67",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_write_word",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585258688,
      "name": "pci_bus_write_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int pci_bus_write_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 value)
```

```json
{
  "name": "pci_bus_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585416416,
      "name": "pci_bus_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:67",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_write_word",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585416416,
      "name": "pci_bus_write_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int pci_bus_write_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 value)
```

```json
{
  "name": "pci_bus_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585296960,
      "name": "pci_bus_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:67",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_write_word",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585296960,
      "name": "pci_bus_write_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int pci_bus_write_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 value)
```

```json
{
  "name": "pci_bus_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585753872,
      "name": "pci_bus_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:67",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_write_word",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585753872,
      "name": "pci_bus_write_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int pci_bus_write_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 value)
```

```json
{
  "name": "pci_bus_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586937520,
      "name": "pci_bus_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:70",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586937520,
      "name": "pci_bus_write_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int pci_bus_write_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 value)
```

```json
{
  "name": "pci_bus_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588094672,
      "name": "pci_bus_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:70",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588094672,
      "name": "pci_bus_write_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int pci_bus_write_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 value)
```

```json
{
  "name": "pci_bus_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588369104,
      "name": "pci_bus_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:70",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588369104,
      "name": "pci_bus_write_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int pci_bus_write_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 value)
```

```json
{
  "name": "pci_bus_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588663872,
      "name": "pci_bus_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:70",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588663872,
      "name": "pci_bus_write_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int pci_bus_write_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 value)
```

```json
{
  "name": "pci_bus_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496823408,
      "name": "pci_bus_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:67",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_write_word",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496823408,
      "name": "pci_bus_write_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int pci_bus_write_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 value)
```

```json
{
  "name": "pci_bus_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230101260,
      "name": "pci_bus_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:67",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_write_word",
        "drivers/pci/quirks.c:pci_idt_bus_quirk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230101260,
      "name": "pci_bus_write_config_word",
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
int pci_bus_write_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 value)
```

```json
{
  "name": "pci_bus_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290889264,
      "name": "pci_bus_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:67",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/pci-common.c:early_write_config_word",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290889264,
      "name": "pci_bus_write_config_word",
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
int pci_bus_write_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 value)
```

```json
{
  "name": "pci_bus_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275527586,
      "name": "pci_bus_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:67",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_write_word",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275527586,
      "name": "pci_bus_write_config_word",
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
int pci_bus_write_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 value)
```

```json
{
  "name": "pci_bus_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584534992,
      "name": "pci_bus_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:67",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584534992,
      "name": "pci_bus_write_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int pci_bus_write_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 value)
```

```json
{
  "name": "pci_bus_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584463168,
      "name": "pci_bus_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:67",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584463168,
      "name": "pci_bus_write_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int pci_bus_write_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 value)
```

```json
{
  "name": "pci_bus_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584532992,
      "name": "pci_bus_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:67",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584532992,
      "name": "pci_bus_write_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int pci_bus_write_config_word(struct pci_bus * bus, unsigned int devfn, int pos, u16 value)
```

```json
{
  "name": "pci_bus_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584640768,
      "name": "pci_bus_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:67",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584640768,
      "name": "pci_bus_write_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
