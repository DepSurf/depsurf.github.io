# Function: <code>pci_write_config_word</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_write_config_word",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583228746,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:923",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pcie_capability_write_word"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583235454,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:923",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583251582,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:923",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "drivers/pci/pci.c:pci_reassigndev_resource_alignment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583275846,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:923",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583290686,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:923",
      "file": "drivers/pci/setup-res.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-res.c:pci_update_resource",
        "drivers/pci/setup-res.c:pci_update_resource",
        "drivers/pci/setup-res.c:pci_enable_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583294157,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:923",
      "file": "drivers/pci/setup-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:__pci_setup_bridge",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583305023,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:923",
      "file": "drivers/pci/vc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583317672,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:923",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_xio2000a"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583367321,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:923",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583381694,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:923",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_enable_msi_range",
        "drivers/pci/msi.c:pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583389812,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:923",
      "file": "drivers/pci/ats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/ats.c:pci_enable_ats",
        "drivers/pci/ats.c:pci_disable_pasid",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_enable_pri"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583392832,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:923",
      "file": "drivers/pci/iov.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "drivers/pci/iov.c:pci_restore_iov_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584209221,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:923",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp3_generic_configure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584212419,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:923",
      "file": "drivers/char/agp/isoch.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584219672,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:923",
      "file": "drivers/char/agp/intel-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "drivers/char/agp/intel-agp.c:intel_820_configure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584224758,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:923",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_enable_gtt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584286120,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:923",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585016942,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:923",
      "file": "drivers/ata/ata_piix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585021479,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:923",
      "file": "drivers/ata/pata_sis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/pata_sis.c:sis_old_set_dmamode",
        "drivers/ata/pata_sis.c:sis_66_set_dmamode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585024862,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:923",
      "file": "drivers/ata/ata_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/ata/ata_generic.c:ata_generic_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585331936,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:923",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/pci-quirks.c:uhci_reset_hc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585420742,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:923",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595306119,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:923",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:hwmon_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586155181,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:923",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_write_config_word",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583537434,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:934",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pcie_capability_write_word"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583550897,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:934",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:__pci_read_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583582792,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:934",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "drivers/pci/pci.c:pci_raw_set_power_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583586833,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:934",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583603137,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:934",
      "file": "drivers/pci/setup-res.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-res.c:pci_enable_resources",
        "drivers/pci/setup-res.c:pci_update_resource",
        "drivers/pci/setup-res.c:pci_update_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583611858,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:934",
      "file": "drivers/pci/setup-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_setup_bridge",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583617501,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:934",
      "file": "drivers/pci/vc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583628664,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:934",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_xio2000a"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583662584,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:934",
      "file": "drivers/pci/pcie/pcie-dpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pcie-dpc.c:dpc_remove",
        "drivers/pci/pcie/pcie-dpc.c:dpc_probe",
        "drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583680617,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:934",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583699759,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:934",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi.c:__pci_write_msi_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583704363,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:934",
      "file": "drivers/pci/ats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/ats.c:pci_disable_pasid",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_enable_ats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583709025,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:934",
      "file": "drivers/pci/iov.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "drivers/pci/iov.c:pci_iov_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584548641,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:934",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp3_generic_configure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584551957,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:934",
      "file": "drivers/char/agp/isoch.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584559713,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:934",
      "file": "drivers/char/agp/intel-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "drivers/char/agp/intel-agp.c:intel_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584564358,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:934",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_enable_gtt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584633309,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:934",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585387413,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:934",
      "file": "drivers/ata/ata_piix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585389609,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:934",
      "file": "drivers/ata/pata_sis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/pata_sis.c:sis_66_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_dmamode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585392773,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:934",
      "file": "drivers/ata/ata_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/ata/ata_generic.c:ata_generic_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585730630,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:934",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:uhci_reset_hc",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585834555,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:934",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595489364,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:934",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:hwmon_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586568100,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:934",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_write_config_word",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583673770,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:964",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pcie_capability_write_word"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583687441,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:964",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:__pci_read_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583719249,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:964",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "drivers/pci/pci.c:pci_raw_set_power_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583723985,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:964",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583740337,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:964",
      "file": "drivers/pci/setup-res.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-res.c:pci_enable_resources",
        "drivers/pci/setup-res.c:pci_update_resource",
        "drivers/pci/setup-res.c:pci_update_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583749058,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:964",
      "file": "drivers/pci/setup-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_setup_bridge",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583754701,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:964",
      "file": "drivers/pci/vc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583765960,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:964",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_xio2000a"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583799976,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:964",
      "file": "drivers/pci/pcie/pcie-dpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pcie-dpc.c:dpc_remove",
        "drivers/pci/pcie/pcie-dpc.c:dpc_probe",
        "drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583818729,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:964",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583837965,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:964",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi.c:__pci_write_msi_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583842683,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:964",
      "file": "drivers/pci/ats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/ats.c:pci_disable_pasid",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_enable_ats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583847361,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:964",
      "file": "drivers/pci/iov.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "drivers/pci/iov.c:pci_iov_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584730593,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:964",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp3_generic_configure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584733909,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:964",
      "file": "drivers/char/agp/isoch.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584741585,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:964",
      "file": "drivers/char/agp/intel-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "drivers/char/agp/intel-agp.c:intel_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584746246,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:964",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_enable_gtt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584817915,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:964",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585588245,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:964",
      "file": "drivers/ata/ata_piix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585590425,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:964",
      "file": "drivers/ata/pata_sis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/pata_sis.c:sis_66_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_dmamode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585593598,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:964",
      "file": "drivers/ata/ata_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/ata/ata_generic.c:ata_generic_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585919222,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:964",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:uhci_reset_hc",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586023291,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:964",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595742399,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:964",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:hwmon_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586749652,
      "name": "pci_write_config_word",
      "external": false,
      "loc": "include/linux/pci.h:964",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_write_config_word(const struct pci_dev * dev, int where, u16 val)
