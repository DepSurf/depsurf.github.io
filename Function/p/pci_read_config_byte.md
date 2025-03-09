# Function: <code>pci_read_config_byte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_read_config_byte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579063533,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:906",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583234406,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:906",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_read_irq",
        "drivers/pci/probe.c:pci_read_irq",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583251252,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:906",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:__pci_find_next_ht_cap",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583313190,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:906",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_via_acpi",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert",
        "drivers/pci/quirks.c:quirk_mediagx_master",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_svwks_csb5ide",
        "drivers/pci/quirks.c:quirk_ide_samemode",
        "drivers/pci/quirks.c:quirk_sis_96x_smbus",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap",
        "drivers/pci/quirks.c:quirk_unhide_mch_dev6",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_via_vlink",
        "drivers/pci/quirks.c:quirk_jmicron_ata",
        "drivers/pci/quirks.c:msi_ht_cap_enabled",
        "drivers/pci/quirks.c:ht_enable_msi_mapping",
        "drivers/pci/quirks.c:ht_check_msi_mapping",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583367355,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:906",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583395499,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:906",
      "file": "drivers/pci/iov.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_iov_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583572629,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:906",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583831179,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:906",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:map_capability",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584129720,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:906",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584213464,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:906",
      "file": "drivers/char/agp/isoch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/isoch.c:agp_3_5_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584221750,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:906",
      "file": "drivers/char/agp/intel-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-agp.c:intel_8xx_fetch_size",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_820_cleanup",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_815_fetch_size",
        "drivers/char/agp/intel-agp.c:intel_815_configure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584231562,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:906",
      "file": "drivers/char/agp/via-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/via-agp.c:via_fetch_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584911485,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:906",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:pci_test_config_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584993682,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:906",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585017021,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:906",
      "file": "drivers/ata/ata_piix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585020518,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:906",
      "file": "drivers/ata/pata_sis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/pata_sis.c:sis_66_cable_detect",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585385452,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:906",
      "file": "drivers/usb/host/ehci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585538784,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:906",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595306045,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:906",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:hwmon_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586149622,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:906",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_pcifront_enable_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586153175,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:906",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450gx",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586156828,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:906",
      "file": "arch/x86/pci/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/irq.c:read_config_nybble",
        "arch/x86/pci/irq.c:pirq_sis_get",
        "arch/x86/pci/irq.c:pirq_piix_get",
        "arch/x86/pci/irq.c:write_config_nybble",
        "arch/x86/pci/irq.c:pirq_sis_set",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pirq_enable_irq",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs"
      ],
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
  "name": "pci_read_config_byte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579059949,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:917",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583549902,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:917",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_read_irq",
        "drivers/pci/probe.c:pci_read_irq",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583564843,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:917",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/pci.c:__pci_find_next_ht_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583641555,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:917",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ht_check_msi_mapping",
        "drivers/pci/quirks.c:ht_enable_msi_mapping",
        "drivers/pci/quirks.c:msi_ht_cap_enabled",
        "drivers/pci/quirks.c:quirk_unhide_mch_dev6",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap",
        "drivers/pci/quirks.c:quirk_jmicron_ata",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_sis_96x_smbus",
        "drivers/pci/quirks.c:quirk_ide_samemode",
        "drivers/pci/quirks.c:quirk_svwks_csb5ide",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_mediagx_master",
        "drivers/pci/quirks.c:quirk_via_vlink",
        "drivers/pci/quirks.c:quirk_via_acpi",
        "drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583680651,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:917",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583709907,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:917",
      "file": "drivers/pci/iov.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_iov_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583894942,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:917",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584162016,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:917",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:map_capability"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584466584,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:917",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584553029,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:917",
      "file": "drivers/char/agp/isoch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/isoch.c:agp_3_5_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584561674,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:917",
      "file": "drivers/char/agp/intel-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_820_cleanup",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_815_fetch_size",
        "drivers/char/agp/intel-agp.c:intel_8xx_fetch_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584571338,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:917",
      "file": "drivers/char/agp/via-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/via-agp.c:via_fetch_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585273437,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:917",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:pci_test_config_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585361690,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:917",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585386953,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:917",
      "file": "drivers/ata/ata_piix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585392023,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:917",
      "file": "drivers/ata/pata_sis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_66_cable_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585782257,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:917",
      "file": "drivers/usb/host/ehci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585932557,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:917",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595489290,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:917",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:hwmon_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586562454,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:917",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_pcifront_enable_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586566742,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:917",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_fixup_i450gx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586573590,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:917",
      "file": "arch/x86/pci/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/irq.c:pirq_enable_irq",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pirq_sis_set",
        "arch/x86/pci/irq.c:pirq_sis_get",
        "arch/x86/pci/irq.c:pirq_piix_get",
        "arch/x86/pci/irq.c:write_config_nybble",
        "arch/x86/pci/irq.c:read_config_nybble"
      ],
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
  "name": "pci_read_config_byte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579058989,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:947",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583686446,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:947",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_read_irq",
        "drivers/pci/probe.c:pci_read_irq",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583701627,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:947",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/pci.c:__pci_find_next_ht_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583779171,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:947",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ht_check_msi_mapping",
        "drivers/pci/quirks.c:ht_enable_msi_mapping",
        "drivers/pci/quirks.c:msi_ht_cap_enabled",
        "drivers/pci/quirks.c:quirk_unhide_mch_dev6",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap",
        "drivers/pci/quirks.c:quirk_jmicron_ata",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_sis_96x_smbus",
        "drivers/pci/quirks.c:quirk_ide_samemode",
        "drivers/pci/quirks.c:quirk_svwks_csb5ide",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_mediagx_master",
        "drivers/pci/quirks.c:quirk_via_vlink",
        "drivers/pci/quirks.c:quirk_via_acpi",
        "drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583818763,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:947",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583848258,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:947",
      "file": "drivers/pci/iov.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_iov_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584034388,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:947",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584343152,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:947",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:map_capability"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584649176,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:947",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584734981,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:947",
      "file": "drivers/char/agp/isoch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/isoch.c:agp_3_5_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584743546,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:947",
      "file": "drivers/char/agp/intel-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_820_cleanup",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_815_fetch_size",
        "drivers/char/agp/intel-agp.c:intel_8xx_fetch_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584753242,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:947",
      "file": "drivers/char/agp/via-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/via-agp.c:via_fetch_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585472989,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:947",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:pci_test_config_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585562554,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:947",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585587785,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:947",
      "file": "drivers/ata/ata_piix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585592839,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:947",
      "file": "drivers/ata/pata_sis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_66_cable_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585970942,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:947",
      "file": "drivers/usb/host/ehci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586120909,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:947",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595742325,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:947",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:hwmon_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586744070,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:947",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_pcifront_enable_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586748294,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:947",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_fixup_i450gx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586755142,
      "name": "pci_read_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:947",
      "file": "arch/x86/pci/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/irq.c:pirq_enable_irq",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pirq_sis_set",
        "arch/x86/pci/irq.c:pirq_sis_get",
        "arch/x86/pci/irq.c:pirq_piix_get",
        "arch/x86/pci/irq.c:write_config_nybble",
        "arch/x86/pci/irq.c:read_config_nybble"
      ],
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int pci_read_config_byte(const struct pci_dev * dev, int where, u8 * val)
```

```json
{
  "name": "pci_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583711952,
      "name": "pci_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:903",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_read_irq",
        "drivers/pci/probe.c:pci_read_irq",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/pci.c:__pci_find_next_ht_cap",
        "drivers/pci/pci-sysfs.c:subordinate_bus_number_show",
        "drivers/pci/pci-sysfs.c:secondary_bus_number_show",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ht_check_msi_mapping",
        "drivers/pci/quirks.c:ht_enable_msi_mapping",
        "drivers/pci/quirks.c:msi_ht_cap_enabled",
        "drivers/pci/quirks.c:quirk_unhide_mch_dev6",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_sis_96x_smbus",
        "drivers/pci/quirks.c:quirk_ide_samemode",
        "drivers/pci/quirks.c:quirk_svwks_csb5ide",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_mediagx_master",
        "drivers/pci/quirks.c:quirk_via_vlink",
        "drivers/pci/quirks.c:quirk_via_acpi",
        "drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:map_capability",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_820_cleanup",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_815_fetch_size",
        "drivers/char/agp/intel-agp.c:intel_8xx_fetch_size",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/char/agp/via-agp.c:via_fetch_size",
        "drivers/ata/libata-core.c:pci_test_config_bits",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_66_cable_detect",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_clear",
        "arch/x86/pci/xen.c:xen_pcifront_enable_irq",
        "arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_fixup_i450gx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/irq.c:pirq_enable_irq",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pirq_sis_set",
        "arch/x86/pci/irq.c:pirq_sis_get",
        "arch/x86/pci/irq.c:pirq_piix_get",
        "arch/x86/pci/irq.c:write_config_nybble",
        "arch/x86/pci/irq.c:read_config_nybble"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583711952,
      "name": "pci_read_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int pci_read_config_byte(const struct pci_dev * dev, int where, u8 * val)
```

```json
{
  "name": "pci_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583969360,
      "name": "pci_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:903",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_read_irq",
        "drivers/pci/probe.c:pci_read_irq",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/pci.c:__pci_find_next_ht_cap",
        "drivers/pci/pci-sysfs.c:subordinate_bus_number_show",
        "drivers/pci/pci-sysfs.c:secondary_bus_number_show",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ht_check_msi_mapping",
        "drivers/pci/quirks.c:ht_enable_msi_mapping",
        "drivers/pci/quirks.c:msi_ht_cap_enabled",
        "drivers/pci/quirks.c:quirk_unhide_mch_dev6",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_sis_96x_smbus",
        "drivers/pci/quirks.c:quirk_ide_samemode",
        "drivers/pci/quirks.c:quirk_svwks_csb5ide",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_mediagx_master",
        "drivers/pci/quirks.c:quirk_via_vlink",
        "drivers/pci/quirks.c:quirk_via_acpi",
        "drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:map_capability",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_820_cleanup",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_815_fetch_size",
        "drivers/char/agp/intel-agp.c:intel_8xx_fetch_size",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/char/agp/via-agp.c:via_fetch_size",
        "drivers/ata/libata-core.c:pci_test_config_bits",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_66_cable_detect",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_clear",
        "arch/x86/pci/xen.c:xen_pcifront_enable_irq",
        "arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_fixup_i450gx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/irq.c:pirq_enable_irq",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pirq_sis_set",
        "arch/x86/pci/irq.c:pirq_sis_get",
        "arch/x86/pci/irq.c:pirq_piix_get",
        "arch/x86/pci/irq.c:write_config_nybble",
        "arch/x86/pci/irq.c:read_config_nybble"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583969360,
      "name": "pci_read_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int pci_read_config_byte(const struct pci_dev * dev, int where, u8 * val)
```

```json
{
  "name": "pci_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584165360,
      "name": "pci_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:536",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/pci.c:__pci_find_next_ht_cap",
        "drivers/pci/pci-sysfs.c:subordinate_bus_number_show",
        "drivers/pci/pci-sysfs.c:secondary_bus_number_show",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ht_check_msi_mapping",
        "drivers/pci/quirks.c:ht_enable_msi_mapping",
        "drivers/pci/quirks.c:msi_ht_cap_enabled",
        "drivers/pci/quirks.c:quirk_unhide_mch_dev6",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_sis_96x_smbus",
        "drivers/pci/quirks.c:quirk_ide_samemode",
        "drivers/pci/quirks.c:quirk_svwks_csb5ide",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_mediagx_master",
        "drivers/pci/quirks.c:quirk_via_vlink",
        "drivers/pci/quirks.c:quirk_via_acpi",
        "drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:map_capability",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_820_cleanup",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_815_fetch_size",
        "drivers/char/agp/intel-agp.c:intel_8xx_fetch_size",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/char/agp/via-agp.c:via_fetch_size",
        "drivers/ata/libata-core.c:pci_test_config_bits",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_66_cable_detect",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_clear",
        "arch/x86/pci/xen.c:xen_pcifront_enable_irq",
        "arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_fixup_i450gx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/irq.c:pirq_enable_irq",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pirq_sis_set",
        "arch/x86/pci/irq.c:pirq_sis_get",
        "arch/x86/pci/irq.c:pirq_piix_get",
        "arch/x86/pci/irq.c:write_config_nybble",
        "arch/x86/pci/irq.c:read_config_nybble"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584165360,
      "name": "pci_read_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int pci_read_config_byte(const struct pci_dev * dev, int where, u8 * val)
```

```json
{
  "name": "pci_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584253520,
      "name": "pci_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:536",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/pci.c:__pci_find_next_ht_cap",
        "drivers/pci/pci-sysfs.c:subordinate_bus_number_show",
        "drivers/pci/pci-sysfs.c:secondary_bus_number_show",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ht_check_msi_mapping",
        "drivers/pci/quirks.c:ht_enable_msi_mapping",
        "drivers/pci/quirks.c:msi_ht_cap_enabled",
        "drivers/pci/quirks.c:quirk_unhide_mch_dev6",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_sis_96x_smbus",
        "drivers/pci/quirks.c:quirk_ide_samemode",
        "drivers/pci/quirks.c:quirk_svwks_csb5ide",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_mediagx_master",
        "drivers/pci/quirks.c:quirk_via_vlink",
        "drivers/pci/quirks.c:quirk_via_acpi",
        "drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:map_capability",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_820_cleanup",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_815_fetch_size",
        "drivers/char/agp/intel-agp.c:intel_8xx_fetch_size",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/char/agp/via-agp.c:via_fetch_size",
        "drivers/ata/libata-core.c:pci_test_config_bits",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_66_cable_detect",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_clear",
        "arch/x86/pci/xen.c:xen_pcifront_enable_irq",
        "arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_fixup_i450gx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/irq.c:pirq_enable_irq",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pirq_sis_set",
        "arch/x86/pci/irq.c:pirq_sis_get",
        "arch/x86/pci/irq.c:pirq_piix_get",
        "arch/x86/pci/irq.c:write_config_nybble",
        "arch/x86/pci/irq.c:read_config_nybble"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584253520,
      "name": "pci_read_config_byte",
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
int pci_read_config_byte(const struct pci_dev * dev, int where, u8 * val)
```

```json
{
  "name": "pci_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584446672,
      "name": "pci_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:536",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/pci.c:__pci_find_next_ht_cap",
        "drivers/pci/pci-sysfs.c:subordinate_bus_number_show",
        "drivers/pci/pci-sysfs.c:secondary_bus_number_show",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/quirks.c:quirk_nvidia_hda",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ht_check_msi_mapping",
        "drivers/pci/quirks.c:ht_enable_msi_mapping",
        "drivers/pci/quirks.c:msi_ht_cap_enabled",
        "drivers/pci/quirks.c:quirk_unhide_mch_dev6",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_sis_96x_smbus",
        "drivers/pci/quirks.c:quirk_ide_samemode",
        "drivers/pci/quirks.c:quirk_svwks_csb5ide",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_mediagx_master",
        "drivers/pci/quirks.c:quirk_via_vlink",
        "drivers/pci/quirks.c:quirk_via_acpi",
        "drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:map_capability",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_820_cleanup",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_815_fetch_size",
        "drivers/char/agp/intel-agp.c:intel_8xx_fetch_size",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/char/agp/via-agp.c:via_fetch_size",
        "drivers/ata/libata-core.c:pci_test_config_bits",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_66_cable_detect",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_clear",
        "arch/x86/pci/xen.c:xen_pcifront_enable_irq",
        "arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_fixup_i450gx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/irq.c:pirq_enable_irq",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pirq_sis_set",
        "arch/x86/pci/irq.c:pirq_sis_get",
        "arch/x86/pci/irq.c:pirq_piix_get",
        "arch/x86/pci/irq.c:write_config_nybble",
        "arch/x86/pci/irq.c:read_config_nybble"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584446672,
      "name": "pci_read_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int pci_read_config_byte(const struct pci_dev * dev, int where, u8 * val)
```

```json
{
  "name": "pci_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584583424,
      "name": "pci_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:527",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/pci.c:__pci_find_next_ht_cap",
        "drivers/pci/pci-sysfs.c:subordinate_bus_number_show",
        "drivers/pci/pci-sysfs.c:secondary_bus_number_show",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/quirks.c:quirk_nvidia_hda",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ht_check_msi_mapping",
        "drivers/pci/quirks.c:ht_enable_msi_mapping",
        "drivers/pci/quirks.c:msi_ht_cap_enabled",
        "drivers/pci/quirks.c:quirk_unhide_mch_dev6",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_sis_96x_smbus",
        "drivers/pci/quirks.c:quirk_ide_samemode",
        "drivers/pci/quirks.c:quirk_svwks_csb5ide",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_mediagx_master",
        "drivers/pci/quirks.c:quirk_via_vlink",
        "drivers/pci/quirks.c:quirk_via_acpi",
        "drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:map_capability",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_820_cleanup",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_815_fetch_size",
        "drivers/char/agp/intel-agp.c:intel_8xx_fetch_size",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/char/agp/via-agp.c:via_fetch_size",
        "drivers/ata/libata-core.c:pci_test_config_bits",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_66_cable_detect",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_clear",
        "arch/x86/pci/xen.c:xen_pcifront_enable_irq",
        "arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_fixup_i450gx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/irq.c:pirq_enable_irq",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pirq_sis_set",
        "arch/x86/pci/irq.c:pirq_sis_get",
        "arch/x86/pci/irq.c:pirq_piix_get",
        "arch/x86/pci/irq.c:write_config_nybble",
        "arch/x86/pci/irq.c:read_config_nybble"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584583424,
      "name": "pci_read_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int pci_read_config_byte(const struct pci_dev * dev, int where, u8 * val)
```

```json
{
  "name": "pci_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585259280,
      "name": "pci_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:523",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_ixp4x0_rev",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_read_bridge_io",
        "drivers/pci/probe.c:pci_read_bridge_io",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/pci.c:__pci_find_next_ht_cap",
        "drivers/pci/pci-sysfs.c:subordinate_bus_number_show",
        "drivers/pci/pci-sysfs.c:secondary_bus_number_show",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/quirks.c:quirk_nvidia_hda",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ht_check_msi_mapping",
        "drivers/pci/quirks.c:ht_enable_msi_mapping",
        "drivers/pci/quirks.c:msi_ht_cap_enabled",
        "drivers/pci/quirks.c:quirk_unhide_mch_dev6",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_sis_96x_smbus",
        "drivers/pci/quirks.c:quirk_ide_samemode",
        "drivers/pci/quirks.c:quirk_svwks_csb5ide",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_mediagx_master",
        "drivers/pci/quirks.c:quirk_via_vlink",
        "drivers/pci/quirks.c:quirk_via_acpi",
        "drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert",
        "drivers/pci/quirks.c:ich6_lpc_acpi_gpio",
        "drivers/pci/quirks.c:ich6_lpc_acpi_gpio",
        "drivers/pci/quirks.c:quirk_ich4_lpc_acpi",
        "drivers/pci/quirks.c:quirk_ich4_lpc_acpi",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:map_capability",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_820_cleanup",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_815_fetch_size",
        "drivers/char/agp/intel-agp.c:intel_8xx_fetch_size",
        "drivers/char/agp/via-agp.c:check_via_agp3",
        "drivers/char/agp/via-agp.c:via_fetch_size",
        "drivers/ata/libata-core.c:pci_test_config_bits",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/ata_piix.c:piix_init_sata_map",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_66_cable_detect",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_get_irq_count",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/hwmon/hwmon.c:hwmon_pci_quirks",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "arch/x86/pci/xen.c:xen_pcifront_enable_irq",
        "arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_fixup_i450gx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/irq.c:pirq_enable_irq",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pirq_amd756_get",
        "arch/x86/pci/irq.c:pirq_vlsi_get",
        "arch/x86/pci/irq.c:pirq_sis_set",
        "arch/x86/pci/irq.c:pirq_sis_get",
        "arch/x86/pci/irq.c:pirq_cyrix_get",
        "arch/x86/pci/irq.c:pirq_opti_get",
        "arch/x86/pci/irq.c:pirq_ite_get",
        "arch/x86/pci/irq.c:pirq_via586_get",
        "arch/x86/pci/irq.c:pirq_via_get",
        "arch/x86/pci/irq.c:pirq_via_get",
        "arch/x86/pci/irq.c:pirq_piix_get",
        "arch/x86/pci/irq.c:pirq_ali_get",
        "arch/x86/pci/irq.c:write_config_nybble"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585259280,
      "name": "pci_read_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int pci_read_config_byte(const struct pci_dev * dev, int where, u8 * val)
```

```json
{
  "name": "pci_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585417008,
      "name": "pci_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:523",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_ixp4x0_rev",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_read_bridge_io",
        "drivers/pci/probe.c:pci_read_bridge_io",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/pci.c:__pci_find_next_ht_cap",
        "drivers/pci/pci-sysfs.c:subordinate_bus_number_show",
        "drivers/pci/pci-sysfs.c:secondary_bus_number_show",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/quirks.c:quirk_nvidia_hda",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ht_check_msi_mapping",
        "drivers/pci/quirks.c:ht_enable_msi_mapping",
        "drivers/pci/quirks.c:msi_ht_cap_enabled",
        "drivers/pci/quirks.c:quirk_unhide_mch_dev6",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_sis_96x_smbus",
        "drivers/pci/quirks.c:quirk_ide_samemode",
        "drivers/pci/quirks.c:quirk_svwks_csb5ide",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_mediagx_master",
        "drivers/pci/quirks.c:quirk_via_vlink",
        "drivers/pci/quirks.c:quirk_via_acpi",
        "drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert",
        "drivers/pci/quirks.c:ich6_lpc_acpi_gpio",
        "drivers/pci/quirks.c:ich6_lpc_acpi_gpio",
        "drivers/pci/quirks.c:quirk_ich4_lpc_acpi",
        "drivers/pci/quirks.c:quirk_ich4_lpc_acpi",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap",
        "drivers/virtio/virtio_pci_modern.c:map_capability",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_820_cleanup",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_815_fetch_size",
        "drivers/char/agp/intel-agp.c:intel_8xx_fetch_size",
        "drivers/char/agp/via-agp.c:check_via_agp3",
        "drivers/char/agp/via-agp.c:via_fetch_size",
        "drivers/ata/libata-core.c:pci_test_config_bits",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/ata_piix.c:piix_init_sata_map",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_66_cable_detect",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_get_irq_count",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/hwmon/hwmon.c:hwmon_pci_quirks",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "arch/x86/pci/xen.c:xen_pcifront_enable_irq",
        "arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_fixup_i450gx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/irq.c:pirq_enable_irq",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pirq_amd756_get",
        "arch/x86/pci/irq.c:pirq_vlsi_get",
        "arch/x86/pci/irq.c:pirq_sis_set",
        "arch/x86/pci/irq.c:pirq_sis_get",
        "arch/x86/pci/irq.c:pirq_cyrix_get",
        "arch/x86/pci/irq.c:pirq_opti_get",
        "arch/x86/pci/irq.c:pirq_ite_get",
        "arch/x86/pci/irq.c:pirq_via586_get",
        "arch/x86/pci/irq.c:pirq_via_get",
        "arch/x86/pci/irq.c:pirq_via_get",
        "arch/x86/pci/irq.c:pirq_piix_get",
        "arch/x86/pci/irq.c:pirq_ali_get",
        "arch/x86/pci/irq.c:write_config_nybble"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585417008,
      "name": "pci_read_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int pci_read_config_byte(const struct pci_dev * dev, int where, u8 * val)
```

```json
{
  "name": "pci_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585297584,
      "name": "pci_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:523",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id",
        "arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/pci.c:__pci_find_next_ht_cap",
        "drivers/pci/pci-sysfs.c:subordinate_bus_number_show",
        "drivers/pci/pci-sysfs.c:secondary_bus_number_show",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/quirks.c:quirk_nvidia_hda",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ht_check_msi_mapping",
        "drivers/pci/quirks.c:ht_enable_msi_mapping",
        "drivers/pci/quirks.c:msi_ht_cap_enabled",
        "drivers/pci/quirks.c:quirk_unhide_mch_dev6",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_sis_96x_smbus",
        "drivers/pci/quirks.c:quirk_ide_samemode",
        "drivers/pci/quirks.c:quirk_svwks_csb5ide",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_mediagx_master",
        "drivers/pci/quirks.c:quirk_via_vlink",
        "drivers/pci/quirks.c:quirk_via_acpi",
        "drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert",
        "drivers/pci/quirks.c:ich6_lpc_acpi_gpio",
        "drivers/pci/quirks.c:ich6_lpc_acpi_gpio",
        "drivers/pci/quirks.c:quirk_ich4_lpc_acpi",
        "drivers/pci/quirks.c:quirk_ich4_lpc_acpi",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:vp_get_shm_region",
        "drivers/virtio/virtio_pci_modern.c:vp_get_shm_region",
        "drivers/virtio/virtio_pci_modern.c:vp_get_shm_region",
        "drivers/virtio/virtio_pci_modern.c:vp_get_shm_region",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_820_cleanup",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_815_fetch_size",
        "drivers/char/agp/intel-agp.c:intel_8xx_fetch_size",
        "drivers/char/agp/via-agp.c:check_via_agp3",
        "drivers/char/agp/via-agp.c:via_fetch_size",
        "drivers/ata/libata-core.c:pci_test_config_bits",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/ata_piix.c:piix_init_sata_map",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_66_cable_detect",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_get_irq_count",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "arch/x86/pci/xen.c:xen_pcifront_enable_irq",
        "arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_fixup_i450gx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/irq.c:pirq_enable_irq",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pirq_amd756_get",
        "arch/x86/pci/irq.c:pirq_vlsi_get",
        "arch/x86/pci/irq.c:pirq_sis_set",
        "arch/x86/pci/irq.c:pirq_sis_get",
        "arch/x86/pci/irq.c:pirq_cyrix_get",
        "arch/x86/pci/irq.c:pirq_opti_get",
        "arch/x86/pci/irq.c:pirq_ite_get",
        "arch/x86/pci/irq.c:pirq_via586_get",
        "arch/x86/pci/irq.c:pirq_via_get",
        "arch/x86/pci/irq.c:pirq_via_get",
        "arch/x86/pci/irq.c:pirq_piix_get",
        "arch/x86/pci/irq.c:pirq_ali_get",
        "arch/x86/pci/irq.c:write_config_nybble"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585297584,
      "name": "pci_read_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int pci_read_config_byte(const struct pci_dev * dev, int where, u8 * val)
```

```json
{
  "name": "pci_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585754368,
      "name": "pci_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:523",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id",
        "arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/pci.c:__pci_find_next_ht_cap",
        "drivers/pci/pci-sysfs.c:subordinate_bus_number_show",
        "drivers/pci/pci-sysfs.c:secondary_bus_number_show",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/quirks.c:quirk_nvidia_hda",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ht_check_msi_mapping",
        "drivers/pci/quirks.c:ht_enable_msi_mapping",
        "drivers/pci/quirks.c:msi_ht_cap_enabled",
        "drivers/pci/quirks.c:quirk_unhide_mch_dev6",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_sis_96x_smbus",
        "drivers/pci/quirks.c:quirk_ide_samemode",
        "drivers/pci/quirks.c:quirk_svwks_csb5ide",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_mediagx_master",
        "drivers/pci/quirks.c:quirk_via_vlink",
        "drivers/pci/quirks.c:quirk_via_acpi",
        "drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert",
        "drivers/pci/quirks.c:ich6_lpc_acpi_gpio",
        "drivers/pci/quirks.c:ich6_lpc_acpi_gpio",
        "drivers/pci/quirks.c:quirk_ich4_lpc_acpi",
        "drivers/pci/quirks.c:quirk_ich4_lpc_acpi",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:vp_get_shm_region",
        "drivers/virtio/virtio_pci_modern.c:vp_get_shm_region",
        "drivers/virtio/virtio_pci_modern.c:vp_get_shm_region",
        "drivers/virtio/virtio_pci_modern.c:vp_get_shm_region",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_820_cleanup",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_815_fetch_size",
        "drivers/char/agp/intel-agp.c:intel_8xx_fetch_size",
        "drivers/char/agp/via-agp.c:check_via_agp3",
        "drivers/char/agp/via-agp.c:via_fetch_size",
        "drivers/ata/libata-core.c:pci_test_config_bits",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/ata_piix.c:piix_init_sata_map",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_66_cable_detect",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_get_irq_count",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "arch/x86/pci/xen.c:xen_pcifront_enable_irq",
        "arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_fixup_i450gx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/irq.c:pirq_enable_irq",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pirq_amd756_get",
        "arch/x86/pci/irq.c:pirq_vlsi_get",
        "arch/x86/pci/irq.c:pirq_sis_set",
        "arch/x86/pci/irq.c:pirq_sis_get",
        "arch/x86/pci/irq.c:pirq_cyrix_get",
        "arch/x86/pci/irq.c:pirq_opti_get",
        "arch/x86/pci/irq.c:pirq_ite_get",
        "arch/x86/pci/irq.c:pirq_via586_get",
        "arch/x86/pci/irq.c:pirq_via_get",
        "arch/x86/pci/irq.c:pirq_via_get",
        "arch/x86/pci/irq.c:pirq_ib_get",
        "arch/x86/pci/irq.c:pirq_piix_get",
        "arch/x86/pci/irq.c:pirq_ali_get",
        "arch/x86/pci/irq.c:write_config_nybble"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585754368,
      "name": "pci_read_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int pci_read_config_byte(const struct pci_dev * dev, int where, u8 * val)
```

```json
{
  "name": "pci_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586938096,
      "name": "pci_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:528",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id",
        "arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:quirk_intel_irqbalance",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_read_irq",
        "drivers/pci/probe.c:pci_read_irq",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/pci.c:do_pci_enable_device",
        "drivers/pci/pci.c:__pci_find_next_ht_cap",
        "drivers/pci/pci-sysfs.c:subordinate_bus_number_show",
        "drivers/pci/pci-sysfs.c:secondary_bus_number_show",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/quirks.c:quirk_nvidia_hda",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ht_check_msi_mapping",
        "drivers/pci/quirks.c:ht_enable_msi_mapping",
        "drivers/pci/quirks.c:msi_ht_cap_enabled",
        "drivers/pci/quirks.c:quirk_unhide_mch_dev6",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap",
        "drivers/pci/quirks.c:quirk_jmicron_ata",
        "drivers/pci/quirks.c:asus_hides_ac97_lpc",
        "drivers/pci/quirks.c:asus_hides_ac97_lpc",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_sis_96x_smbus",
        "drivers/pci/quirks.c:quirk_ide_samemode",
        "drivers/pci/quirks.c:quirk_svwks_csb5ide",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_mediagx_master",
        "drivers/pci/quirks.c:quirk_via_vlink",
        "drivers/pci/quirks.c:quirk_via_acpi",
        "drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert",
        "drivers/pci/quirks.c:ich6_lpc_acpi_gpio",
        "drivers/pci/quirks.c:ich6_lpc_acpi_gpio",
        "drivers/pci/quirks.c:quirk_ich4_lpc_acpi",
        "drivers/pci/quirks.c:quirk_ich4_lpc_acpi",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_capability",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_820_cleanup",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_815_fetch_size",
        "drivers/char/agp/intel-agp.c:intel_8xx_fetch_size",
        "drivers/char/agp/via-agp.c:check_via_agp3",
        "drivers/char/agp/via-agp.c:via_fetch_size",
        "drivers/ata/libata-core.c:pci_test_config_bits",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/ata_piix.c:piix_init_sata_map",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_66_cable_detect",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_get_irq_count",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ext_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ext_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ext_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ext_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "arch/x86/pci/xen.c:xen_pcifront_enable_irq",
        "arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530",
        "arch/x86/pci/fixup.c:pci_fixup_msi_k8t_onboard_sound",
        "arch/x86/pci/fixup.c:pci_fixup_msi_k8t_onboard_sound",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_fixup_i450gx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/irq.c:pirq_enable_irq",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pirq_amd756_get",
        "arch/x86/pci/irq.c:pirq_vlsi_get",
        "arch/x86/pci/irq.c:pirq_sis503_set",
        "arch/x86/pci/irq.c:pirq_sis503_get",
        "arch/x86/pci/irq.c:pirq_sis497_set",
        "arch/x86/pci/irq.c:pirq_sis497_get",
        "arch/x86/pci/irq.c:pirq_cyrix_get",
        "arch/x86/pci/irq.c:pirq_opti_get",
        "arch/x86/pci/irq.c:pirq_ite_get",
        "arch/x86/pci/irq.c:pirq_via586_get",
        "arch/x86/pci/irq.c:pirq_via_get",
        "arch/x86/pci/irq.c:pirq_via_get",
        "arch/x86/pci/irq.c:pirq_ib_get",
        "arch/x86/pci/irq.c:pirq_piix_get",
        "arch/x86/pci/irq.c:pirq_ali_get",
        "arch/x86/pci/irq.c:write_config_nybble"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586938096,
      "name": "pci_read_config_byte",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int pci_read_config_byte(const struct pci_dev * dev, int where, u8 * val)
```

```json
{
  "name": "pci_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588095344,
      "name": "pci_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:534",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id",
        "arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:quirk_intel_irqbalance",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_read_irq",
        "drivers/pci/probe.c:pci_read_irq",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/pci.c:do_pci_enable_device",
        "drivers/pci/pci.c:__pci_find_next_ht_cap",
        "drivers/pci/pci-sysfs.c:subordinate_bus_number_show",
        "drivers/pci/pci-sysfs.c:secondary_bus_number_show",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/quirks.c:quirk_nvidia_hda",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ht_check_msi_mapping",
        "drivers/pci/quirks.c:ht_enable_msi_mapping",
        "drivers/pci/quirks.c:msi_ht_cap_enabled",
        "drivers/pci/quirks.c:quirk_unhide_mch_dev6",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap",
        "drivers/pci/quirks.c:quirk_jmicron_ata",
        "drivers/pci/quirks.c:asus_hides_ac97_lpc",
        "drivers/pci/quirks.c:asus_hides_ac97_lpc",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_sis_96x_smbus",
        "drivers/pci/quirks.c:quirk_ide_samemode",
        "drivers/pci/quirks.c:quirk_svwks_csb5ide",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_mediagx_master",
        "drivers/pci/quirks.c:quirk_via_vlink",
        "drivers/pci/quirks.c:quirk_via_acpi",
        "drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert",
        "drivers/pci/quirks.c:ich6_lpc_acpi_gpio",
        "drivers/pci/quirks.c:ich6_lpc_acpi_gpio",
        "drivers/pci/quirks.c:quirk_ich4_lpc_acpi",
        "drivers/pci/quirks.c:quirk_ich4_lpc_acpi",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_capability",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_820_cleanup",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_815_fetch_size",
        "drivers/char/agp/intel-agp.c:intel_8xx_fetch_size",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/char/agp/via-agp.c:via_fetch_size",
        "drivers/ata/libata-core.c:pci_test_config_bits",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/ata_piix.c:piix_init_sata_map",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_66_cable_detect",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "arch/x86/pci/xen.c:xen_pcifront_enable_irq",
        "arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530",
        "arch/x86/pci/fixup.c:pci_fixup_msi_k8t_onboard_sound",
        "arch/x86/pci/fixup.c:pci_fixup_msi_k8t_onboard_sound",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_fixup_i450gx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/irq.c:pirq_enable_irq",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pirq_amd756_get",
        "arch/x86/pci/irq.c:pirq_sis503_set",
        "arch/x86/pci/irq.c:pirq_sis503_get",
        "arch/x86/pci/irq.c:pirq_sis497_set",
        "arch/x86/pci/irq.c:pirq_sis497_get",
        "arch/x86/pci/irq.c:pirq_cyrix_get",
        "arch/x86/pci/irq.c:pirq_opti_get",
        "arch/x86/pci/irq.c:pirq_ite_get",
        "arch/x86/pci/irq.c:pirq_via586_get",
        "arch/x86/pci/irq.c:pirq_via_get",
        "arch/x86/pci/irq.c:pirq_via_get",
        "arch/x86/pci/irq.c:pirq_ib_get",
        "arch/x86/pci/irq.c:pirq_piix_get",
        "arch/x86/pci/irq.c:pirq_ali_get",
        "arch/x86/pci/irq.c:write_config_nybble"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588095344,
      "name": "pci_read_config_byte",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int pci_read_config_byte(const struct pci_dev * dev, int where, u8 * val)
```

```json
{
  "name": "pci_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588369776,
      "name": "pci_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:548",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id",
        "arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:quirk_intel_irqbalance",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_read_irq",
        "drivers/pci/probe.c:pci_read_irq",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/pci.c:do_pci_enable_device",
        "drivers/pci/pci.c:__pci_find_next_ht_cap",
        "drivers/pci/pci-sysfs.c:subordinate_bus_number_show",
        "drivers/pci/pci-sysfs.c:secondary_bus_number_show",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/quirks.c:quirk_nvidia_hda",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ht_check_msi_mapping",
        "drivers/pci/quirks.c:ht_enable_msi_mapping",
        "drivers/pci/quirks.c:msi_ht_cap_enabled",
        "drivers/pci/quirks.c:quirk_unhide_mch_dev6",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap",
        "drivers/pci/quirks.c:quirk_jmicron_ata",
        "drivers/pci/quirks.c:asus_hides_ac97_lpc",
        "drivers/pci/quirks.c:asus_hides_ac97_lpc",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_sis_96x_smbus",
        "drivers/pci/quirks.c:quirk_ide_samemode",
        "drivers/pci/quirks.c:quirk_svwks_csb5ide",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_mediagx_master",
        "drivers/pci/quirks.c:quirk_via_vlink",
        "drivers/pci/quirks.c:quirk_via_acpi",
        "drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert",
        "drivers/pci/quirks.c:ich6_lpc_acpi_gpio",
        "drivers/pci/quirks.c:ich6_lpc_acpi_gpio",
        "drivers/pci/quirks.c:quirk_ich4_lpc_acpi",
        "drivers/pci/quirks.c:quirk_ich4_lpc_acpi",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_capability",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_820_cleanup",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_815_fetch_size",
        "drivers/char/agp/intel-agp.c:intel_8xx_fetch_size",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/char/agp/via-agp.c:via_fetch_size",
        "drivers/ata/libata-core.c:pci_test_config_bits",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/ata_piix.c:piix_init_sata_map",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_66_cable_detect",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "arch/x86/pci/xen.c:xen_pcifront_enable_irq",
        "arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530",
        "arch/x86/pci/fixup.c:pci_fixup_msi_k8t_onboard_sound",
        "arch/x86/pci/fixup.c:pci_fixup_msi_k8t_onboard_sound",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_fixup_i450gx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/irq.c:pirq_enable_irq",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pirq_amd756_get",
        "arch/x86/pci/irq.c:pirq_sis503_set",
        "arch/x86/pci/irq.c:pirq_sis503_get",
        "arch/x86/pci/irq.c:pirq_sis497_set",
        "arch/x86/pci/irq.c:pirq_sis497_get",
        "arch/x86/pci/irq.c:pirq_cyrix_get",
        "arch/x86/pci/irq.c:pirq_opti_get",
        "arch/x86/pci/irq.c:pirq_ite_get",
        "arch/x86/pci/irq.c:pirq_via586_get",
        "arch/x86/pci/irq.c:pirq_via_get",
        "arch/x86/pci/irq.c:pirq_via_get",
        "arch/x86/pci/irq.c:pirq_ib_get",
        "arch/x86/pci/irq.c:pirq_piix_get",
        "arch/x86/pci/irq.c:pirq_ali_get",
        "arch/x86/pci/irq.c:write_config_nybble"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588369776,
      "name": "pci_read_config_byte",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int pci_read_config_byte(const struct pci_dev * dev, int where, u8 * val)
```

```json
{
  "name": "pci_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588664544,
      "name": "pci_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:546",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id",
        "arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:quirk_intel_irqbalance",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_read_irq",
        "drivers/pci/probe.c:pci_read_irq",
        "drivers/pci/probe.c:pci_read_bridge_io",
        "drivers/pci/probe.c:pci_read_bridge_io",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/pci.c:do_pci_enable_device",
        "drivers/pci/pci.c:__pci_find_next_ht_cap",
        "drivers/pci/pci-sysfs.c:subordinate_bus_number_show",
        "drivers/pci/pci-sysfs.c:secondary_bus_number_show",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/quirks.c:quirk_nvidia_hda",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ht_check_msi_mapping",
        "drivers/pci/quirks.c:ht_enable_msi_mapping",
        "drivers/pci/quirks.c:msi_ht_cap_enabled",
        "drivers/pci/quirks.c:quirk_unhide_mch_dev6",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap",
        "drivers/pci/quirks.c:quirk_jmicron_ata",
        "drivers/pci/quirks.c:asus_hides_ac97_lpc",
        "drivers/pci/quirks.c:asus_hides_ac97_lpc",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_sis_96x_smbus",
        "drivers/pci/quirks.c:quirk_ide_samemode",
        "drivers/pci/quirks.c:quirk_svwks_csb5ide",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_mediagx_master",
        "drivers/pci/quirks.c:quirk_via_vlink",
        "drivers/pci/quirks.c:quirk_via_acpi",
        "drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert",
        "drivers/pci/quirks.c:ich6_lpc_acpi_gpio",
        "drivers/pci/quirks.c:ich6_lpc_acpi_gpio",
        "drivers/pci/quirks.c:quirk_ich4_lpc_acpi",
        "drivers/pci/quirks.c:quirk_ich4_lpc_acpi",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_capability",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_820_cleanup",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_815_fetch_size",
        "drivers/char/agp/intel-agp.c:intel_8xx_fetch_size",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/char/agp/via-agp.c:via_fetch_size",
        "drivers/ata/libata-core.c:pci_test_config_bits",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/ata_piix.c:piix_init_sata_map",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_66_cable_detect",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "arch/x86/pci/xen.c:xen_pcifront_enable_irq",
        "arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530",
        "arch/x86/pci/fixup.c:pci_fixup_msi_k8t_onboard_sound",
        "arch/x86/pci/fixup.c:pci_fixup_msi_k8t_onboard_sound",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_fixup_i450gx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/irq.c:pirq_enable_irq",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pirq_amd756_get",
        "arch/x86/pci/irq.c:pirq_sis503_set",
        "arch/x86/pci/irq.c:pirq_sis503_get",
        "arch/x86/pci/irq.c:pirq_sis497_set",
        "arch/x86/pci/irq.c:pirq_sis497_get",
        "arch/x86/pci/irq.c:pirq_cyrix_get",
        "arch/x86/pci/irq.c:pirq_opti_get",
        "arch/x86/pci/irq.c:pirq_ite_get",
        "arch/x86/pci/irq.c:pirq_via586_get",
        "arch/x86/pci/irq.c:pirq_via_get",
        "arch/x86/pci/irq.c:pirq_via_get",
        "arch/x86/pci/irq.c:pirq_ib_get",
        "arch/x86/pci/irq.c:pirq_piix_get",
        "arch/x86/pci/irq.c:pirq_ali_get",
        "arch/x86/pci/irq.c:write_config_nybble"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588664544,
      "name": "pci_read_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int pci_read_config_byte(const struct pci_dev * dev, int where, u8 * val)
```

```json
{
  "name": "pci_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496822384,
      "name": "pci_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:527",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/pci.c:__pci_find_next_ht_cap",
        "drivers/pci/pci-sysfs.c:subordinate_bus_number_show",
        "drivers/pci/pci-sysfs.c:secondary_bus_number_show",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/of.c:of_irq_parse_and_map_pci",
        "drivers/pci/quirks.c:quirk_nvidia_hda",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ht_check_msi_mapping",
        "drivers/pci/quirks.c:ht_enable_msi_mapping",
        "drivers/pci/quirks.c:msi_ht_cap_enabled",
        "drivers/pci/quirks.c:quirk_unhide_mch_dev6",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_sis_96x_smbus",
        "drivers/pci/quirks.c:quirk_ide_samemode",
        "drivers/pci/quirks.c:quirk_svwks_csb5ide",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_mediagx_master",
        "drivers/pci/quirks.c:quirk_via_vlink",
        "drivers/pci/quirks.c:quirk_via_acpi",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:map_capability",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/ata/libata-core.c:pci_test_config_bits",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496822384,
      "name": "pci_read_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int pci_read_config_byte(const struct pci_dev * dev, int where, u8 * val)
```

```json
{
  "name": "pci_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230101984,
      "name": "pci_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:527",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/pci.c:__pci_find_next_ht_cap",
        "drivers/pci/pci-sysfs.c:subordinate_bus_number_show",
        "drivers/pci/pci-sysfs.c:secondary_bus_number_show",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/of.c:of_irq_parse_and_map_pci",
        "drivers/pci/quirks.c:quirk_nvidia_hda",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ht_check_msi_mapping",
        "drivers/pci/quirks.c:ht_enable_msi_mapping",
        "drivers/pci/quirks.c:msi_ht_cap_enabled",
        "drivers/pci/quirks.c:quirk_unhide_mch_dev6",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_sis_96x_smbus",
        "drivers/pci/quirks.c:quirk_ide_samemode",
        "drivers/pci/quirks.c:quirk_svwks_csb5ide",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_mediagx_master",
        "drivers/pci/quirks.c:quirk_via_vlink",
        "drivers/pci/quirks.c:quirk_via_acpi",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:map_capability",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/ata/libata-core.c:pci_test_config_bits",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230101984,
      "name": "pci_read_config_byte",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int pci_read_config_byte(const struct pci_dev * dev, int where, u8 * val)
```

```json
{
  "name": "pci_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290890288,
      "name": "pci_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:527",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/pci-common.c:pcibios_setup_device",
        "arch/powerpc/kernel/pci-common.c:pcibios_setup_device",
        "arch/powerpc/platforms/powernv/ocxl.c:pnv_ocxl_fixup_actag",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/pci.c:__pci_find_next_ht_cap",
        "drivers/pci/pci-sysfs.c:subordinate_bus_number_show",
        "drivers/pci/pci-sysfs.c:secondary_bus_number_show",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/of.c:of_irq_parse_and_map_pci",
        "drivers/pci/quirks.c:quirk_nvidia_hda",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ht_check_msi_mapping",
        "drivers/pci/quirks.c:ht_enable_msi_mapping",
        "drivers/pci/quirks.c:msi_ht_cap_enabled",
        "drivers/pci/quirks.c:quirk_unhide_mch_dev6",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_sis_96x_smbus",
        "drivers/pci/quirks.c:quirk_ide_samemode",
        "drivers/pci/quirks.c:quirk_svwks_csb5ide",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_mediagx_master",
        "drivers/pci/quirks.c:quirk_via_vlink",
        "drivers/pci/quirks.c:quirk_via_acpi",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pci/iov.c:sriov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:map_capability",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/ata/libata-core.c:pci_test_config_bits",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_get_irq_count",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290890288,
      "name": "pci_read_config_byte",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int pci_read_config_byte(const struct pci_dev * dev, int where, u8 * val)
```

```json
{
  "name": "pci_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275528452,
      "name": "pci_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:527",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/pci.c:__pci_find_next_ht_cap",
        "drivers/pci/pci-sysfs.c:subordinate_bus_number_show",
        "drivers/pci/pci-sysfs.c:secondary_bus_number_show",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/of.c:of_irq_parse_and_map_pci",
        "drivers/pci/quirks.c:quirk_nvidia_hda",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ht_check_msi_mapping",
        "drivers/pci/quirks.c:ht_enable_msi_mapping",
        "drivers/pci/quirks.c:msi_ht_cap_enabled",
        "drivers/pci/quirks.c:quirk_unhide_mch_dev6",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_sis_96x_smbus",
        "drivers/pci/quirks.c:quirk_ide_samemode",
        "drivers/pci/quirks.c:quirk_svwks_csb5ide",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_mediagx_master",
        "drivers/pci/quirks.c:quirk_via_vlink",
        "drivers/pci/quirks.c:quirk_via_acpi",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:map_capability",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/ata/libata-core.c:pci_test_config_bits",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275528452,
      "name": "pci_read_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int pci_read_config_byte(const struct pci_dev * dev, int where, u8 * val)
```

```json
{
  "name": "pci_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584535584,
      "name": "pci_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:527",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/pci.c:__pci_find_next_ht_cap",
        "drivers/pci/pci-sysfs.c:subordinate_bus_number_show",
        "drivers/pci/pci-sysfs.c:secondary_bus_number_show",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/quirks.c:quirk_nvidia_hda",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ht_check_msi_mapping",
        "drivers/pci/quirks.c:ht_enable_msi_mapping",
        "drivers/pci/quirks.c:msi_ht_cap_enabled",
        "drivers/pci/quirks.c:quirk_unhide_mch_dev6",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_sis_96x_smbus",
        "drivers/pci/quirks.c:quirk_ide_samemode",
        "drivers/pci/quirks.c:quirk_svwks_csb5ide",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_mediagx_master",
        "drivers/pci/quirks.c:quirk_via_vlink",
        "drivers/pci/quirks.c:quirk_via_acpi",
        "drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:map_capability",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_820_cleanup",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_815_fetch_size",
        "drivers/char/agp/intel-agp.c:intel_8xx_fetch_size",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/char/agp/via-agp.c:via_fetch_size",
        "drivers/ata/libata-core.c:pci_test_config_bits",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_66_cable_detect",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_clear",
        "arch/x86/pci/xen.c:xen_pcifront_enable_irq",
        "arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_fixup_i450gx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/irq.c:pirq_enable_irq",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pirq_sis_set",
        "arch/x86/pci/irq.c:pirq_sis_get",
        "arch/x86/pci/irq.c:pirq_piix_get",
        "arch/x86/pci/irq.c:write_config_nybble",
        "arch/x86/pci/irq.c:read_config_nybble"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584535584,
      "name": "pci_read_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int pci_read_config_byte(const struct pci_dev * dev, int where, u8 * val)
```

```json
{
  "name": "pci_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584463760,
      "name": "pci_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:527",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/pci.c:__pci_find_next_ht_cap",
        "drivers/pci/pci-sysfs.c:subordinate_bus_number_show",
        "drivers/pci/pci-sysfs.c:secondary_bus_number_show",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/quirks.c:quirk_nvidia_hda",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:ht_check_msi_mapping",
        "drivers/pci/quirks.c:ht_enable_msi_mapping",
        "drivers/pci/quirks.c:msi_ht_cap_enabled",
        "drivers/pci/quirks.c:quirk_unhide_mch_dev6",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_sis_96x_smbus",
        "drivers/pci/quirks.c:quirk_ide_samemode",
        "drivers/pci/quirks.c:quirk_svwks_csb5ide",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_mediagx_master",
        "drivers/pci/quirks.c:quirk_via_vlink",
        "drivers/pci/quirks.c:quirk_via_acpi",
        "drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:map_capability",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_820_cleanup",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_815_fetch_size",
        "drivers/char/agp/intel-agp.c:intel_8xx_fetch_size",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/char/agp/via-agp.c:via_fetch_size",
        "drivers/ata/libata-core.c:pci_test_config_bits",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_66_cable_detect",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_clear",
        "arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_fixup_i450gx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/irq.c:pirq_enable_irq",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pirq_sis_set",
        "arch/x86/pci/irq.c:pirq_sis_get",
        "arch/x86/pci/irq.c:pirq_piix_get",
        "arch/x86/pci/irq.c:write_config_nybble",
        "arch/x86/pci/irq.c:read_config_nybble"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584463760,
      "name": "pci_read_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int pci_read_config_byte(const struct pci_dev * dev, int where, u8 * val)
```

```json
{
  "name": "pci_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584533584,
      "name": "pci_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:527",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/pci.c:__pci_find_next_ht_cap",
        "drivers/pci/pci-sysfs.c:subordinate_bus_number_show",
        "drivers/pci/pci-sysfs.c:secondary_bus_number_show",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/quirks.c:quirk_nvidia_hda",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ht_check_msi_mapping",
        "drivers/pci/quirks.c:ht_enable_msi_mapping",
        "drivers/pci/quirks.c:msi_ht_cap_enabled",
        "drivers/pci/quirks.c:quirk_unhide_mch_dev6",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_sis_96x_smbus",
        "drivers/pci/quirks.c:quirk_ide_samemode",
        "drivers/pci/quirks.c:quirk_svwks_csb5ide",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_mediagx_master",
        "drivers/pci/quirks.c:quirk_via_vlink",
        "drivers/pci/quirks.c:quirk_via_acpi",
        "drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:map_capability",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_820_cleanup",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_815_fetch_size",
        "drivers/char/agp/intel-agp.c:intel_8xx_fetch_size",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/char/agp/via-agp.c:via_fetch_size",
        "drivers/ata/libata-core.c:pci_test_config_bits",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_66_cable_detect",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_clear",
        "arch/x86/pci/xen.c:xen_pcifront_enable_irq",
        "arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_fixup_i450gx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/irq.c:pirq_enable_irq",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pirq_sis_set",
        "arch/x86/pci/irq.c:pirq_sis_get",
        "arch/x86/pci/irq.c:pirq_piix_get",
        "arch/x86/pci/irq.c:write_config_nybble",
        "arch/x86/pci/irq.c:read_config_nybble"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584533584,
      "name": "pci_read_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int pci_read_config_byte(const struct pci_dev * dev, int where, u8 * val)
```

```json
{
  "name": "pci_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584641360,
      "name": "pci_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:527",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/pci.c:__pci_find_next_ht_cap",
        "drivers/pci/pci-sysfs.c:subordinate_bus_number_show",
        "drivers/pci/pci-sysfs.c:secondary_bus_number_show",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/quirks.c:quirk_nvidia_hda",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:quirk_intel_ntb",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ht_check_msi_mapping",
        "drivers/pci/quirks.c:ht_enable_msi_mapping",
        "drivers/pci/quirks.c:msi_ht_cap_enabled",
        "drivers/pci/quirks.c:quirk_unhide_mch_dev6",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_sis_96x_smbus",
        "drivers/pci/quirks.c:quirk_ide_samemode",
        "drivers/pci/quirks.c:quirk_svwks_csb5ide",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_mediagx_master",
        "drivers/pci/quirks.c:quirk_via_vlink",
        "drivers/pci/quirks.c:quirk_via_acpi",
        "drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:pci_apply_final_quirks",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:map_capability",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_820_cleanup",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_815_fetch_size",
        "drivers/char/agp/intel-agp.c:intel_8xx_fetch_size",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/char/agp/via-agp.c:via_fetch_size",
        "drivers/ata/libata-core.c:pci_test_config_bits",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_66_cable_detect",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_clear",
        "arch/x86/pci/xen.c:xen_pcifront_enable_irq",
        "arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_fixup_i450gx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/irq.c:pirq_enable_irq",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pirq_sis_set",
        "arch/x86/pci/irq.c:pirq_sis_get",
        "arch/x86/pci/irq.c:pirq_piix_get",
        "arch/x86/pci/irq.c:write_config_nybble",
        "arch/x86/pci/irq.c:read_config_nybble"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584641360,
      "name": "pci_read_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int pci_read_config_byte(const struct pci_dev * dev, int where, u8 * val)
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
