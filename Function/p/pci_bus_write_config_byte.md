# Function: <code>pci_bus_write_config_byte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int pci_bus_write_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 value)
```

```json
{
  "name": "pci_bus_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583226976,
      "name": "pci_bus_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:59",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/quirks.c:quirk_via_ioapic",
        "drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert",
        "drivers/pci/quirks.c:quirk_mediagx_master",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
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
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_vt82c598_id",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_via_vlink",
        "drivers/pci/quirks.c:ht_enable_msi_mapping",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/htirq.c:__ht_create_irq",
        "drivers/pci/htirq.c:write_ht_irq_msg",
        "drivers/pci/htirq.c:write_ht_irq_msg",
        "drivers/acpi/reboot.c:acpi_reboot",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/char/agp/intel-agp.c:intel_8xx_cleanup",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_820_cleanup",
        "drivers/char/agp/intel-agp.c:intel_820_cleanup",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/via-agp.c:via_cleanup",
        "drivers/char/agp/via-agp.c:via_cleanup_agp3",
        "drivers/char/agp/via-agp.c:via_configure",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_pre_reset",
        "drivers/ata/pata_sis.c:sis_133_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_100_set_piomode",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530",
        "arch/x86/pci/irq.c:write_config_nybble",
        "arch/x86/pci/irq.c:pirq_sis_set",
        "arch/x86/pci/irq.c:pirq_piix_set",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_lookup_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583226976,
      "name": "pci_bus_write_config_byte",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int pci_bus_write_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 value)
```

```json
{
  "name": "pci_bus_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583535088,
      "name": "pci_bus_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:59",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ht_enable_msi_mapping",
        "drivers/pci/quirks.c:quirk_unhide_mch_dev6",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_sis_96x_smbus",
        "drivers/pci/quirks.c:quirk_ide_samemode",
        "drivers/pci/quirks.c:quirk_svwks_csb5ide",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_mediagx_master",
        "drivers/pci/quirks.c:quirk_vt82c598_id",
        "drivers/pci/quirks.c:quirk_via_vlink",
        "drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert",
        "drivers/pci/quirks.c:quirk_via_ioapic",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/htirq.c:__ht_create_irq",
        "drivers/pci/htirq.c:write_ht_irq_msg",
        "drivers/pci/htirq.c:write_ht_irq_msg",
        "drivers/acpi/reboot.c:acpi_reboot",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_820_cleanup",
        "drivers/char/agp/intel-agp.c:intel_820_cleanup",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-agp.c:intel_8xx_cleanup",
        "drivers/char/agp/via-agp.c:via_cleanup_agp3",
        "drivers/char/agp/via-agp.c:via_cleanup",
        "drivers/char/agp/via-agp.c:via_configure",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_133_set_piomode",
        "drivers/ata/pata_sis.c:sis_100_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_pre_reset",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pirq_sis_set",
        "arch/x86/pci/irq.c:pirq_piix_set",
        "arch/x86/pci/irq.c:write_config_nybble"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583535088,
      "name": "pci_bus_write_config_byte",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int pci_bus_write_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 value)
```

```json
{
  "name": "pci_bus_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583671296,
      "name": "pci_bus_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:59",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ht_enable_msi_mapping",
        "drivers/pci/quirks.c:quirk_unhide_mch_dev6",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_sis_503",
        "drivers/pci/quirks.c:quirk_sis_96x_smbus",
        "drivers/pci/quirks.c:quirk_ide_samemode",
        "drivers/pci/quirks.c:quirk_svwks_csb5ide",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_amd_ide_mode",
        "drivers/pci/quirks.c:quirk_mediagx_master",
        "drivers/pci/quirks.c:quirk_vt82c598_id",
        "drivers/pci/quirks.c:quirk_via_vlink",
        "drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert",
        "drivers/pci/quirks.c:quirk_via_ioapic",
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/htirq.c:__ht_create_irq",
        "drivers/pci/htirq.c:write_ht_irq_msg",
        "drivers/pci/htirq.c:write_ht_irq_msg",
        "drivers/acpi/reboot.c:acpi_reboot",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_820_cleanup",
        "drivers/char/agp/intel-agp.c:intel_820_cleanup",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-agp.c:intel_8xx_cleanup",
        "drivers/char/agp/via-agp.c:via_cleanup_agp3",
        "drivers/char/agp/via-agp.c:via_cleanup",
        "drivers/char/agp/via-agp.c:via_configure",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_133_set_piomode",
        "drivers/ata/pata_sis.c:sis_100_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_pre_reset",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pirq_sis_set",
        "arch/x86/pci/irq.c:pirq_piix_set",
        "arch/x86/pci/irq.c:write_config_nybble"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583671296,
      "name": "pci_bus_write_config_byte",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_bus_write_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 value)
