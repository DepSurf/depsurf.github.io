# Function: <code>dmi_check_system</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int dmi_check_system(const struct dmi_system_id * list)
```

```json
{
  "name": "dmi_check_system",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585984800,
      "name": "dmi_check_system",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:783",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/io_delay.c:io_delay_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_table_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/apic/apic.c:apic_is_clustered_box",
        "arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks",
        "arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi",
        "drivers/acpi/blacklist.c:acpi_blacklisted",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/bus.c:acpi_early_init",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/ac.c:acpi_ac_add",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/battery.c:acpi_battery_init_async",
        "drivers/ata/ata_piix.c:piix_pci_device_suspend",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/input/keyboard/atkbd.c:atkbd_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "arch/x86/pci/acpi.c:pci_acpi_crs_quirks",
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/common.c:dmi_check_pciprobe",
        "arch/x86/pci/common.c:dmi_check_skip_isa_align"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585984800,
      "name": "dmi_check_system",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int dmi_check_system(const struct dmi_system_id * list)
```

```json
{
  "name": "dmi_check_system",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586391184,
      "name": "dmi_check_system",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:805",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/io_delay.c:io_delay_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_table_init",
        "arch/x86/kernel/apic/apic.c:apic_is_clustered_box",
        "arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks",
        "arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi",
        "arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks",
        "drivers/acpi/blacklist.c:acpi_blacklisted",
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/bus.c:acpi_early_init",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/ac.c:acpi_ac_add",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/battery.c:acpi_battery_init_async",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_pci_device_suspend",
        "drivers/input/keyboard/atkbd.c:atkbd_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "arch/x86/pci/acpi.c:pci_acpi_crs_quirks",
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/common.c:dmi_check_skip_isa_align",
        "arch/x86/pci/common.c:dmi_check_pciprobe",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586391184,
      "name": "dmi_check_system",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int dmi_check_system(const struct dmi_system_id * list)
```

```json
{
  "name": "dmi_check_system",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586600032,
      "name": "dmi_check_system",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:805",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/io_delay.c:io_delay_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_table_init",
        "arch/x86/kernel/apic/apic.c:apic_is_clustered_box",
        "arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks",
        "arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi",
        "arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks",
        "drivers/acpi/blacklist.c:acpi_blacklisted",
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/bus.c:acpi_early_init",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/ac.c:acpi_ac_add",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/battery.c:acpi_battery_init_async",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_pci_device_suspend",
        "drivers/input/keyboard/atkbd.c:atkbd_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "arch/x86/pci/acpi.c:pci_acpi_crs_quirks",
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/common.c:dmi_check_skip_isa_align",
        "arch/x86/pci/common.c:dmi_check_pciprobe",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586600032,
      "name": "dmi_check_system",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int dmi_check_system(const struct dmi_system_id * list)
```

```json
{
  "name": "dmi_check_system",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586724976,
      "name": "dmi_check_system",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:830",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/io_delay.c:io_delay_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_table_init",
        "arch/x86/kernel/apic/apic.c:apic_is_clustered_box",
        "arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks",
        "arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi",
        "arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/acpi/blacklist.c:acpi_blacklisted",
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/bus.c:acpi_early_init",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/acpi/ac.c:acpi_ac_add",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_pci_device_suspend",
        "drivers/input/keyboard/atkbd.c:atkbd_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "arch/x86/pci/acpi.c:pci_acpi_crs_quirks",
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/common.c:dmi_check_skip_isa_align",
        "arch/x86/pci/common.c:dmi_check_pciprobe",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586724976,
      "name": "dmi_check_system",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int dmi_check_system(const struct dmi_system_id * list)
```

```json
{
  "name": "dmi_check_system",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587209280,
      "name": "dmi_check_system",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:830",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/io_delay.c:io_delay_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_table_init",
        "arch/x86/kernel/apic/apic.c:apic_is_clustered_box",
        "arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks",
        "arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi",
        "arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/acpi/blacklist.c:acpi_blacklisted",
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/bus.c:acpi_early_init",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/acpi/ac.c:acpi_ac_add",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_pci_device_suspend",
        "drivers/input/keyboard/atkbd.c:atkbd_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "arch/x86/pci/acpi.c:pci_acpi_crs_quirks",
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/common.c:dmi_check_skip_isa_align",
        "arch/x86/pci/common.c:dmi_check_pciprobe",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587209280,
      "name": "dmi_check_system",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int dmi_check_system(const struct dmi_system_id * list)
```

```json
{
  "name": "dmi_check_system",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587510176,
      "name": "dmi_check_system",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:846",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/io_delay.c:io_delay_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_table_init",
        "arch/x86/kernel/reboot.c:reboot_init",
        "arch/x86/kernel/apic/apic.c:apic_is_clustered_box",
        "arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks",
        "arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi",
        "arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init",
        "drivers/acpi/blacklist.c:acpi_blacklisted",
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/bus.c:acpi_early_init",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/acpi/ac.c:acpi_ac_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/acpi/battery.c:acpi_battery_init_async",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_pci_device_suspend",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/keyboard/atkbd.c:atkbd_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "arch/x86/pci/acpi.c:pci_acpi_crs_quirks",
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/common.c:dmi_check_skip_isa_align",
        "arch/x86/pci/common.c:dmi_check_pciprobe",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587510176,
      "name": "dmi_check_system",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int dmi_check_system(const struct dmi_system_id * list)
```

```json
{
  "name": "dmi_check_system",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587690336,
      "name": "dmi_check_system",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:846",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/io_delay.c:io_delay_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_table_init",
        "arch/x86/kernel/reboot.c:reboot_init",
        "arch/x86/kernel/apic/apic.c:apic_is_clustered_box",
        "arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks",
        "arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi",
        "arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init",
        "drivers/acpi/blacklist.c:acpi_blacklisted",
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/bus.c:acpi_early_init",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/acpi/ac.c:acpi_ac_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/acpi/battery.c:acpi_battery_init_async",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_pci_device_suspend",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/keyboard/atkbd.c:atkbd_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "arch/x86/pci/acpi.c:pci_acpi_crs_quirks",
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/common.c:dmi_check_skip_isa_align",
        "arch/x86/pci/common.c:dmi_check_pciprobe",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587690336,
      "name": "dmi_check_system",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int dmi_check_system(const struct dmi_system_id * list)
```

```json
{
  "name": "dmi_check_system",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587969552,
      "name": "dmi_check_system",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:849",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/io_delay.c:io_delay_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_table_init",
        "arch/x86/kernel/reboot.c:reboot_init",
        "arch/x86/kernel/apic/apic.c:apic_is_clustered_box",
        "arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks",
        "arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks",
        "arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi",
        "arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init",
        "drivers/acpi/blacklist.c:acpi_blacklisted",
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/bus.c:acpi_early_init",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/acpi/ac.c:acpi_ac_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/acpi/battery.c:acpi_battery_init_async",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_pci_device_suspend",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/keyboard/atkbd.c:atkbd_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "arch/x86/pci/acpi.c:pci_acpi_crs_quirks",
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/common.c:dmi_check_skip_isa_align",
        "arch/x86/pci/common.c:dmi_check_pciprobe",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587969552,
      "name": "dmi_check_system",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int dmi_check_system(const struct dmi_system_id * list)
```

```json
{
  "name": "dmi_check_system",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588176688,
      "name": "dmi_check_system",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:849",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/io_delay.c:io_delay_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_table_init",
        "arch/x86/kernel/reboot.c:reboot_init",
        "arch/x86/kernel/apic/apic.c:apic_is_clustered_box",
        "arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks",
        "arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks",
        "arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi",
        "arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init",
        "drivers/acpi/blacklist.c:acpi_blacklisted",
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/bus.c:acpi_early_init",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/acpi/ac.c:acpi_ac_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/acpi/battery.c:acpi_battery_init_async",
        "drivers/iommu/amd_iommu_quirks.c:amd_iommu_apply_ivrs_quirks",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_pci_device_suspend",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/keyboard/atkbd.c:atkbd_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "arch/x86/pci/acpi.c:pci_acpi_crs_quirks",
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/common.c:dmi_check_skip_isa_align",
        "arch/x86/pci/common.c:dmi_check_pciprobe",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588176688,
      "name": "dmi_check_system",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int dmi_check_system(const struct dmi_system_id * list)
```

```json
{
  "name": "dmi_check_system",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589042416,
      "name": "dmi_check_system",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:885",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/io_delay.c:io_delay_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_table_init",
        "arch/x86/kernel/reboot.c:reboot_init",
        "arch/x86/kernel/apic/apic.c:apic_is_clustered_box",
        "arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks",
        "arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks",
        "arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi",
        "arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init",
        "drivers/acpi/blacklist.c:acpi_blacklisted",
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/bus.c:acpi_early_init",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/pci_irq.c:do_prt_fixups",
        "drivers/acpi/pci_irq.c:do_prt_fixups",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/acpi/ac.c:acpi_ac_init",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/acpi/battery.c:acpi_battery_init_async",
        "drivers/iommu/amd/quirks.c:amd_iommu_apply_ivrs_quirks",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_broken_suspend",
        "drivers/usb/host/pci-quirks.c:ehci_bios_handoff",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_pnp_init",
        "drivers/input/serio/i8042.c:i8042_pnp_init",
        "drivers/input/keyboard/atkbd.c:atkbd_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "arch/x86/pci/acpi.c:pci_acpi_crs_quirks",
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/common.c:dmi_check_skip_isa_align",
        "arch/x86/pci/common.c:dmi_check_pciprobe",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589042416,
      "name": "dmi_check_system",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int dmi_check_system(const struct dmi_system_id * list)
```

```json
{
  "name": "dmi_check_system",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589051744,
      "name": "dmi_check_system",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:885",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/io_delay.c:io_delay_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_table_init",
        "arch/x86/kernel/reboot.c:reboot_init",
        "arch/x86/kernel/apic/apic.c:apic_is_clustered_box",
        "arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks",
        "arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks",
        "arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init",
        "drivers/acpi/blacklist.c:acpi_blacklisted",
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/bus.c:acpi_early_init",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/pci_irq.c:do_prt_fixups",
        "drivers/acpi/pci_irq.c:do_prt_fixups",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/acpi/ac.c:acpi_ac_init",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/acpi/battery.c:acpi_battery_init_async",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/iommu/amd/quirks.c:amd_iommu_apply_ivrs_quirks",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_broken_suspend",
        "drivers/usb/host/pci-quirks.c:ehci_bios_handoff",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_pnp_init",
        "drivers/input/serio/i8042.c:i8042_pnp_init",
        "drivers/input/keyboard/atkbd.c:atkbd_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "arch/x86/pci/acpi.c:pci_acpi_crs_quirks",
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/common.c:dmi_check_skip_isa_align",
        "arch/x86/pci/common.c:dmi_check_pciprobe",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589051744,
      "name": "dmi_check_system",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int dmi_check_system(const struct dmi_system_id * list)
```

```json
{
  "name": "dmi_check_system",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588939104,
      "name": "dmi_check_system",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:886",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/io_delay.c:io_delay_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_table_init",
        "arch/x86/kernel/reboot.c:reboot_init",
        "arch/x86/kernel/apic/apic.c:apic_is_clustered_box",
        "arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks",
        "arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks",
        "arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init",
        "drivers/acpi/blacklist.c:acpi_blacklisted",
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/bus.c:acpi_early_init",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/pci_irq.c:do_prt_fixups",
        "drivers/acpi/pci_irq.c:do_prt_fixups",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/acpi/ac.c:acpi_ac_init",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/acpi/battery.c:acpi_battery_init_async",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/iommu/amd/quirks.c:amd_iommu_apply_ivrs_quirks",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_pci_device_suspend",
        "drivers/usb/host/pci-quirks.c:ehci_bios_handoff",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_init",
        "drivers/input/serio/i8042.c:i8042_pnp_init",
        "drivers/input/keyboard/atkbd.c:atkbd_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "arch/x86/pci/acpi.c:pci_acpi_crs_quirks",
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/common.c:dmi_check_skip_isa_align",
        "arch/x86/pci/common.c:dmi_check_pciprobe",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588939104,
      "name": "dmi_check_system",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int dmi_check_system(const struct dmi_system_id * list)
```

```json
{
  "name": "dmi_check_system",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589647424,
      "name": "dmi_check_system",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:886",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/io_delay.c:io_delay_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_table_init",
        "arch/x86/kernel/reboot.c:reboot_init",
        "arch/x86/kernel/apic/apic.c:apic_is_clustered_box",
        "arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init",
        "drivers/acpi/blacklist.c:acpi_blacklisted",
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/bus.c:acpi_early_init",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/pci_irq.c:do_prt_fixups",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/x86/utils.c:acpi_device_override_status",
        "drivers/acpi/ac.c:acpi_ac_init",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/acpi/battery.c:acpi_battery_init_async",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/iommu/amd/quirks.c:amd_iommu_apply_ivrs_quirks",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_pci_device_suspend",
        "drivers/usb/host/pci-quirks.c:ehci_bios_handoff",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_pnp_init",
        "drivers/input/serio/i8042.c:i8042_pnp_init",
        "drivers/input/keyboard/atkbd.c:atkbd_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/firmware/efi/sysfb_efi.c:sysfb_apply_efi_quirks",
        "drivers/firmware/efi/sysfb_efi.c:sysfb_apply_efi_quirks",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_probe",
        "arch/x86/pci/acpi.c:pci_acpi_crs_quirks",
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/common.c:dmi_check_skip_isa_align",
        "arch/x86/pci/common.c:dmi_check_pciprobe",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589647424,
      "name": "dmi_check_system",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int dmi_check_system(const struct dmi_system_id * list)
```

```json
{
  "name": "dmi_check_system",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591148752,
      "name": "dmi_check_system",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:886",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/io_delay.c:io_delay_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_table_init",
        "arch/x86/kernel/reboot.c:reboot_init",
        "arch/x86/kernel/apic/apic.c:apic_is_clustered_box",
        "arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe",
        "drivers/pci/pci.c:pci_allocate_cap_save_buffers",
        "drivers/pci/pci.c:pci_bridge_d3_possible",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init",
        "drivers/acpi/blacklist.c:acpi_blacklisted",
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/bus.c:acpi_early_init",
        "drivers/acpi/resource.c:acpi_dev_get_irqresource",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/pci_irq.c:do_prt_fixups",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/x86/utils.c:acpi_device_override_status",
        "drivers/acpi/ac.c:acpi_ac_init",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/acpi/battery.c:acpi_battery_init_async",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/iommu/amd/quirks.c:amd_iommu_apply_ivrs_quirks",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_pci_device_suspend",
        "drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_pnp_init",
        "drivers/input/serio/i8042.c:i8042_pnp_init",
        "drivers/input/keyboard/atkbd.c:atkbd_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/firmware/efi/sysfb_efi.c:sysfb_apply_efi_quirks",
        "drivers/firmware/efi/sysfb_efi.c:sysfb_apply_efi_quirks",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_probe",
        "arch/x86/pci/fixup.c:pci_fixup_msi_k8t_onboard_sound",
        "arch/x86/pci/acpi.c:pci_acpi_crs_quirks",
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/common.c:dmi_check_skip_isa_align",
        "arch/x86/pci/common.c:dmi_check_pciprobe",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591148752,
      "name": "dmi_check_system",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int dmi_check_system(const struct dmi_system_id * list)
```

```json
{
  "name": "dmi_check_system",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592875200,
      "name": "dmi_check_system",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:892",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/io_delay.c:io_delay_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_table_init",
        "arch/x86/kernel/reboot.c:reboot_init",
        "arch/x86/kernel/apic/apic.c:apic_is_clustered_box",
        "arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe",
        "drivers/pci/pci.c:pci_bridge_d3_possible",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_init",
        "drivers/acpi/blacklist.c:acpi_blacklisted",
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/bus.c:acpi_early_init",
        "drivers/acpi/resource.c:acpi_dev_get_irqresource",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/pci_irq.c:do_prt_fixups",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/x86/utils.c:acpi_device_override_status",
        "drivers/acpi/x86/s2idle.c:acpi_s2idle_setup",
        "drivers/acpi/ac.c:acpi_ac_init",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/acpi/battery.c:acpi_battery_init_async",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/iommu/amd/quirks.c:amd_iommu_apply_ivrs_quirks",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_pci_device_suspend",
        "drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci",
        "drivers/input/serio/i8042.c:i8042_pnp_init",
        "drivers/input/keyboard/atkbd.c:atkbd_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/firmware/efi/sysfb_efi.c:sysfb_apply_efi_quirks",
        "drivers/firmware/efi/sysfb_efi.c:sysfb_apply_efi_quirks",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_probe",
        "arch/x86/pci/fixup.c:pci_fixup_msi_k8t_onboard_sound",
        "arch/x86/pci/acpi.c:pci_acpi_crs_quirks",
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/common.c:dmi_check_skip_isa_align",
        "arch/x86/pci/common.c:dmi_check_pciprobe",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592875200,
      "name": "dmi_check_system",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int dmi_check_system(const struct dmi_system_id * list)
```

```json
{
  "name": "dmi_check_system",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593313680,
      "name": "dmi_check_system",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:892",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/io_delay.c:io_delay_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_table_init",
        "arch/x86/kernel/reboot.c:reboot_init",
        "arch/x86/kernel/apic/apic.c:apic_is_clustered_box",
        "arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe",
        "drivers/pci/pci.c:pci_bridge_d3_possible",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_init",
        "drivers/acpi/blacklist.c:acpi_blacklisted",
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/bus.c:acpi_early_init",
        "drivers/acpi/resource.c:acpi_dev_get_irqresource",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/pci_irq.c:do_prt_fixups",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/power.c:acpi_turn_off_unused_power_resources",
        "drivers/acpi/x86/utils.c:acpi_device_override_status",
        "drivers/acpi/ac.c:acpi_ac_init",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/acpi/battery.c:acpi_battery_init_async",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/iommu/amd/quirks.c:amd_iommu_apply_ivrs_quirks",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_pci_device_suspend",
        "drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci",
        "drivers/input/serio/i8042.c:i8042_pnp_init",
        "drivers/input/keyboard/atkbd.c:atkbd_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/firmware/efi/sysfb_efi.c:sysfb_apply_efi_quirks",
        "drivers/firmware/efi/sysfb_efi.c:sysfb_apply_efi_quirks",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_probe",
        "arch/x86/pci/fixup.c:pci_fixup_msi_k8t_onboard_sound",
        "arch/x86/pci/acpi.c:pci_acpi_crs_quirks",
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/common.c:dmi_check_skip_isa_align",
        "arch/x86/pci/common.c:dmi_check_pciprobe",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593313680,
      "name": "dmi_check_system",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int dmi_check_system(const struct dmi_system_id * list)
```

```json
{
  "name": "dmi_check_system",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594070224,
      "name": "dmi_check_system",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:892",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/io_delay.c:io_delay_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_table_init",
        "arch/x86/kernel/reboot.c:reboot_init",
        "arch/x86/kernel/apic/apic.c:apic_is_clustered_box",
        "arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe",
        "drivers/pci/pci.c:pci_bridge_d3_possible",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_init",
        "drivers/acpi/blacklist.c:acpi_blacklisted",
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/bus.c:acpi_early_init",
        "drivers/acpi/resource.c:acpi_dev_get_irqresource",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/pci_irq.c:do_prt_fixups",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/power.c:acpi_turn_off_unused_power_resources",
        "drivers/acpi/x86/utils.c:acpi_proc_quirk_mwait_check",
        "drivers/acpi/x86/utils.c:acpi_device_override_status",
        "drivers/acpi/ac.c:acpi_ac_init",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/acpi/battery.c:acpi_battery_init_async",
        "drivers/iommu/amd/quirks.c:amd_iommu_apply_ivrs_quirks",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_pci_device_suspend",
        "drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci",
        "drivers/input/serio/i8042.c:i8042_pnp_init",
        "drivers/input/keyboard/atkbd.c:atkbd_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/firmware/efi/sysfb_efi.c:sysfb_apply_efi_quirks",
        "drivers/firmware/efi/sysfb_efi.c:sysfb_apply_efi_quirks",
        "arch/x86/pci/fixup.c:pci_fixup_msi_k8t_onboard_sound",
        "arch/x86/pci/acpi.c:pci_acpi_crs_quirks",
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/common.c:dmi_check_skip_isa_align",
        "arch/x86/pci/common.c:dmi_check_pciprobe",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594070224,
      "name": "dmi_check_system",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int dmi_check_system(const struct dmi_system_id * list)
```

```json
{
  "name": "dmi_check_system",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501484304,
      "name": "dmi_check_system",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:849",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init",
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/ac.c:acpi_ac_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_init",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/acpi/battery.c:acpi_battery_init_async",
        "drivers/input/keyboard/atkbd.c:atkbd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501484304,
      "name": "dmi_check_system",
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
int dmi_check_system(const struct dmi_system_id * list)
```

```json
{
  "name": "dmi_check_system",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234024340,
      "name": "dmi_check_system",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:849",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init",
        "drivers/input/keyboard/atkbd.c:atkbd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234024340,
      "name": "dmi_check_system",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "dmi_check_system",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dmi_check_system",
      "external": false,
      "loc": "include/linux/dmi.h:119",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dmi_check_system",
      "external": false,
      "loc": "include/linux/dmi.h:119",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dmi_check_system",
      "external": false,
      "loc": "include/linux/dmi.h:119",
      "file": "drivers/input/keyboard/atkbd.c",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "dmi_check_system",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dmi_check_system",
      "external": false,
      "loc": "include/linux/dmi.h:119",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dmi_check_system",
      "external": false,
      "loc": "include/linux/dmi.h:119",
      "file": "drivers/pci/pcie/portdrv_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dmi_check_system",
      "external": false,
      "loc": "include/linux/dmi.h:119",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dmi_check_system",
      "external": false,
      "loc": "include/linux/dmi.h:119",
      "file": "drivers/input/keyboard/atkbd.c",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int dmi_check_system(const struct dmi_system_id * list)
```

```json
{
  "name": "dmi_check_system",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587795120,
      "name": "dmi_check_system",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:849",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/io_delay.c:io_delay_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_table_init",
        "arch/x86/kernel/reboot.c:reboot_init",
        "arch/x86/kernel/apic/apic.c:apic_is_clustered_box",
        "arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks",
        "arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks",
        "arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi",
        "arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init",
        "drivers/acpi/blacklist.c:acpi_blacklisted",
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/bus.c:acpi_early_init",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/iommu/amd_iommu_quirks.c:amd_iommu_apply_ivrs_quirks",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_pci_device_suspend",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/keyboard/atkbd.c:atkbd_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "arch/x86/pci/acpi.c:pci_acpi_crs_quirks",
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/common.c:dmi_check_skip_isa_align",
        "arch/x86/pci/common.c:dmi_check_pciprobe",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587795120,
      "name": "dmi_check_system",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int dmi_check_system(const struct dmi_system_id * list)
```

```json
{
  "name": "dmi_check_system",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587498544,
      "name": "dmi_check_system",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:849",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/io_delay.c:io_delay_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_table_init",
        "arch/x86/kernel/reboot.c:reboot_init",
        "arch/x86/kernel/apic/apic.c:apic_is_clustered_box",
        "arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks",
        "arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks",
        "arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi",
        "arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init",
        "drivers/acpi/blacklist.c:acpi_blacklisted",
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/bus.c:acpi_early_init",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/iommu/amd_iommu_quirks.c:amd_iommu_apply_ivrs_quirks",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_pci_device_suspend",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/keyboard/atkbd.c:atkbd_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "arch/x86/pci/acpi.c:pci_acpi_crs_quirks",
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/common.c:dmi_check_skip_isa_align",
        "arch/x86/pci/common.c:dmi_check_pciprobe",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587498544,
      "name": "dmi_check_system",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int dmi_check_system(const struct dmi_system_id * list)
```

```json
{
  "name": "dmi_check_system",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588131216,
      "name": "dmi_check_system",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:849",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/io_delay.c:io_delay_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_table_init",
        "arch/x86/kernel/reboot.c:reboot_init",
        "arch/x86/kernel/apic/apic.c:apic_is_clustered_box",
        "arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks",
        "arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks",
        "arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi",
        "arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init",
        "drivers/acpi/blacklist.c:acpi_blacklisted",
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/bus.c:acpi_early_init",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/acpi/ac.c:acpi_ac_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/acpi/battery.c:acpi_battery_init_async",
        "drivers/iommu/amd_iommu_quirks.c:amd_iommu_apply_ivrs_quirks",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_pci_device_suspend",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/keyboard/atkbd.c:atkbd_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "arch/x86/pci/acpi.c:pci_acpi_crs_quirks",
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/common.c:dmi_check_skip_isa_align",
        "arch/x86/pci/common.c:dmi_check_pciprobe",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588131216,
      "name": "dmi_check_system",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int dmi_check_system(const struct dmi_system_id * list)
```

```json
{
  "name": "dmi_check_system",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588248752,
      "name": "dmi_check_system",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:849",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/io_delay.c:io_delay_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_table_init",
        "arch/x86/kernel/reboot.c:reboot_init",
        "arch/x86/kernel/apic/apic.c:apic_is_clustered_box",
        "arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks",
        "arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks",
        "arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi",
        "arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init",
        "drivers/acpi/blacklist.c:acpi_blacklisted",
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/bus.c:acpi_early_init",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/acpi/ac.c:acpi_ac_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/acpi/battery.c:acpi_battery_init_async",
        "drivers/iommu/amd_iommu_quirks.c:amd_iommu_apply_ivrs_quirks",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_pci_device_suspend",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/keyboard/atkbd.c:atkbd_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "arch/x86/pci/acpi.c:pci_acpi_crs_quirks",
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/common.c:dmi_check_skip_isa_align",
        "arch/x86/pci/common.c:dmi_check_pciprobe",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588248752,
      "name": "dmi_check_system",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int dmi_check_system(const struct dmi_system_id * list)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int dmi_check_system(const struct dmi_system_id * list)
```
</details>
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
