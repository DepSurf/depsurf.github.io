# Function: <code>pci_bus_read_config_byte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int pci_bus_read_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 * value)
```

```json
{
  "name": "pci_bus_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583226464,
      "name": "pci_bus_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:56",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "drivers/pci/probe.c:pci_read_irq",
        "drivers/pci/probe.c:pci_read_irq",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl",
        "drivers/pci/pci.c:__pci_find_next_ht_cap",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pcibios_set_master",
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
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/virtio/virtio_pci_modern.c:map_capability",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/intel-agp.c:intel_8xx_fetch_size",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_820_cleanup",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_815_fetch_size",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/via-agp.c:via_fetch_size",
        "drivers/ata/libata-core.c:pci_test_config_bits",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/pata_sis.c:sis_66_cable_detect",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "arch/x86/pci/xen.c:xen_pcifront_enable_irq",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450nx",
        "arch/x86/pci/fixup.c:pci_fixup_i450gx",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530",
        "arch/x86/pci/irq.c:read_config_nybble",
        "arch/x86/pci/irq.c:pirq_sis_get",
        "arch/x86/pci/irq.c:pirq_piix_get",
        "arch/x86/pci/irq.c:write_config_nybble",
        "arch/x86/pci/irq.c:pirq_sis_set",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pirq_enable_irq",
        "arch/x86/pci/irq.c:pcibios_fixup_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583226464,
      "name": "pci_bus_read_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int pci_bus_read_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 * value)
```

```json
{
  "name": "pci_bus_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583534576,
      "name": "pci_bus_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:56",
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
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:__pci_find_next_ht_cap",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl",
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
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
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
      "addr": 18446744071583534576,
      "name": "pci_bus_read_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int pci_bus_read_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 * value)
```

```json
{
  "name": "pci_bus_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583670784,
      "name": "pci_bus_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:56",
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
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:__pci_find_next_ht_cap",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl",
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
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
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
      "addr": 18446744071583670784,
      "name": "pci_bus_read_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int pci_bus_read_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 * value)
```

```json
{
  "name": "pci_bus_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583712005,
      "name": "pci_bus_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:64",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_read_config_byte"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583710800,
      "name": "pci_bus_read_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int pci_bus_read_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 * value)
```

```json
{
  "name": "pci_bus_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583969413,
      "name": "pci_bus_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:64",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_read_config_byte"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583968192,
      "name": "pci_bus_read_config_byte",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_bus_read_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 * value)
```

```json
{
  "name": "pci_bus_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584165413,
      "name": "pci_bus_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:63",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_read_config_byte"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584164384,
      "name": "pci_bus_read_config_byte",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int pci_bus_read_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 * value)
```

```json
{
  "name": "pci_bus_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584252544,
      "name": "pci_bus_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:63",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_read_config_byte",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584252544,
      "name": "pci_bus_read_config_byte",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int pci_bus_read_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 * value)
```

```json
{
  "name": "pci_bus_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584445712,
      "name": "pci_bus_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:63",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_read_config_byte",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584445712,
      "name": "pci_bus_read_config_byte",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int pci_bus_read_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 * value)
```

```json
{
  "name": "pci_bus_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584582464,
      "name": "pci_bus_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:63",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_read_config_byte",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584582464,
      "name": "pci_bus_read_config_byte",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int pci_bus_read_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 * value)
```

```json
{
  "name": "pci_bus_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585258320,
      "name": "pci_bus_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:63",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_read_config_byte",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585258320,
      "name": "pci_bus_read_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int pci_bus_read_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 * value)
```

```json
{
  "name": "pci_bus_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585416048,
      "name": "pci_bus_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:63",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_read_config_byte",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585416048,
      "name": "pci_bus_read_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int pci_bus_read_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 * value)
```

```json
{
  "name": "pci_bus_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585296592,
      "name": "pci_bus_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:63",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_read_config_byte",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585296592,
      "name": "pci_bus_read_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int pci_bus_read_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 * value)
```

```json
{
  "name": "pci_bus_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585753504,
      "name": "pci_bus_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:63",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_read_config_byte",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585753504,
      "name": "pci_bus_read_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int pci_bus_read_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 * value)
```

```json
{
  "name": "pci_bus_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586937040,
      "name": "pci_bus_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:66",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_read_config_byte",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586937040,
      "name": "pci_bus_read_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int pci_bus_read_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 * value)
```

```json
{
  "name": "pci_bus_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588094128,
      "name": "pci_bus_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:66",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_read_config_byte",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588094128,
      "name": "pci_bus_read_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int pci_bus_read_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 * value)
```

```json
{
  "name": "pci_bus_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588368560,
      "name": "pci_bus_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:66",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_read_config_byte",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588368560,
      "name": "pci_bus_read_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int pci_bus_read_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 * value)
```

```json
{
  "name": "pci_bus_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588663328,
      "name": "pci_bus_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:66",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_read_config_byte",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588663328,
      "name": "pci_bus_read_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int pci_bus_read_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 * value)
```

```json
{
  "name": "pci_bus_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496822104,
      "name": "pci_bus_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:63",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_read_config_byte",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496822104,
      "name": "pci_bus_read_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int pci_bus_read_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 * value)
```

```json
{
  "name": "pci_bus_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230100528,
      "name": "pci_bus_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:63",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_read_config_byte",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230100528,
      "name": "pci_bus_read_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int pci_bus_read_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 * value)
```

```json
{
  "name": "pci_bus_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290888240,
      "name": "pci_bus_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:63",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/pci-common.c:early_read_config_byte",
        "drivers/pci/access.c:pci_read_config_byte",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290888240,
      "name": "pci_bus_read_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int pci_bus_read_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 * value)
```

```json
{
  "name": "pci_bus_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275527076,
      "name": "pci_bus_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:63",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_read_config_byte",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275527076,
      "name": "pci_bus_read_config_byte",
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
int pci_bus_read_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 * value)
```

```json
{
  "name": "pci_bus_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584534624,
      "name": "pci_bus_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:63",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_read_config_byte",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584534624,
      "name": "pci_bus_read_config_byte",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int pci_bus_read_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 * value)
```

```json
{
  "name": "pci_bus_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584462800,
      "name": "pci_bus_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:63",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_read_config_byte",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584462800,
      "name": "pci_bus_read_config_byte",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int pci_bus_read_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 * value)
```

```json
{
  "name": "pci_bus_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584532624,
      "name": "pci_bus_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:63",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_read_config_byte",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584532624,
      "name": "pci_bus_read_config_byte",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int pci_bus_read_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 * value)
```

```json
{
  "name": "pci_bus_read_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584640400,
      "name": "pci_bus_read_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:63",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_read_config_byte",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_bus_find_capability",
        "drivers/pci/pci.c:__pci_find_next_cap_ttl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584640400,
      "name": "pci_bus_read_config_byte",
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