```

```json
{
  "name": "pci_bus_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583712109,
      "name": "pci_bus_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:67",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_write_config_byte"
      ],
      "caller_func": [
        "drivers/acpi/reboot.c:acpi_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583711120,
      "name": "pci_bus_write_config_byte",
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
int pci_bus_write_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 value)
```

```json
{
  "name": "pci_bus_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583969533,
      "name": "pci_bus_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:67",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_write_config_byte"
      ],
      "caller_func": [
        "drivers/acpi/reboot.c:acpi_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583968512,
      "name": "pci_bus_write_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int pci_bus_write_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 value)
```

```json
{
  "name": "pci_bus_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584165833,
      "name": "pci_bus_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:66",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_write_config_byte"
      ],
      "caller_func": [
        "drivers/acpi/reboot.c:acpi_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584164704,
      "name": "pci_bus_write_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int pci_bus_write_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 value)
```

```json
{
  "name": "pci_bus_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584252864,
      "name": "pci_bus_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:66",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_write_config_byte",
        "drivers/acpi/reboot.c:acpi_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584252864,
      "name": "pci_bus_write_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int pci_bus_write_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 value)
```

```json
{
  "name": "pci_bus_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584446032,
      "name": "pci_bus_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:66",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_write_config_byte",
        "drivers/acpi/reboot.c:acpi_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584446032,
      "name": "pci_bus_write_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int pci_bus_write_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 value)
```

```json
{
  "name": "pci_bus_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584582784,
      "name": "pci_bus_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:66",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_write_config_byte",
        "drivers/acpi/reboot.c:acpi_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584582784,
      "name": "pci_bus_write_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int pci_bus_write_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 value)
```

```json
{
  "name": "pci_bus_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585258640,
      "name": "pci_bus_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:66",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_write_config_byte",
        "drivers/acpi/reboot.c:acpi_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585258640,
      "name": "pci_bus_write_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int pci_bus_write_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 value)
```

```json
{
  "name": "pci_bus_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585416368,
      "name": "pci_bus_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:66",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_write_config_byte",
        "drivers/acpi/reboot.c:acpi_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585416368,
      "name": "pci_bus_write_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int pci_bus_write_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 value)
```

```json
{
  "name": "pci_bus_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585296912,
      "name": "pci_bus_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:66",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_write_config_byte",
        "drivers/acpi/reboot.c:acpi_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585296912,
      "name": "pci_bus_write_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int pci_bus_write_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 value)
```

```json
{
  "name": "pci_bus_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585753824,
      "name": "pci_bus_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:66",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_write_config_byte",
        "drivers/acpi/reboot.c:acpi_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585753824,
      "name": "pci_bus_write_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int pci_bus_write_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 value)
```

```json
{
  "name": "pci_bus_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586937456,
      "name": "pci_bus_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:69",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_write_config_byte",
        "drivers/acpi/reboot.c:acpi_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586937456,
      "name": "pci_bus_write_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int pci_bus_write_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 value)
```

```json
{
  "name": "pci_bus_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588094592,
      "name": "pci_bus_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:69",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_write_config_byte",
        "drivers/acpi/reboot.c:acpi_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588094592,
      "name": "pci_bus_write_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int pci_bus_write_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 value)
```

```json
{
  "name": "pci_bus_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588369024,
      "name": "pci_bus_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:69",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_write_config_byte",
        "drivers/acpi/reboot.c:acpi_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588369024,
      "name": "pci_bus_write_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int pci_bus_write_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 value)
```

```json
{
  "name": "pci_bus_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588663792,
      "name": "pci_bus_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:69",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_write_config_byte",
        "drivers/acpi/reboot.c:acpi_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588663792,
      "name": "pci_bus_write_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int pci_bus_write_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 value)
```

```json
{
  "name": "pci_bus_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496821776,
      "name": "pci_bus_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:66",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_write_config_byte",
        "drivers/acpi/reboot.c:acpi_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496821776,
      "name": "pci_bus_write_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int pci_bus_write_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 value)
```

```json
{
  "name": "pci_bus_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230101132,
      "name": "pci_bus_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:66",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_write_config_byte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230101132,
      "name": "pci_bus_write_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int pci_bus_write_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 value)
```

```json
{
  "name": "pci_bus_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290889088,
      "name": "pci_bus_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:66",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/pci-common.c:early_write_config_byte",
        "drivers/pci/access.c:pci_write_config_byte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290889088,
      "name": "pci_bus_write_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int pci_bus_write_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 value)
```

```json
{
  "name": "pci_bus_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275527476,
      "name": "pci_bus_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:66",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_write_config_byte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275527476,
      "name": "pci_bus_write_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int pci_bus_write_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 value)
```

```json
{
  "name": "pci_bus_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584534944,
      "name": "pci_bus_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:66",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_write_config_byte",
        "drivers/acpi/reboot.c:acpi_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584534944,
      "name": "pci_bus_write_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int pci_bus_write_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 value)
```

```json
{
  "name": "pci_bus_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584463120,
      "name": "pci_bus_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:66",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_write_config_byte",
        "drivers/acpi/reboot.c:acpi_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584463120,
      "name": "pci_bus_write_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int pci_bus_write_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 value)
```

```json
{
  "name": "pci_bus_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584532944,
      "name": "pci_bus_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:66",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_write_config_byte",
        "drivers/acpi/reboot.c:acpi_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584532944,
      "name": "pci_bus_write_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int pci_bus_write_config_byte(struct pci_bus * bus, unsigned int devfn, int pos, u8 value)
```

```json
{
  "name": "pci_bus_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584640720,
      "name": "pci_bus_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:66",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_write_config_byte",
        "drivers/acpi/reboot.c:acpi_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584640720,
      "name": "pci_bus_write_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