```

```json
{
  "name": "pci_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583714103,
      "name": "pci_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:942",
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
        "drivers/pci/probe.c:pci_setup_device",
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
        "drivers/pci/pci.c:pci_clear_mwi",
        "drivers/pci/pci.c:__pci_set_master",
        "drivers/pci/pci.c:pci_std_enable_acs",
        "drivers/pci/pci.c:pci_pme_restore",
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
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msix",
        "drivers/pci/msi.c:__pci_enable_msix",
        "drivers/pci/msi.c:__pci_enable_msix",
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
        "drivers/pci/ats.c:pci_restore_pri_state",
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
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
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
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:get_pci_parity_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583713680,
      "name": "pci_write_config_word.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071583713744,
      "name": "pci_write_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_write_config_word(const struct pci_dev * dev, int where, u16 val)
```

```json
{
  "name": "pci_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583971607,
      "name": "pci_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:942",
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
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/pci.c:pci_reassigndev_resource_alignment",
        "drivers/pci/pci.c:pci_set_vga_state",
        "drivers/pci/pci.c:pci_set_vga_state",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_reset_secondary_bus",
        "drivers/pci/pci.c:pci_reset_secondary_bus",
        "drivers/pci/pci.c:pci_clear_mwi",
        "drivers/pci/pci.c:__pci_set_master",
        "drivers/pci/pci.c:pci_std_enable_acs",
        "drivers/pci/pci.c:pci_pme_restore",
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
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msix",
        "drivers/pci/msi.c:__pci_enable_msix",
        "drivers/pci/msi.c:__pci_enable_msix",
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
        "drivers/pci/ats.c:pci_restore_pri_state",
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
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
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
        "drivers/iommu/amd_iommu.c:attach_device",
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
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:get_pci_parity_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583971168,
      "name": "pci_write_config_word.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071583971232,
      "name": "pci_write_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int pci_write_config_word(const struct pci_dev * dev, int where, u16 val)
```

```json
{
  "name": "pci_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584166682,
      "name": "pci_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:575",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pcie_capability_write_word"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/pci.c:pci_reassigndev_resource_alignment",
        "drivers/pci/pci.c:pci_set_vga_state",
        "drivers/pci/pci.c:pci_set_vga_state",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_reset_secondary_bus",
        "drivers/pci/pci.c:pci_reset_secondary_bus",
        "drivers/pci/pci.c:pci_clear_mwi",
        "drivers/pci/pci.c:__pci_set_master",
        "drivers/pci/pci.c:pci_std_enable_acs",
        "drivers/pci/pci.c:pci_pme_restore",
        "drivers/pci/pci.c:pci_check_pme_status",
        "drivers/pci/pci.c:do_pci_disable_device",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/setup-res.c:pci_enable_resources",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_setup_bridge",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/quirks.c:quirk_xio2000a",
        "drivers/pci/pcie/dpc.c:dpc_remove",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/pci/pcie/dpc.c:dpc_irq",
        "drivers/pci/pcie/dpc.c:dpc_irq",
        "drivers/pci/pcie/dpc.c:dpc_irq",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msix",
        "drivers/pci/msi.c:__pci_enable_msix",
        "drivers/pci/msi.c:__pci_enable_msix",
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
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_enable_ats",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
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
        "drivers/iommu/amd_iommu.c:attach_device",
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
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:get_pci_parity_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584165888,
      "name": "pci_write_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int pci_write_config_word(const struct pci_dev * dev, int where, u16 val)
```

```json
{
  "name": "pci_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584254574,
      "name": "pci_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:575",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pcie_capability_write_word"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/pci.c:pci_reassigndev_resource_alignment",
        "drivers/pci/pci.c:pci_set_vga_state",
        "drivers/pci/pci.c:pci_set_vga_state",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_reset_secondary_bus",
        "drivers/pci/pci.c:pci_reset_secondary_bus",
        "drivers/pci/pci.c:pci_clear_mwi",
        "drivers/pci/pci.c:__pci_set_master",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_pme_restore",
        "drivers/pci/pci.c:pci_check_pme_status",
        "drivers/pci/pci.c:do_pci_disable_device",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/setup-res.c:pci_enable_resources",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_setup_bridge",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:quirk_xio2000a",
        "drivers/pci/pcie/dpc.c:dpc_remove",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/pci/pcie/dpc.c:dpc_irq",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:pci_restore_dpc_state",
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
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_enable_ats",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
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
        "drivers/iommu/amd_iommu.c:attach_device",
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
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:get_pci_parity_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584253744,
      "name": "pci_write_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int pci_write_config_word(const struct pci_dev * dev, int where, u16 val)
```

```json
{
  "name": "pci_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584446912,
      "name": "pci_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:575",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:program_hpp_type0",
        "drivers/pci/probe.c:program_hpp_type0",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
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
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_pme_restore",
        "drivers/pci/pci.c:pci_check_pme_status",
        "drivers/pci/pci.c:do_pci_disable_device",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/setup-res.c:pci_enable_resources",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_setup_bridge",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:quirk_xio2000a",
        "drivers/pci/pcie/dpc.c:dpc_remove",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/pci/pcie/dpc.c:dpc_irq",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:pci_restore_dpc_state",
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
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_enable_ats",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
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
        "drivers/iommu/amd_iommu.c:attach_device",
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
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:get_pci_parity_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584446912,
      "name": "pci_write_config_word",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_write_config_word(const struct pci_dev * dev, int where, u16 val)
```

```json
{
  "name": "pci_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584583664,
      "name": "pci_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:566",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
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
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_pme_restore",
        "drivers/pci/pci.c:pci_check_pme_status",
        "drivers/pci/pci.c:do_pci_disable_device",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/setup-res.c:pci_enable_resources",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_setup_bridge",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:quirk_xio2000a",
        "drivers/pci/pcie/dpc.c:dpc_remove",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/pci/pcie/dpc.c:dpc_irq",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:pci_restore_dpc_state",
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
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_enable_ats",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
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
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_66_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_dmamode",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/usb/host/pci-quirks.c:uhci_reset_hc",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:get_pci_parity_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584583664,
      "name": "pci_write_config_word",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_write_config_word(const struct pci_dev * dev, int where, u16 val)
```

```json
{
  "name": "pci_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585260813,
      "name": "pci_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:562",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pcie_capability_write_word"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_msi_setup_pci_dev",
        "drivers/pci/probe.c:pci_msi_setup_pci_dev",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_read_bridge_windows",
        "drivers/pci/probe.c:pci_read_bridge_windows",
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
        "drivers/pci/pci.c:pci_clear_master",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_disable_acs_redir",
        "drivers/pci/pci.c:pci_pme_restore",
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci.c:pci_disable_enabled_device",
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/pci.c:pci_status_get_and_clear_errors",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/setup-res.c:pci_enable_resources",
        "drivers/pci/setup-res.c:pci_std_update_resource",
        "drivers/pci/setup-res.c:pci_std_update_resource",
        "drivers/pci/setup-bus.c:__pci_setup_bridge",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/pcie/dpc.c:dpc_remove",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/pci/pcie/dpc.c:dpc_irq",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:pci_restore_dpc_state",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr",
        "drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:quirk_intel_mc_errata",
        "drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt",
        "drivers/pci/quirks.c:quirk_xio2000a",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:msi_capability_init",
        "drivers/pci/msi.c:msi_capability_init",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/ats.c:pci_restore_pasid_state",
        "drivers/pci/ats.c:pci_disable_pasid",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_restore_ats_state",
        "drivers/pci/ats.c:pci_disable_ats",
        "drivers/pci/ats.c:pci_enable_ats",
        "drivers/pci/iov.c:sriov_restore_state",
        "drivers/pci/iov.c:sriov_restore_state",
        "drivers/pci/iov.c:sriov_restore_state",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable",
        "drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable",
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
        "drivers/iommu/amd/iommu.c:pdev_iommuv2_enable",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_66_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_dmamode",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/usb/host/pci-quirks.c:uhci_reset_hc",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/hwmon/hwmon.c:hwmon_pci_quirks",
        "drivers/edac/edac_pci_sysfs.c:get_pci_parity_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585259520,
      "name": "pci_write_config_word",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_write_config_word(const struct pci_dev * dev, int where, u16 val)
```

```json
{
  "name": "pci_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585418540,
      "name": "pci_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:562",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pcie_capability_write_word"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_read_bridge_windows",
        "drivers/pci/probe.c:pci_read_bridge_windows",
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
        "drivers/pci/pci.c:pci_clear_master",
        "drivers/pci/pci.c:pci_pme_restore",
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci.c:pci_disable_enabled_device",
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_disable_acs_redir",
        "drivers/pci/pci.c:pci_status_get_and_clear_errors",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/setup-res.c:pci_enable_resources",
        "drivers/pci/setup-res.c:pci_std_update_resource",
        "drivers/pci/setup-res.c:pci_std_update_resource",
        "drivers/pci/setup-bus.c:__pci_setup_bridge",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/msi.c:pci_msix_init",
        "drivers/pci/msi.c:pci_msi_init",
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:msi_capability_init",
        "drivers/pci/msi.c:msi_capability_init",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/pcie/dpc.c:dpc_remove",
        "drivers/pci/pcie/dpc.c:dpc_suspend",
        "drivers/pci/pcie/dpc.c:dpc_irq",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:pci_restore_dpc_state",
        "drivers/pci/pcie/ptm.c:pci_restore_ptm_state",
        "drivers/pci/pcie/ptm.c:pci_disable_ptm",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr",
        "drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:quirk_intel_mc_errata",
        "drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt",
        "drivers/pci/quirks.c:quirk_xio2000a",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/ats.c:pci_restore_pasid_state",
        "drivers/pci/ats.c:pci_disable_pasid",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_restore_ats_state",
        "drivers/pci/ats.c:pci_disable_ats",
        "drivers/pci/ats.c:pci_enable_ats",
        "drivers/pci/iov.c:sriov_restore_state",
        "drivers/pci/iov.c:sriov_restore_state",
        "drivers/pci/iov.c:sriov_restore_state",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable",
        "drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable",
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
        "drivers/iommu/amd/iommu.c:pdev_iommuv2_enable",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_66_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_dmamode",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/usb/host/pci-quirks.c:uhci_reset_hc",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/hwmon/hwmon.c:hwmon_pci_quirks",
        "drivers/edac/edac_pci_sysfs.c:get_pci_parity_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585417248,
      "name": "pci_write_config_word",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_write_config_word(const struct pci_dev * dev, int where, u16 val)
```

```json
{
  "name": "pci_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585298892,
      "name": "pci_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:562",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pcie_capability_write_word"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
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
        "drivers/pci/pci.c:pci_disable_parity",
        "drivers/pci/pci.c:pci_clear_master",
        "drivers/pci/pci.c:pci_pme_restore",
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci.c:pci_disable_enabled_device",
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_status_get_and_clear_errors",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/setup-res.c:pci_enable_resources",
        "drivers/pci/setup-res.c:pci_std_update_resource",
        "drivers/pci/setup-res.c:pci_std_update_resource",
        "drivers/pci/setup-bus.c:__pci_setup_bridge",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/msi.c:pci_msix_init",
        "drivers/pci/msi.c:pci_msi_init",
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:msi_capability_init",
        "drivers/pci/msi.c:msi_capability_init",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/pcie/dpc.c:dpc_remove",
        "drivers/pci/pcie/dpc.c:dpc_suspend",
        "drivers/pci/pcie/dpc.c:dpc_irq",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:pci_restore_dpc_state",
        "drivers/pci/pcie/ptm.c:pci_restore_ptm_state",
        "drivers/pci/pcie/ptm.c:pci_disable_ptm",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr",
        "drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:quirk_intel_mc_errata",
        "drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt",
        "drivers/pci/quirks.c:quirk_xio2000a",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/ats.c:pci_restore_pasid_state",
        "drivers/pci/ats.c:pci_disable_pasid",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_restore_ats_state",
        "drivers/pci/ats.c:pci_disable_ats",
        "drivers/pci/ats.c:pci_enable_ats",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable",
        "drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable",
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
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_66_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_dmamode",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/usb/host/pci-quirks.c:uhci_reset_hc",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:get_pci_parity_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585297824,
      "name": "pci_write_config_word",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_write_config_word(const struct pci_dev * dev, int where, u16 val)
```

```json
{
  "name": "pci_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585755852,
      "name": "pci_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:562",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pcie_capability_write_word"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/pci.c:pci_reassigndev_resource_alignment",
        "drivers/pci/pci.c:pci_set_vga_state",
        "drivers/pci/pci.c:pci_set_vga_state",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_reset_secondary_bus",
        "drivers/pci/pci.c:pci_reset_secondary_bus",
        "drivers/pci/pci.c:pci_pm_reset",
        "drivers/pci/pci.c:pci_pm_reset",
        "drivers/pci/pci.c:pci_intx",
        "drivers/pci/pci.c:pci_disable_parity",
        "drivers/pci/pci.c:pci_clear_master",
        "drivers/pci/pci.c:pci_pme_restore",
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci.c:pci_disable_enabled_device",
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_status_get_and_clear_errors",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/setup-res.c:pci_enable_resources",
        "drivers/pci/setup-res.c:pci_std_update_resource",
        "drivers/pci/setup-res.c:pci_std_update_resource",
        "drivers/pci/setup-bus.c:__pci_setup_bridge",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/msi.c:pci_msix_init",
        "drivers/pci/msi.c:pci_msi_init",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi.c:__pci_write_msi_msg",
        "drivers/pci/pcie/dpc.c:dpc_remove",
        "drivers/pci/pcie/dpc.c:dpc_suspend",
        "drivers/pci/pcie/dpc.c:dpc_irq",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:pci_restore_dpc_state",
        "drivers/pci/pcie/ptm.c:pci_restore_ptm_state",
        "drivers/pci/pcie/ptm.c:pci_disable_ptm",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr",
        "drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:quirk_intel_mc_errata",
        "drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt",
        "drivers/pci/quirks.c:quirk_xio2000a",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/ats.c:pci_restore_pasid_state",
        "drivers/pci/ats.c:pci_disable_pasid",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_restore_ats_state",
        "drivers/pci/ats.c:pci_disable_ats",
        "drivers/pci/ats.c:pci_enable_ats",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable",
        "drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable",
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
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_66_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_dmamode",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable",
        "drivers/usb/host/pci-quirks.c:uhci_reset_hc",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:get_pci_parity_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585754608,
      "name": "pci_write_config_word",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_write_config_word(const struct pci_dev * dev, int where, u16 val)
```

```json
{
  "name": "pci_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586938416,
      "name": "pci_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:567",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_read_bridge_windows",
        "drivers/pci/probe.c:pci_read_bridge_windows",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/pci.c:pci_reassigndev_resource_alignment",
        "drivers/pci/pci.c:pci_set_vga_state",
        "drivers/pci/pci.c:pci_set_vga_state",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_reset_secondary_bus",
        "drivers/pci/pci.c:pci_reset_secondary_bus",
        "drivers/pci/pci.c:pci_pm_reset",
        "drivers/pci/pci.c:pci_pm_reset",
        "drivers/pci/pci.c:pci_intx",
        "drivers/pci/pci.c:pci_disable_parity",
        "drivers/pci/pci.c:pci_set_mwi",
        "drivers/pci/pci.c:__pci_set_master",
        "drivers/pci/pci.c:pci_pme_restore",
        "drivers/pci/pci.c:__pci_pme_active",
        "drivers/pci/pci.c:pci_check_pme_status",
        "drivers/pci/pci.c:do_pci_disable_device",
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci.c:do_pci_enable_device",
        "drivers/pci/pci.c:pci_set_low_power_state",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_status_get_and_clear_errors",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/setup-res.c:pci_enable_resources",
        "drivers/pci/setup-res.c:pci_std_update_resource",
        "drivers/pci/setup-res.c:pci_std_update_resource",
        "drivers/pci/setup-bus.c:__pci_setup_bridge",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/msi/pcidev_msi.c:pci_msix_init",
        "drivers/pci/msi/pcidev_msi.c:pci_msi_init",
        "drivers/pci/msi/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi/msi.c:msix_capability_init",
        "drivers/pci/msi/msi.c:msix_capability_init",
        "drivers/pci/msi/msi.c:msix_capability_init",
        "drivers/pci/msi/msi.c:pci_restore_msi_state",
        "drivers/pci/msi/msi.c:pci_restore_msi_state",
        "drivers/pci/msi/msi.c:pci_restore_msi_state",
        "drivers/pci/msi/msi.c:pci_restore_msi_state",
        "drivers/pci/msi/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi/msi.c:__pci_write_msi_msg",
        "drivers/pci/pcie/dpc.c:dpc_irq",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:pci_restore_dpc_state",
        "drivers/pci/pcie/ptm.c:pci_restore_ptm_state",
        "drivers/pci/pcie/ptm.c:pci_disable_ptm",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr",
        "drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr",
        "drivers/pci/quirks.c:pci_fixup_pericom_acs_store_forward",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:reset_hinic_vf_dev",
        "drivers/pci/quirks.c:nvme_disable_and_flr",
        "drivers/pci/quirks.c:reset_chelsio_generic_dev",
        "drivers/pci/quirks.c:reset_chelsio_generic_dev",
        "drivers/pci/quirks.c:reset_chelsio_generic_dev",
        "drivers/pci/quirks.c:quirk_intel_mc_errata",
        "drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt",
        "drivers/pci/quirks.c:asus_hides_smbus_lpc",
        "drivers/pci/quirks.c:quirk_disable_pxb",
        "drivers/pci/quirks.c:quirk_xio2000a",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/ats.c:pci_restore_pasid_state",
        "drivers/pci/ats.c:pci_disable_pasid",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_restore_ats_state",
        "drivers/pci/ats.c:pci_disable_ats",
        "drivers/pci/ats.c:pci_enable_ats",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable",
        "drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable",
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
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_66_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_dmamode",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_memory_lock_and_enable",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable",
        "drivers/usb/host/pci-quirks.c:uhci_reset_hc",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:get_pci_parity_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586938416,
      "name": "pci_write_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int pci_write_config_word(const struct pci_dev * dev, int where, u16 val)
```

```json
{
  "name": "pci_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588095728,
      "name": "pci_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:573",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_read_bridge_windows",
        "drivers/pci/probe.c:pci_read_bridge_windows",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/pci.c:pci_reassigndev_resource_alignment",
        "drivers/pci/pci.c:pci_set_vga_state",
        "drivers/pci/pci.c:pci_set_vga_state",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_reset_secondary_bus",
        "drivers/pci/pci.c:pci_reset_secondary_bus",
        "drivers/pci/pci.c:pci_pm_reset",
        "drivers/pci/pci.c:pci_pm_reset",
        "drivers/pci/pci.c:pci_intx",
        "drivers/pci/pci.c:pci_disable_parity",
        "drivers/pci/pci.c:pci_set_mwi",
        "drivers/pci/pci.c:pci_clear_master",
        "drivers/pci/pci.c:pci_pme_restore",
        "drivers/pci/pci.c:__pci_pme_active",
        "drivers/pci/pci.c:pci_check_pme_status",
        "drivers/pci/pci.c:do_pci_disable_device",
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci.c:do_pci_enable_device",
        "drivers/pci/pci.c:pci_set_low_power_state",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_status_get_and_clear_errors",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-sysfs.c:resource5_resize_store",
        "drivers/pci/pci-sysfs.c:resource5_resize_store",
        "drivers/pci/pci-sysfs.c:resource4_resize_store",
        "drivers/pci/pci-sysfs.c:resource4_resize_store",
        "drivers/pci/pci-sysfs.c:resource3_resize_store",
        "drivers/pci/pci-sysfs.c:resource3_resize_store",
        "drivers/pci/pci-sysfs.c:resource2_resize_store",
        "drivers/pci/pci-sysfs.c:resource2_resize_store",
        "drivers/pci/pci-sysfs.c:resource1_resize_store",
        "drivers/pci/pci-sysfs.c:resource1_resize_store",
        "drivers/pci/pci-sysfs.c:resource0_resize_store",
        "drivers/pci/pci-sysfs.c:resource0_resize_store",
        "drivers/pci/setup-res.c:pci_enable_resources",
        "drivers/pci/setup-res.c:pci_std_update_resource",
        "drivers/pci/setup-res.c:pci_std_update_resource",
        "drivers/pci/setup-bus.c:pci_bus_release_bridge_resources",
        "drivers/pci/setup-bus.c:pci_setup_bridge",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/msi/pcidev_msi.c:pci_msix_init",
        "drivers/pci/msi/pcidev_msi.c:pci_msi_init",
        "drivers/pci/msi/msi.c:pci_msix_shutdown",
        "drivers/pci/msi/msi.c:__pci_restore_msix_state",
        "drivers/pci/msi/msi.c:__pci_restore_msix_state",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:pci_msi_shutdown",
        "drivers/pci/msi/msi.c:__pci_restore_msi_state",
        "drivers/pci/msi/msi.c:__pci_restore_msi_state",
        "drivers/pci/msi/msi.c:msi_capability_init",
        "drivers/pci/msi/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi/msi.c:__pci_write_msi_msg",
        "drivers/pci/pcie/dpc.c:dpc_remove",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/pci/pcie/dpc.c:dpc_irq",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:pci_restore_dpc_state",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr",
        "drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr",
        "drivers/pci/quirks.c:pci_fixup_pericom_acs_store_forward",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:pci_quirk_enable_intel_pch_acs",
        "drivers/pci/quirks.c:reset_hinic_vf_dev",
        "drivers/pci/quirks.c:nvme_disable_and_flr",
        "drivers/pci/quirks.c:reset_chelsio_generic_dev",
        "drivers/pci/quirks.c:reset_chelsio_generic_dev",
        "drivers/pci/quirks.c:reset_chelsio_generic_dev",
        "drivers/pci/quirks.c:quirk_intel_mc_errata",
        "drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt",
        "drivers/pci/quirks.c:asus_hides_smbus_lpc",
        "drivers/pci/quirks.c:quirk_disable_pxb",
        "drivers/pci/quirks.c:quirk_xio2000a",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/ats.c:pci_restore_pasid_state",
        "drivers/pci/ats.c:pci_disable_pasid",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_restore_ats_state",
        "drivers/pci/ats.c:pci_disable_ats",
        "drivers/pci/ats.c:pci_enable_ats",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable",
        "drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable",
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
        "drivers/char/agp/intel-gtt.c:intel_gmch_enable_gtt",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_66_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_dmamode",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/usb/host/pci-quirks.c:uhci_reset_hc",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:get_pci_parity_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588095728,
      "name": "pci_write_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int pci_write_config_word(const struct pci_dev * dev, int where, u16 val)
```

```json
{
  "name": "pci_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588370160,
      "name": "pci_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:587",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_read_bridge_windows",
        "drivers/pci/probe.c:pci_read_bridge_windows",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/pci.c:pci_reassigndev_resource_alignment",
        "drivers/pci/pci.c:pci_set_vga_state",
        "drivers/pci/pci.c:pci_set_vga_state",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_reset_secondary_bus",
        "drivers/pci/pci.c:pci_reset_secondary_bus",
        "drivers/pci/pci.c:pci_pm_reset",
        "drivers/pci/pci.c:pci_pm_reset",
        "drivers/pci/pci.c:pci_intx",
        "drivers/pci/pci.c:pci_disable_parity",
        "drivers/pci/pci.c:pci_set_mwi",
        "drivers/pci/pci.c:pci_clear_master",
        "drivers/pci/pci.c:pci_pme_restore",
        "drivers/pci/pci.c:__pci_pme_active",
        "drivers/pci/pci.c:pci_check_pme_status",
        "drivers/pci/pci.c:do_pci_disable_device",
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci.c:do_pci_enable_device",
        "drivers/pci/pci.c:pci_set_low_power_state",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_status_get_and_clear_errors",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-sysfs.c:resource5_resize_store",
        "drivers/pci/pci-sysfs.c:resource5_resize_store",
        "drivers/pci/pci-sysfs.c:resource4_resize_store",
        "drivers/pci/pci-sysfs.c:resource4_resize_store",
        "drivers/pci/pci-sysfs.c:resource3_resize_store",
        "drivers/pci/pci-sysfs.c:resource3_resize_store",
        "drivers/pci/pci-sysfs.c:resource2_resize_store",
        "drivers/pci/pci-sysfs.c:resource2_resize_store",
        "drivers/pci/pci-sysfs.c:resource1_resize_store",
        "drivers/pci/pci-sysfs.c:resource1_resize_store",
        "drivers/pci/pci-sysfs.c:resource0_resize_store",
        "drivers/pci/pci-sysfs.c:resource0_resize_store",
        "drivers/pci/setup-res.c:pci_enable_resources",
        "drivers/pci/setup-res.c:pci_std_update_resource",
        "drivers/pci/setup-res.c:pci_std_update_resource",
        "drivers/pci/setup-bus.c:pci_bus_release_bridge_resources",
        "drivers/pci/setup-bus.c:pci_setup_bridge",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/msi/pcidev_msi.c:pci_msix_init",
        "drivers/pci/msi/pcidev_msi.c:pci_msi_init",
        "drivers/pci/msi/msi.c:pci_msix_shutdown",
        "drivers/pci/msi/msi.c:__pci_restore_msix_state",
        "drivers/pci/msi/msi.c:__pci_restore_msix_state",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:pci_msi_shutdown",
        "drivers/pci/msi/msi.c:__pci_restore_msi_state",
        "drivers/pci/msi/msi.c:__pci_restore_msi_state",
        "drivers/pci/msi/msi.c:msi_capability_init",
        "drivers/pci/msi/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi/msi.c:__pci_write_msi_msg",
        "drivers/pci/pcie/dpc.c:dpc_irq",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:pci_restore_dpc_state",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/quirks.c:pci_fixup_pericom_acs_store_forward",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:pci_quirk_enable_intel_pch_acs",
        "drivers/pci/quirks.c:reset_hinic_vf_dev",
        "drivers/pci/quirks.c:nvme_disable_and_flr",
        "drivers/pci/quirks.c:reset_chelsio_generic_dev",
        "drivers/pci/quirks.c:reset_chelsio_generic_dev",
        "drivers/pci/quirks.c:reset_chelsio_generic_dev",
        "drivers/pci/quirks.c:quirk_intel_mc_errata",
        "drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt",
        "drivers/pci/quirks.c:asus_hides_smbus_lpc",
        "drivers/pci/quirks.c:quirk_disable_pxb",
        "drivers/pci/quirks.c:quirk_xio2000a",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/ats.c:pci_restore_pasid_state",
        "drivers/pci/ats.c:pci_disable_pasid",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_restore_ats_state",
        "drivers/pci/ats.c:pci_disable_ats",
        "drivers/pci/ats.c:pci_enable_ats",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable",
        "drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable",
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
        "drivers/char/agp/intel-gtt.c:intel_gmch_enable_gtt",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_66_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_dmamode",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/usb/host/pci-quirks.c:uhci_reset_hc",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:get_pci_parity_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588370160,
      "name": "pci_write_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int pci_write_config_word(const struct pci_dev * dev, int where, u16 val)
```

```json
{
  "name": "pci_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588664928,
      "name": "pci_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:585",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_read_bridge_windows",
        "drivers/pci/probe.c:pci_read_bridge_windows",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/pci.c:pci_reassigndev_resource_alignment",
        "drivers/pci/pci.c:pci_set_vga_state",
        "drivers/pci/pci.c:pci_set_vga_state",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_reset_secondary_bus",
        "drivers/pci/pci.c:pci_reset_secondary_bus",
        "drivers/pci/pci.c:pci_pm_reset",
        "drivers/pci/pci.c:pci_pm_reset",
        "drivers/pci/pci.c:pci_intx",
        "drivers/pci/pci.c:pci_disable_parity",
        "drivers/pci/pci.c:pci_set_mwi",
        "drivers/pci/pci.c:pci_clear_master",
        "drivers/pci/pci.c:pci_pme_restore",
        "drivers/pci/pci.c:__pci_pme_active",
        "drivers/pci/pci.c:pci_check_pme_status",
        "drivers/pci/pci.c:do_pci_disable_device",
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci.c:do_pci_enable_device",
        "drivers/pci/pci.c:pci_set_low_power_state",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_status_get_and_clear_errors",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-sysfs.c:resource5_resize_store",
        "drivers/pci/pci-sysfs.c:resource5_resize_store",
        "drivers/pci/pci-sysfs.c:resource4_resize_store",
        "drivers/pci/pci-sysfs.c:resource4_resize_store",
        "drivers/pci/pci-sysfs.c:resource3_resize_store",
        "drivers/pci/pci-sysfs.c:resource3_resize_store",
        "drivers/pci/pci-sysfs.c:resource2_resize_store",
        "drivers/pci/pci-sysfs.c:resource2_resize_store",
        "drivers/pci/pci-sysfs.c:resource1_resize_store",
        "drivers/pci/pci-sysfs.c:resource1_resize_store",
        "drivers/pci/pci-sysfs.c:resource0_resize_store",
        "drivers/pci/pci-sysfs.c:resource0_resize_store",
        "drivers/pci/setup-res.c:pci_enable_resources",
        "drivers/pci/setup-res.c:pci_std_update_resource",
        "drivers/pci/setup-res.c:pci_std_update_resource",
        "drivers/pci/setup-bus.c:pci_bus_release_bridge_resources",
        "drivers/pci/setup-bus.c:pci_setup_bridge",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/msi/pcidev_msi.c:pci_msix_init",
        "drivers/pci/msi/pcidev_msi.c:pci_msi_init",
        "drivers/pci/msi/msi.c:pci_msix_shutdown",
        "drivers/pci/msi/msi.c:__pci_restore_msix_state",
        "drivers/pci/msi/msi.c:__pci_restore_msix_state",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:pci_msi_shutdown",
        "drivers/pci/msi/msi.c:__pci_restore_msi_state",
        "drivers/pci/msi/msi.c:__pci_restore_msi_state",
        "drivers/pci/msi/msi.c:msi_capability_init",
        "drivers/pci/msi/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi/msi.c:__pci_write_msi_msg",
        "drivers/pci/msi/msi.c:__pci_write_msi_msg",
        "drivers/pci/pcie/dpc.c:dpc_irq",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:pci_restore_dpc_state",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/quirks.c:pci_fixup_pericom_acs_store_forward",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:pci_quirk_enable_intel_pch_acs",
        "drivers/pci/quirks.c:reset_hinic_vf_dev",
        "drivers/pci/quirks.c:nvme_disable_and_flr",
        "drivers/pci/quirks.c:reset_chelsio_generic_dev",
        "drivers/pci/quirks.c:reset_chelsio_generic_dev",
        "drivers/pci/quirks.c:reset_chelsio_generic_dev",
        "drivers/pci/quirks.c:quirk_intel_mc_errata",
        "drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt",
        "drivers/pci/quirks.c:asus_hides_smbus_lpc",
        "drivers/pci/quirks.c:quirk_disable_pxb",
        "drivers/pci/quirks.c:quirk_xio2000a",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/ats.c:pci_restore_pasid_state",
        "drivers/pci/ats.c:pci_disable_pasid",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_restore_ats_state",
        "drivers/pci/ats.c:pci_disable_ats",
        "drivers/pci/ats.c:pci_enable_ats",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable",
        "drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable",
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
        "drivers/char/agp/intel-gtt.c:intel_gmch_enable_gtt",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_66_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_dmamode",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/usb/host/pci-quirks.c:uhci_reset_hc",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:get_pci_parity_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588664928,
      "name": "pci_write_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int pci_write_config_word(const struct pci_dev * dev, int where, u16 val)
```

```json
{
  "name": "pci_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496823828,
      "name": "pci_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:566",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pcie_capability_write_word"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
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
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_pme_restore",
        "drivers/pci/pci.c:pci_check_pme_status",
        "drivers/pci/pci.c:do_pci_disable_device",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/setup-res.c:pci_enable_resources",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_setup_bridge",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:quirk_xio2000a",
        "drivers/pci/pcie/dpc.c:dpc_remove",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/pci/pcie/dpc.c:dpc_irq",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:pci_restore_dpc_state",
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
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_enable_ats",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/usb/host/pci-quirks.c:uhci_reset_hc",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/edac/edac_pci_sysfs.c:get_pci_parity_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496823640,
      "name": "pci_write_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int pci_write_config_word(const struct pci_dev * dev, int where, u16 val)
```

```json
{
  "name": "pci_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230105156,
      "name": "pci_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:566",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pcie_capability_write_word"
      ],
      "caller_func": [
        "arch/arm/kernel/bios32.c:pcibios_fixup_bus",
        "arch/arm/kernel/bios32.c:pcibios_fixup_bus",
        "arch/arm/kernel/bios32.c:pcibios_fixup_bus",
        "arch/arm/kernel/bios32.c:pci_fixup_83c553",
        "arch/arm/kernel/bios32.c:pci_fixup_83c553",
        "arch/arm/kernel/bios32.c:pcibios_bus_report_status",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
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
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_pme_restore",
        "drivers/pci/pci.c:pci_check_pme_status",
        "drivers/pci/pci.c:do_pci_disable_device",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/setup-res.c:pci_enable_resources",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_setup_bridge",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:quirk_xio2000a",
        "drivers/pci/pcie/dpc.c:dpc_remove",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/pci/pcie/dpc.c:dpc_irq",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:pci_restore_dpc_state",
        "drivers/pci/msi.c:__pci_enable_msi_range",
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
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_enable_ats",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/usb/host/pci-quirks.c:uhci_reset_hc",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/edac/edac_pci_sysfs.c:get_pci_parity_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230102264,
      "name": "pci_write_config_word",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int pci_write_config_word(const struct pci_dev * dev, int where, u16 val)
```

```json
{
  "name": "pci_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290890608,
      "name": "pci_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:566",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/eeh.c:eeh_dev_break_write",
        "arch/powerpc/kernel/eeh.c:eeh_dev_break_write",
        "arch/powerpc/kernel/eeh.c:eeh_disable_and_save_dev_state",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
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
        "drivers/pci/pci.c:__pci_set_master",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_pme_restore",
        "drivers/pci/pci.c:pci_check_pme_status",
        "drivers/pci/pci.c:do_pci_disable_device",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/setup-res.c:pci_enable_resources",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_setup_bridge",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:quirk_xio2000a",
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
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_restore_ats_state",
        "drivers/pci/ats.c:pci_restore_ats_state",
        "drivers/pci/ats.c:pci_enable_ats",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable",
        "drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/usb/host/pci-quirks.c:uhci_reset_hc",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/edac/edac_pci_sysfs.c:get_pci_parity_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290890608,
      "name": "pci_write_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int pci_write_config_word(const struct pci_dev * dev, int where, u16 val)
```

```json
{
  "name": "pci_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275529592,
      "name": "pci_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:566",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pcie_capability_write_word"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
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
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_pme_restore",
        "drivers/pci/pci.c:pci_check_pme_status",
        "drivers/pci/pci.c:do_pci_disable_device",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/setup-res.c:pci_enable_resources",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_setup_bridge",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:quirk_xio2000a",
        "drivers/pci/pcie/dpc.c:dpc_remove",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/pci/pcie/dpc.c:dpc_irq",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:pci_restore_dpc_state",
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
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_restore_ats_state",
        "drivers/pci/ats.c:pci_enable_ats",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/usb/host/pci-quirks.c:uhci_reset_hc",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/edac/edac_pci_sysfs.c:get_pci_parity_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275528808,
      "name": "pci_write_config_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int pci_write_config_word(const struct pci_dev * dev, int where, u16 val)
```

```json
{
  "name": "pci_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584535824,
      "name": "pci_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:566",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
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
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_pme_restore",
        "drivers/pci/pci.c:pci_check_pme_status",
        "drivers/pci/pci.c:do_pci_disable_device",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/setup-res.c:pci_enable_resources",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_setup_bridge",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:quirk_xio2000a",
        "drivers/pci/pcie/dpc.c:dpc_remove",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/pci/pcie/dpc.c:dpc_irq",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:pci_restore_dpc_state",
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
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_enable_ats",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
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
        "drivers/iommu/amd_iommu.c:attach_device",
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
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:get_pci_parity_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584535824,
      "name": "pci_write_config_word",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int pci_write_config_word(const struct pci_dev * dev, int where, u16 val)
```

```json
{
  "name": "pci_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584464000,
      "name": "pci_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:566",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
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
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_pme_restore",
        "drivers/pci/pci.c:pci_check_pme_status",
        "drivers/pci/pci.c:do_pci_disable_device",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/setup-res.c:pci_enable_resources",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_setup_bridge",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:quirk_xio2000a",
        "drivers/pci/pcie/dpc.c:dpc_remove",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/pci/pcie/dpc.c:dpc_irq",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:pci_restore_dpc_state",
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
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_enable_ats",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
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
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_66_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_dmamode",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/usb/host/pci-quirks.c:uhci_reset_hc",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:get_pci_parity_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584464000,
      "name": "pci_write_config_word",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int pci_write_config_word(const struct pci_dev * dev, int where, u16 val)
```

```json
{
  "name": "pci_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584533824,
      "name": "pci_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:566",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
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
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_pme_restore",
        "drivers/pci/pci.c:pci_check_pme_status",
        "drivers/pci/pci.c:do_pci_disable_device",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/setup-res.c:pci_enable_resources",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_setup_bridge",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:quirk_xio2000a",
        "drivers/pci/pcie/dpc.c:dpc_remove",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/pci/pcie/dpc.c:dpc_irq",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:pci_restore_dpc_state",
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
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_enable_ats",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
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
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_66_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_dmamode",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/usb/host/pci-quirks.c:uhci_reset_hc",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:get_pci_parity_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584533824,
      "name": "pci_write_config_word",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int pci_write_config_word(const struct pci_dev * dev, int where, u16 val)
```

```json
{
  "name": "pci_write_config_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584641600,
      "name": "pci_write_config_word",
      "external": true,
      "loc": "drivers/pci/access.c:566",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
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
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_pme_restore",
        "drivers/pci/pci.c:pci_check_pme_status",
        "drivers/pci/pci.c:do_pci_disable_device",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/setup-res.c:pci_enable_resources",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:__pci_setup_bridge",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:quirk_xio2000a",
        "drivers/pci/pcie/dpc.c:dpc_remove",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/pci/pcie/dpc.c:dpc_irq",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:pci_restore_dpc_state",
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
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_enable_ats",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_restore_iov_state",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
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
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_66_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_dmamode",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/ata/ata_generic.c:ata_generic_init_one",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/usb/host/pci-quirks.c:uhci_reset_hc",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/pci-quirks.c:sb800_prefetch",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:get_pci_parity_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584641600,
      "name": "pci_write_config_word",
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int pci_write_config_word(const struct pci_dev * dev, int where, u16 val)
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
