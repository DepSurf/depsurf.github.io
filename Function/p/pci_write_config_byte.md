# Function: <code>pci_write_config_byte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_write_config_byte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579063576,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:919",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583235341,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:919",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583255274,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:919",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583313579,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:919",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583388991,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:919",
      "file": "drivers/pci/htirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/htirq.c:__ht_create_irq",
        "drivers/pci/htirq.c:write_ht_irq_msg",
        "drivers/pci/htirq.c:write_ht_irq_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584129869,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:919",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584219886,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:919",
      "file": "drivers/char/agp/intel-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "drivers/char/agp/intel-agp.c:intel_815_configure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584231480,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:919",
      "file": "drivers/char/agp/via-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/via-agp.c:via_cleanup",
        "drivers/char/agp/via-agp.c:via_cleanup_agp3",
        "drivers/char/agp/via-agp.c:via_configure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585017066,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:919",
      "file": "drivers/ata/ata_piix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:do_pata_set_dmamode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585020827,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:919",
      "file": "drivers/ata/pata_sis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_pre_reset",
        "drivers/ata/pata_sis.c:sis_133_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_100_set_piomode",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585335931,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:919",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585386000,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:919",
      "file": "drivers/usb/host/ehci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585420789,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:919",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595306141,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:919",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:hwmon_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586153773,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:919",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586157414,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:919",
      "file": "arch/x86/pci/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/irq.c:write_config_nybble",
        "arch/x86/pci/irq.c:pirq_sis_set",
        "arch/x86/pci/irq.c:pirq_piix_set",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_lookup_irq"
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
  "name": "pci_write_config_byte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579059992,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:930",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583544435,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:930",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583564890,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:930",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583632297,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:930",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "drivers/pci/quirks.c:quirk_passive_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583703423,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:930",
      "file": "drivers/pci/htirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/htirq.c:__ht_create_irq",
        "drivers/pci/htirq.c:write_ht_irq_msg",
        "drivers/pci/htirq.c:write_ht_irq_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584467474,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:930",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584559552,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:930",
      "file": "drivers/char/agp/intel-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "drivers/char/agp/intel-agp.c:intel_8xx_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584571308,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:930",
      "file": "drivers/char/agp/via-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/via-agp.c:via_cleanup_agp3",
        "drivers/char/agp/via-agp.c:via_cleanup",
        "drivers/char/agp/via-agp.c:via_configure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585385550,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:930",
      "file": "drivers/ata/ata_piix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585392051,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:930",
      "file": "drivers/ata/pata_sis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_133_set_piomode",
        "drivers/ata/pata_sis.c:sis_100_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_pre_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585732316,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:930",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585782296,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:930",
      "file": "drivers/usb/host/ehci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585834608,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:930",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595489389,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:930",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:hwmon_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586566793,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:930",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586573388,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:930",
      "file": "arch/x86/pci/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pirq_sis_set",
        "arch/x86/pci/irq.c:pirq_piix_set",
        "arch/x86/pci/irq.c:write_config_nybble"
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
  "name": "pci_write_config_byte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579059032,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:960",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583680755,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:960",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583701674,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:960",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583769593,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:960",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "drivers/pci/quirks.c:quirk_passive_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583841743,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:960",
      "file": "drivers/pci/htirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/htirq.c:__ht_create_irq",
        "drivers/pci/htirq.c:write_ht_irq_msg",
        "drivers/pci/htirq.c:write_ht_irq_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584650066,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:960",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584741424,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:960",
      "file": "drivers/char/agp/intel-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "drivers/char/agp/intel-agp.c:intel_8xx_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584753212,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:960",
      "file": "drivers/char/agp/via-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/via-agp.c:via_cleanup_agp3",
        "drivers/char/agp/via-agp.c:via_cleanup",
        "drivers/char/agp/via-agp.c:via_configure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585586382,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:960",
      "file": "drivers/ata/ata_piix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/ata_piix.c:do_pata_set_dmamode",
        "drivers/ata/ata_piix.c:piix_set_timings",
        "drivers/ata/ata_piix.c:piix_set_timings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585592867,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:960",
      "file": "drivers/ata/pata_sis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_133_set_piomode",
        "drivers/ata/pata_sis.c:sis_100_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_pre_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585920908,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:960",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585970981,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:960",
      "file": "drivers/usb/host/ehci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586023344,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:960",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595742424,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:960",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:hwmon_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586748345,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:960",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586754940,
      "name": "pci_write_config_byte",
      "external": false,
      "loc": "include/linux/pci.h:960",
      "file": "arch/x86/pci/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pirq_sis_set",
        "arch/x86/pci/irq.c:pirq_piix_set",
        "arch/x86/pci/irq.c:write_config_nybble"
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
int pci_write_config_byte(const struct pci_dev * dev, int where, u8 val)
```

```json
{
  "name": "pci_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583712080,
      "name": "pci_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:934",
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
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/setup-irq.c:pcibios_update_irq",
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
      "addr": 18446744071583712080,
      "name": "pci_write_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int pci_write_config_byte(const struct pci_dev * dev, int where, u8 val)
```

```json
{
  "name": "pci_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583969504,
      "name": "pci_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:934",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/setup-irq.c:pci_assign_irq",
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
      "addr": 18446744071583969504,
      "name": "pci_write_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int pci_write_config_byte(const struct pci_dev * dev, int where, u8 val)
```

```json
{
  "name": "pci_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584165808,
      "name": "pci_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:567",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/setup-irq.c:pci_assign_irq",
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
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
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
      "addr": 18446744071584165808,
      "name": "pci_write_config_byte",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int pci_write_config_byte(const struct pci_dev * dev, int where, u8 val)
```

```json
{
  "name": "pci_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584253696,
      "name": "pci_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:567",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/setup-irq.c:pci_assign_irq",
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
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
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
      "addr": 18446744071584253696,
      "name": "pci_write_config_byte",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int pci_write_config_byte(const struct pci_dev * dev, int where, u8 val)
```

```json
{
  "name": "pci_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584446864,
      "name": "pci_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:567",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "drivers/pci/probe.c:program_hpp_type0",
        "drivers/pci/probe.c:program_hpp_type0",
        "drivers/pci/probe.c:program_hpp_type0",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/setup-irq.c:pci_assign_irq",
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
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
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
      "addr": 18446744071584446864,
      "name": "pci_write_config_byte",
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
int pci_write_config_byte(const struct pci_dev * dev, int where, u8 val)
```

```json
{
  "name": "pci_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584583616,
      "name": "pci_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:558",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
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
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
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
      "addr": 18446744071584583616,
      "name": "pci_write_config_byte",
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
int pci_write_config_byte(const struct pci_dev * dev, int where, u8 val)
```

```json
{
  "name": "pci_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585259472,
      "name": "pci_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:554",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_ixp4x0_rev",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
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
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
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
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_133_set_piomode",
        "drivers/ata/pata_sis.c:sis_100_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_pre_reset",
        "drivers/usb/host/pci-quirks.c:ehci_bios_handoff",
        "drivers/usb/host/pci-quirks.c:ehci_bios_handoff",
        "drivers/usb/host/pci-quirks.c:ehci_bios_handoff",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/hwmon/hwmon.c:hwmon_pci_quirks",
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
      "addr": 18446744071585259472,
      "name": "pci_write_config_byte",
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
int pci_write_config_byte(const struct pci_dev * dev, int where, u8 val)
```

```json
{
  "name": "pci_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585417200,
      "name": "pci_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:554",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_ixp4x0_rev",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
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
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
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
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_133_set_piomode",
        "drivers/ata/pata_sis.c:sis_100_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_pre_reset",
        "drivers/usb/host/pci-quirks.c:ehci_bios_handoff",
        "drivers/usb/host/pci-quirks.c:ehci_bios_handoff",
        "drivers/usb/host/pci-quirks.c:ehci_bios_handoff",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/hwmon/hwmon.c:hwmon_pci_quirks",
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
      "addr": 18446744071585417200,
      "name": "pci_write_config_byte",
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
int pci_write_config_byte(const struct pci_dev * dev, int where, u8 val)
```

```json
{
  "name": "pci_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585297776,
      "name": "pci_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:554",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
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
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
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
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_133_set_piomode",
        "drivers/ata/pata_sis.c:sis_100_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_pre_reset",
        "drivers/usb/host/pci-quirks.c:ehci_bios_handoff",
        "drivers/usb/host/pci-quirks.c:ehci_bios_handoff",
        "drivers/usb/host/pci-quirks.c:ehci_bios_handoff",
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
      "addr": 18446744071585297776,
      "name": "pci_write_config_byte",
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
int pci_write_config_byte(const struct pci_dev * dev, int where, u8 val)
```

```json
{
  "name": "pci_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585754560,
      "name": "pci_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:554",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
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
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
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
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_133_set_piomode",
        "drivers/ata/pata_sis.c:sis_100_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_pre_reset",
        "drivers/usb/host/pci-quirks.c:ehci_bios_handoff",
        "drivers/usb/host/pci-quirks.c:ehci_bios_handoff",
        "drivers/usb/host/pci-quirks.c:ehci_bios_handoff",
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
        "arch/x86/pci/irq.c:pirq_ib_set",
        "arch/x86/pci/irq.c:pirq_piix_set",
        "arch/x86/pci/irq.c:write_config_nybble"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585754560,
      "name": "pci_write_config_byte",
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
int pci_write_config_byte(const struct pci_dev * dev, int where, u8 val)
```

```json
{
  "name": "pci_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586938336,
      "name": "pci_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:559",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:quirk_intel_irqbalance",
        "arch/x86/kernel/quirks.c:quirk_intel_irqbalance",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
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
        "drivers/pci/quirks.c:asus_hides_ac97_lpc",
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
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
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
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_133_set_piomode",
        "drivers/ata/pata_sis.c:sis_100_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_pre_reset",
        "drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci",
        "drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci",
        "drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530",
        "arch/x86/pci/fixup.c:pci_fixup_msi_k8t_onboard_sound",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pirq_sis503_set",
        "arch/x86/pci/irq.c:pirq_sis497_set",
        "arch/x86/pci/irq.c:pirq_ib_set",
        "arch/x86/pci/irq.c:pirq_piix_set",
        "arch/x86/pci/irq.c:write_config_nybble"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586938336,
      "name": "pci_write_config_byte",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int pci_write_config_byte(const struct pci_dev * dev, int where, u8 val)
```

```json
{
  "name": "pci_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588095632,
      "name": "pci_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:565",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:quirk_intel_irqbalance",
        "arch/x86/kernel/quirks.c:quirk_intel_irqbalance",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
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
        "drivers/pci/quirks.c:asus_hides_ac97_lpc",
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
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
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
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_133_set_piomode",
        "drivers/ata/pata_sis.c:sis_100_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_pre_reset",
        "drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci",
        "drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci",
        "drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530",
        "arch/x86/pci/fixup.c:pci_fixup_msi_k8t_onboard_sound",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pirq_sis503_set",
        "arch/x86/pci/irq.c:pirq_sis497_set",
        "arch/x86/pci/irq.c:pirq_ib_set",
        "arch/x86/pci/irq.c:pirq_piix_set",
        "arch/x86/pci/irq.c:write_config_nybble"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588095632,
      "name": "pci_write_config_byte",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int pci_write_config_byte(const struct pci_dev * dev, int where, u8 val)
```

```json
{
  "name": "pci_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588370064,
      "name": "pci_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:579",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:quirk_intel_irqbalance",
        "arch/x86/kernel/quirks.c:quirk_intel_irqbalance",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
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
        "drivers/pci/quirks.c:asus_hides_ac97_lpc",
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
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
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
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_133_set_piomode",
        "drivers/ata/pata_sis.c:sis_100_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_pre_reset",
        "drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci",
        "drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci",
        "drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530",
        "arch/x86/pci/fixup.c:pci_fixup_msi_k8t_onboard_sound",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pirq_sis503_set",
        "arch/x86/pci/irq.c:pirq_sis497_set",
        "arch/x86/pci/irq.c:pirq_ib_set",
        "arch/x86/pci/irq.c:pirq_piix_set",
        "arch/x86/pci/irq.c:write_config_nybble"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588370064,
      "name": "pci_write_config_byte",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int pci_write_config_byte(const struct pci_dev * dev, int where, u8 val)
```

```json
{
  "name": "pci_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588664832,
      "name": "pci_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:577",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:quirk_intel_irqbalance",
        "arch/x86/kernel/quirks.c:quirk_intel_irqbalance",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
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
        "drivers/pci/quirks.c:asus_hides_ac97_lpc",
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
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
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
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_fixup",
        "drivers/ata/pata_sis.c:sis_133_early_set_dmamode",
        "drivers/ata/pata_sis.c:sis_100_set_dmamode",
        "drivers/ata/pata_sis.c:sis_133_set_piomode",
        "drivers/ata/pata_sis.c:sis_100_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_old_set_piomode",
        "drivers/ata/pata_sis.c:sis_pre_reset",
        "drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci",
        "drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci",
        "drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530",
        "arch/x86/pci/fixup.c:pci_fixup_msi_k8t_onboard_sound",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pcibios_lookup_irq",
        "arch/x86/pci/irq.c:pirq_sis503_set",
        "arch/x86/pci/irq.c:pirq_sis497_set",
        "arch/x86/pci/irq.c:pirq_ib_set",
        "arch/x86/pci/irq.c:pirq_piix_set",
        "arch/x86/pci/irq.c:write_config_nybble"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588664832,
      "name": "pci_write_config_byte",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int pci_write_config_byte(const struct pci_dev * dev, int where, u8 val)
```

```json
{
  "name": "pci_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496822000,
      "name": "pci_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:558",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
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
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496822000,
      "name": "pci_write_config_byte",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int pci_write_config_byte(const struct pci_dev * dev, int where, u8 val)
```

```json
{
  "name": "pci_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230102200,
      "name": "pci_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:558",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/bios32.c:pcibios_fixup_bus",
        "arch/arm/kernel/bios32.c:pci_fixup_83c553",
        "arch/arm/kernel/bios32.c:pci_fixup_83c553",
        "arch/arm/kernel/bios32.c:pci_fixup_83c553",
        "arch/arm/kernel/bios32.c:pci_fixup_83c553",
        "arch/arm/kernel/bios32.c:pci_fixup_83c553",
        "arch/arm/kernel/bios32.c:pci_fixup_83c553",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/setup-irq.c:pci_assign_irq",
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
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230102200,
      "name": "pci_write_config_byte",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int pci_write_config_byte(const struct pci_dev * dev, int where, u8 val)
```

```json
{
  "name": "pci_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290890528,
      "name": "pci_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:558",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/setup-irq.c:pci_assign_irq",
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
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290890528,
      "name": "pci_write_config_byte",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int pci_write_config_byte(const struct pci_dev * dev, int where, u8 val)
```

```json
{
  "name": "pci_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275528734,
      "name": "pci_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:558",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/setup-irq.c:pci_assign_irq",
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
        "drivers/pci/quirks.c:quirk_vialatency",
        "drivers/pci/quirks.c:quirk_passive_release",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275528734,
      "name": "pci_write_config_byte",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int pci_write_config_byte(const struct pci_dev * dev, int where, u8 val)
```

```json
{
  "name": "pci_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584535776,
      "name": "pci_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:558",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
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
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
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
      "addr": 18446744071584535776,
      "name": "pci_write_config_byte",
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
int pci_write_config_byte(const struct pci_dev * dev, int where, u8 val)
```

```json
{
  "name": "pci_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584463952,
      "name": "pci_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:558",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
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
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
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
      "addr": 18446744071584463952,
      "name": "pci_write_config_byte",
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
int pci_write_config_byte(const struct pci_dev * dev, int where, u8 val)
```

```json
{
  "name": "pci_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584533776,
      "name": "pci_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:558",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
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
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
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
      "addr": 18446744071584533776,
      "name": "pci_write_config_byte",
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
int pci_write_config_byte(const struct pci_dev * dev, int where, u8 val)
```

```json
{
  "name": "pci_write_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584641552,
      "name": "pci_write_config_byte",
      "external": true,
      "loc": "drivers/pci/access.c:558",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_set_cacheline_size",
        "drivers/pci/pci.c:pcibios_set_master",
        "drivers/pci/setup-irq.c:pci_assign_irq",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
        "drivers/pci/pci-acpi.c:program_hpx_type0",
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
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init",
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
      "addr": 18446744071584641552,
      "name": "pci_write_config_byte",
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
int pci_write_config_byte(const struct pci_dev * dev, int where, u8 val)
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
