# Function: <code>inb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578993997,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/xen/platform-pci-unplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579054644,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/x86_init.c:default_get_nmi_reason"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579055149,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/i8259.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/i8259.c:i8259A_irq_pending",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:probe_8259A"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579063824,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579074313,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:native_calibrate_tsc",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076573,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_set_rtc_mmss",
        "arch/x86/kernel/rtc.c:mach_set_rtc_mmss",
        "arch/x86/kernel/rtc.c:mach_set_rtc_mmss",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595025233,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger",
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579174351,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595029238,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595032965,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/mpparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595041873,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579245793,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/early_printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/early_printk.c:io_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580131662,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "kernel/debug/kdb/kdb_keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583049410,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "lib/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iomap.c:ioread8"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583281105,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_resource_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583422158,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_startup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583537808,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583576182,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:advance_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583745459,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_idle_do_entry",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584111282,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:hub6_serial_in",
        "drivers/tty/serial/8250/8250_port.c:io_serial_in",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584129253,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:kt_serial_in",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595259206,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584158095,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584988856,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585333275,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585426297,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585548677,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_wait_write",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585624344,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586146700,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/pci/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/direct.c:pci_conf1_read",
        "arch/x86/pci/direct.c:pci_conf2_read",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586154824,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586156657,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/pci/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/irq.c:pirq_serverworks_get",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_pico_set",
        "arch/x86/pci/irq.c:elcr_set_level_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586162851,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/pci/early.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:early_dump_pci_devices"
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
  "name": "inb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578990605,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/xen/platform-pci-unplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579051012,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/x86_init.c:default_get_nmi_reason"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579052122,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/i8259.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/i8259.c:probe_8259A",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579060240,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579071410,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579073343,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595190120,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger",
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579174825,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595195019,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595198668,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/mpparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595207749,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579245335,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/early_printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/early_printk.c:io_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580166317,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "kernel/debug/kdb/kdb_keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583293468,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/lib/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/kaslr.c:kaslr_get_random_long",
        "arch/x86/lib/kaslr.c:kaslr_get_random_long",
        "arch/x86/lib/kaslr.c:kaslr_get_random_long"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583343477,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "lib/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iomap.c:ioread8"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583597689,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583742171,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_startup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583858773,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583900057,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:advance_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584074130,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_idle_do_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584451827,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:io_serial_in",
        "drivers/tty/serial/8250/8250_port.c:hub6_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584465282,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584466126,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:kt_serial_in",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595440639,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584495371,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585356856,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585729659,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585822381,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585942859,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_wait_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586020573,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595516802,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/pci/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_conf2_read",
        "arch/x86/pci/direct.c:pci_conf1_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586567720,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586569717,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/pci/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/irq.c:pirq_pico_set",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_serverworks_get",
        "arch/x86/pci/irq.c:elcr_set_level_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586576926,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/pci/early.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:early_dump_pci_devices"
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
  "name": "inb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578992445,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/xen/platform-pci-unplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579050116,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/x86_init.c:default_get_nmi_reason"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579051210,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/i8259.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/i8259.c:probe_8259A",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579059280,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579070786,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579072792,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595433116,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger",
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579185177,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595437981,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595441557,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/mpparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595450636,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579257799,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/kernel/early_printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/early_printk.c:io_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580206733,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "kernel/debug/kdb/kdb_keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583412124,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/lib/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/kaslr.c:kaslr_get_random_long",
        "arch/x86/lib/kaslr.c:kaslr_get_random_long",
        "arch/x86/lib/kaslr.c:kaslr_get_random_long"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583468853,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "lib/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iomap.c:ioread8"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583734873,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583881704,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_startup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583997797,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584040514,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:advance_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584216602,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_idle_do_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584634113,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:io_serial_in",
        "drivers/tty/serial/8250/8250_port.c:hub6_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584647500,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584648718,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:kt_serial_in",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595692991,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584677483,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585557720,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585918251,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586011085,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586131307,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_wait_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586217181,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595772870,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/pci/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_conf2_read",
        "arch/x86/pci/direct.c:pci_conf1_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586749272,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586751269,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/pci/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/irq.c:pirq_pico_set",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_serverworks_get",
        "arch/x86/pci/irq.c:elcr_set_level_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586758494,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:316",
      "file": "arch/x86/pci/early.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:early_dump_pci_devices"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578957646,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "arch/x86/xen/platform-pci-unplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579042500,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/x86_init.c:default_get_nmi_reason"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579043594,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "arch/x86/kernel/i8259.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/i8259.c:probe_8259A",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579051281,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579062748,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579064776,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596353690,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger",
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579183992,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596358662,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596362348,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "arch/x86/kernel/mpparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596371519,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579253575,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "arch/x86/kernel/early_printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/early_printk.c:io_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580214781,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "kernel/debug/kdb/kdb_keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583491093,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "lib/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iomap.c:ioread8"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583777245,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583930856,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_startup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584046173,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584101751,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_space_handler",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584287621,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584723783,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:io_serial_in",
        "drivers/tty/serial/8250/8250_port.c:hub6_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584730554,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584731790,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:kt_serial_in",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596617585,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584759627,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585641576,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586002409,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586093492,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586219677,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_wait_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586306302,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596703852,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "arch/x86/pci/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_conf2_read",
        "arch/x86/pci/direct.c:pci_conf1_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586876625,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586878565,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "arch/x86/pci/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/irq.c:pirq_pico_set",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_serverworks_get",
        "arch/x86/pci/irq.c:elcr_set_level_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586885372,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "arch/x86/pci/early.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:early_dump_pci_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588269372,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:340",
      "file": "arch/x86/lib/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/kaslr.c:kaslr_get_random_long",
        "arch/x86/lib/kaslr.c:kaslr_get_random_long",
        "arch/x86/lib/kaslr.c:kaslr_get_random_long"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578960942,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "arch/x86/xen/platform-pci-unplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579051604,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/x86_init.c:default_get_nmi_reason"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579052714,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "arch/x86/kernel/i8259.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/i8259.c:probe_8259A",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579060289,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579071788,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579073768,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602671828,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger",
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579199605,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602676803,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602680263,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "arch/x86/kernel/mpparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602689885,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579270327,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "arch/x86/kernel/early_printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/early_printk.c:io_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580266125,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "kernel/debug/kdb/kdb_keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583672137,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "lib/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iomap.c:ioread8"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584037357,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584193548,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_startup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584310685,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584373207,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_space_handler",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584684949,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585138045,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:io_serial_in",
        "drivers/tty/serial/8250/8250_port.c:hub6_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585145489,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585146782,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:kt_serial_in",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585155939,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585179995,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586073304,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586446505,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586537892,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586683021,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_wait_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586769790,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603034546,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "arch/x86/pci/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_conf2_read",
        "arch/x86/pci/direct.c:pci_conf1_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587364721,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587367189,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "arch/x86/pci/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/irq.c:pirq_pico_set",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_serverworks_get",
        "arch/x86/pci/irq.c:elcr_set_level_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587374060,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "arch/x86/pci/early.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:early_dump_pci_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588825068,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:348",
      "file": "arch/x86/lib/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/kaslr.c:kaslr_get_random_long",
        "arch/x86/lib/kaslr.c:kaslr_get_random_long",
        "arch/x86/lib/kaslr.c:kaslr_get_random_long"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578963505,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "arch/x86/xen/platform-pci-unplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579056496,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/x86_init.c:default_get_nmi_reason"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579057610,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "arch/x86/kernel/i8259.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/i8259.c:probe_8259A",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579064409,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579075982,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579078120,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602823096,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "arch/x86/kernel/i8237.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/i8237.c:i8237A_init_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602843170,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger",
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579211407,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602847918,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/early-quirks.c:ati_bugs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602851984,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "arch/x86/kernel/mpparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602859895,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579281648,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "arch/x86/kernel/early_printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/early_printk.c:io_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580326605,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "kernel/debug/kdb/kdb_keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583889910,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "lib/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iomap.c:ioread8"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584234513,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584413429,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_startup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584530898,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584595881,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_space_handler",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584911208,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585370305,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:io_serial_in",
        "drivers/tty/serial/8250/8250_port.c:hub6_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585379646,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585380949,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:kt_serial_in",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585390064,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585415841,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586321253,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586711146,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586800905,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603167520,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_wait_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587042372,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603207326,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "arch/x86/pci/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_conf2_read",
        "arch/x86/pci/direct.c:pci_conf1_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587668417,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587670965,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "arch/x86/pci/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/irq.c:pirq_pico_set",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_serverworks_get",
        "arch/x86/pci/irq.c:elcr_set_level_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587677929,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "arch/x86/pci/early.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:early_dump_pci_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589203228,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:333",
      "file": "arch/x86/lib/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/kaslr.c:kaslr_get_random_long",
        "arch/x86/lib/kaslr.c:kaslr_get_random_long",
        "arch/x86/lib/kaslr.c:kaslr_get_random_long"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578962618,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "arch/x86/xen/platform-pci-unplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579061456,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/x86_init.c:default_get_nmi_reason"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579062554,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "arch/x86/kernel/i8259.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/i8259.c:probe_8259A",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579068985,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579078830,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579082744,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604618235,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "arch/x86/kernel/i8237.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/i8237.c:i8237A_init_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604639624,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger",
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579235229,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604644688,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/early-quirks.c:ati_bugs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604648885,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "arch/x86/kernel/mpparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604656832,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579261555,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:irq_trigger"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305600,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "arch/x86/kernel/early_printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/early_printk.c:io_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580379405,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "kernel/debug/kdb/kdb_keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583974150,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "lib/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iomap.c:ioread8"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584324209,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584509797,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_startup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584628226,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584691817,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_space_handler",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585015096,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585493971,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:io_serial_in",
        "drivers/tty/serial/8250/8250_port.c:hub6_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585503086,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585504389,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:kt_serial_in",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585513538,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585539442,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586462805,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586868874,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586958873,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604975156,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_wait_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587202292,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604985787,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/eisa/eisa-bus.c:eisa_init_device",
        "drivers/eisa/eisa-bus.c:eisa_init_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605017776,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "arch/x86/pci/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_conf2_read",
        "arch/x86/pci/direct.c:pci_conf1_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587800241,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587802245,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "arch/x86/pci/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/irq.c:pirq_pico_set",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_serverworks_get",
        "arch/x86/pci/irq.c:elcr_set_level_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587808886,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "arch/x86/pci/early.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589444812,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:342",
      "file": "arch/x86/lib/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/kaslr.c:kaslr_get_random_long",
        "arch/x86/lib/kaslr.c:kaslr_get_random_long",
        "arch/x86/lib/kaslr.c:kaslr_get_random_long"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578969594,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/xen/platform-pci-unplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579069488,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/x86_init.c:default_get_nmi_reason"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579070586,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/i8259.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/i8259.c:probe_8259A",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579077275,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579088450,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579092438,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604714430,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/i8237.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/i8237.c:i8237A_init_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604737162,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger",
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579248600,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604742318,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/early-quirks.c:ati_bugs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604746371,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/mpparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604754778,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579275808,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:irq_trigger"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322048,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/early_printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/early_printk.c:io_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580432125,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "kernel/debug/kdb/kdb_keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584156258,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "lib/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iomap.c:ioread8"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584519057,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584708513,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_startup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584827874,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584892467,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_space_handler",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585218564,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_idle_do_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585715400,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:io_serial_in",
        "drivers/tty/serial/8250/8250_port.c:hub6_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585721783,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585722613,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:kt_serial_in",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585732376,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585759528,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586707960,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587127450,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587217423,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605083107,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_wait_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587467558,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605097546,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/eisa/eisa-bus.c:eisa_init_device",
        "drivers/eisa/eisa-bus.c:eisa_init_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605131008,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/pci/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_conf2_read",
        "arch/x86/pci/direct.c:pci_conf1_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588104849,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588107701,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/pci/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/irq.c:pirq_pico_set",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_serverworks_get",
        "arch/x86/pci/irq.c:elcr_set_level_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588114372,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/pci/early.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589902990,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/lib/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/kaslr.c:kaslr_get_random_long",
        "arch/x86/lib/kaslr.c:kaslr_get_random_long",
        "arch/x86/lib/kaslr.c:kaslr_get_random_long"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578972026,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/xen/platform-pci-unplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579071488,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/x86_init.c:default_get_nmi_reason"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579072586,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/i8259.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/i8259.c:probe_8259A",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579079275,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579090450,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579094422,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604726732,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/i8237.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/i8237.c:i8237A_init_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604750553,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger",
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579250760,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604755712,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/early-quirks.c:ati_bugs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604759770,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/mpparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604768282,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579278240,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:irq_trigger"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326096,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/early_printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/early_printk.c:io_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604839510,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580480877,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "kernel/debug/kdb/kdb_keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584290002,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "lib/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iomap.c:ioread8"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584654273,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584844593,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_startup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584963682,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585028211,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_space_handler",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585354897,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_idle_do_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585856024,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:io_serial_in",
        "drivers/tty/serial/8250/8250_port.c:hub6_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585863143,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585864053,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:kt_serial_in",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585874440,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585901870,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586854584,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587327834,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587417695,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605122590,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_wait_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587670678,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605136975,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/eisa/eisa-bus.c:eisa_init_device",
        "drivers/eisa/eisa-bus.c:eisa_init_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605171351,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/pci/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_conf2_read",
        "arch/x86/pci/direct.c:pci_conf1_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588310545,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588313397,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/pci/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/irq.c:pirq_pico_set",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_serverworks_get",
        "arch/x86/pci/irq.c:elcr_set_level_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588320068,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/pci/early.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590128974,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/lib/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/kaslr.c:kaslr_get_random_long",
        "arch/x86/lib/kaslr.c:kaslr_get_random_long",
        "arch/x86/lib/kaslr.c:kaslr_get_random_long"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578981770,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/xen/platform-pci-unplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579079344,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/x86_init.c:default_get_nmi_reason"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579080442,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/i8259.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/i8259.c:probe_8259A",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579090348,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579102155,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:pit_calibrate_tsc",
        "arch/x86/kernel/tsc.c:pit_calibrate_tsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579106326,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609072312,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/i8237.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/i8237.c:i8237A_init_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609098020,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger",
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579275584,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609102274,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/early-quirks.c:ati_bugs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609106042,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/mpparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609114116,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_PIC",
        "arch/x86/kernel/apic/vector.c:print_PIC",
        "arch/x86/kernel/apic/vector.c:print_PIC",
        "arch/x86/kernel/apic/vector.c:print_PIC",
        "arch/x86/kernel/apic/vector.c:print_PIC",
        "arch/x86/kernel/apic/vector.c:print_PIC",
        "arch/x86/kernel/apic/vector.c:print_PIC",
        "arch/x86/kernel/apic/vector.c:print_PIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309508,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:irq_trigger"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579355296,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/early_printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/early_printk.c:io_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609174904,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580565549,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "kernel/debug/kdb/kdb_keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584700274,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "lib/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iomap.c:ioread8"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585133534,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/lib/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/kaslr.c:kaslr_get_random_long",
        "arch/x86/lib/kaslr.c:kaslr_get_random_long",
        "arch/x86/lib/kaslr.c:kaslr_get_random_long"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585338686,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585544791,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_adjust_height",
        "drivers/video/console/vgacon.c:vgacon_adjust_height",
        "drivers/video/console/vgacon.c:vgacon_startup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585658866,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585732056,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_space_handler",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586062437,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_idle_bm_check",
        "drivers/acpi/processor_idle.c:acpi_idle_bm_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586581511,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_irq",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_irq",
        "drivers/tty/serial/8250/8250_port.c:io_serial_in",
        "drivers/tty/serial/8250/8250_port.c:hub6_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586597056,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586598645,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:kt_serial_in",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586609416,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586640145,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587663112,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588184025,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588272988,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_show_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588436206,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_controller_init",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_kbd_write",
        "drivers/input/serio/i8042.c:i8042_command",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588537878,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609408538,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/eisa/eisa-bus.c:eisa_init_device",
        "drivers/eisa/eisa-bus.c:decode_eisa_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609455107,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/pci/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_conf2_read",
        "arch/x86/pci/direct.c:pci_conf1_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591129873,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591133269,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/pci/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/irq.c:pirq_pico_set",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_serverworks_get",
        "arch/x86/pci/irq.c:elcr_set_level_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591140387,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/pci/early.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578983754,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/xen/platform-pci-unplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579081584,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/x86_init.c:default_get_nmi_reason"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579082586,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/i8259.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/i8259.c:probe_8259A",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579092252,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579102331,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:pit_calibrate_tsc",
        "arch/x86/kernel/tsc.c:pit_calibrate_tsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579105942,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612135649,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/i8237.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/i8237.c:i8237A_init_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612162882,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger",
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579282880,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612167190,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/early-quirks.c:ati_bugs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612170949,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/mpparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612178882,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_PIC",
        "arch/x86/kernel/apic/vector.c:print_PIC",
        "arch/x86/kernel/apic/vector.c:print_PIC",
        "arch/x86/kernel/apic/vector.c:print_PIC",
        "arch/x86/kernel/apic/vector.c:print_PIC",
        "arch/x86/kernel/apic/vector.c:print_PIC",
        "arch/x86/kernel/apic/vector.c:print_PIC",
        "arch/x86/kernel/apic/vector.c:print_PIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579315187,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:irq_is_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579354864,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/early_printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/early_printk.c:io_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612240338,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580553613,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "kernel/debug/kdb/kdb_keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584813570,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "lib/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iomap.c:ioread8"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585285038,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/lib/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/kaslr.c:kaslr_get_random_long",
        "arch/x86/lib/kaslr.c:kaslr_get_random_long",
        "arch/x86/lib/kaslr.c:kaslr_get_random_long"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585491934,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585679079,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_adjust_height",
        "drivers/video/console/vgacon.c:vgacon_adjust_height",
        "drivers/video/console/vgacon.c:vgacon_startup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585784498,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585854232,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_space_handler",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586185009,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_idle_do_entry",
        "drivers/acpi/processor_idle.c:acpi_idle_bm_check",
        "drivers/acpi/processor_idle.c:acpi_idle_bm_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586692183,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_irq",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_irq",
        "drivers/tty/serial/8250/8250_port.c:io_serial_in",
        "drivers/tty/serial/8250/8250_port.c:hub6_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586707424,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586708981,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:kt_serial_in",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_clock",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586719336,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586749162,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587724056,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588220857,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588308028,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_show_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588467790,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_controller_init",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_kbd_write",
        "drivers/input/serio/i8042.c:i8042_command",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588561222,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612482038,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/eisa/eisa-bus.c:eisa_init_device",
        "drivers/eisa/eisa-bus.c:decode_eisa_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612531085,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/pci/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_conf2_read",
        "arch/x86/pci/direct.c:pci_conf1_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591216033,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591218277,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/pci/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/irq.c:pirq_pico_set",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_serverworks_get",
        "arch/x86/pci/irq.c:elcr_set_level_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591224611,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/pci/early.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578992858,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/xen/platform-pci-unplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579088448,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/x86_init.c:default_get_nmi_reason"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579089450,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/i8259.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/i8259.c:probe_8259A",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579098729,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579109109,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579112502,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614275459,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/i8237.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/i8237.c:i8237A_init_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614302236,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger",
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579285346,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614307518,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/early-quirks.c:ati_bugs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614311246,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/mpparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614319333,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_PIC",
        "arch/x86/kernel/apic/vector.c:print_PIC",
        "arch/x86/kernel/apic/vector.c:print_PIC",
        "arch/x86/kernel/apic/vector.c:print_PIC",
        "arch/x86/kernel/apic/vector.c:print_PIC",
        "arch/x86/kernel/apic/vector.c:print_PIC",
        "arch/x86/kernel/apic/vector.c:print_PIC",
        "arch/x86/kernel/apic/vector.c:print_PIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579317046,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:irq_is_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579359392,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/early_printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/early_printk.c:io_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614380619,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580556781,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "kernel/debug/kdb/kdb_keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584858130,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "lib/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iomap.c:ioread8"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585168798,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/lib/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/kaslr.c:kaslr_get_random_long",
        "arch/x86/lib/kaslr.c:kaslr_get_random_long",
        "arch/x86/lib/kaslr.c:kaslr_get_random_long"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585371726,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585560183,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_adjust_height",
        "drivers/video/console/vgacon.c:vgacon_adjust_height",
        "drivers/video/console/vgacon.c:vgacon_startup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585665010,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585732904,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_space_handler",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586060459,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_idle_do_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586584663,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_irq",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_irq",
        "drivers/tty/serial/8250/8250_port.c:io_serial_in",
        "drivers/tty/serial/8250/8250_port.c:hub6_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586590668,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586592549,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:kt_serial_in",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586602856,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586632374,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587603192,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588104121,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588190795,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_show_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614614692,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_kbd_write",
        "drivers/input/serio/i8042.c:i8042_command",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588444534,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614624121,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/eisa/eisa-bus.c:eisa_init_device",
        "drivers/eisa/eisa-bus.c:eisa_init_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614673797,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/pci/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_conf2_read",
        "arch/x86/pci/direct.c:pci_conf1_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591165409,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591167637,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/pci/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/irq.c:pirq_pico_set",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_serverworks_get",
        "arch/x86/pci/irq.c:elcr_set_level_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591173845,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/pci/early.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579010219,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/xen/platform-pci-unplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111584,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/x86_init.c:default_get_nmi_reason"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579112730,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/i8259.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/i8259.c:probe_8259A",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579122667,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579133925,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate",
        "arch/x86/kernel/tsc.c:quick_pit_calibrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579137733,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615198084,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/i8237.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/i8237.c:i8237A_init_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615229284,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger",
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329104,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615234375,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/early-quirks.c:ati_bugs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615239334,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/mpparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615247982,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_PIC",
        "arch/x86/kernel/apic/vector.c:print_PIC",
        "arch/x86/kernel/apic/vector.c:print_PIC",
        "arch/x86/kernel/apic/vector.c:print_PIC",
        "arch/x86/kernel/apic/vector.c:print_PIC",
        "arch/x86/kernel/apic/vector.c:print_PIC",
        "arch/x86/kernel/apic/vector.c:print_PIC",
        "arch/x86/kernel/apic/vector.c:print_PIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579367278,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:irq_is_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579419344,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/kernel/early_printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/early_printk.c:io_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615313261,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580726701,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "kernel/debug/kdb/kdb_keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585279586,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "lib/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iomap.c:ioread8"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585622494,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/lib/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/kaslr.c:kaslr_get_random_long",
        "arch/x86/lib/kaslr.c:kaslr_get_random_long",
        "arch/x86/lib/kaslr.c:kaslr_get_random_long"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585831914,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586031799,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_adjust_height",
        "drivers/video/console/vgacon.c:vgacon_adjust_height",
        "drivers/video/console/vgacon.c:vgacon_startup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586144130,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_read_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586214833,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_space_handler",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586553099,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_idle_do_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587125431,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_irq",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_irq",
        "drivers/tty/serial/8250/8250_port.c:io_serial_in",
        "drivers/tty/serial/8250/8250_port.c:hub6_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587131930,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587134213,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:kt_serial_in",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587145887,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587179590,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588187624,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588737161,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588831467,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_show_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589009369,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_controller_init",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_kbd_write",
        "drivers/input/serio/i8042.c:i8042_command",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589111654,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615580397,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/eisa/eisa-bus.c:eisa_init_device",
        "drivers/eisa/eisa-bus.c:eisa_init_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615634185,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/pci/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_conf2_read",
        "arch/x86/pci/direct.c:pci_conf1_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592017265,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592019893,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/pci/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/irq.c:pirq_pico_set",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_serverworks_get",
        "arch/x86/pci/irq.c:pirq_esc_get",
        "arch/x86/pci/irq.c:pirq_finali_lvl",
        "arch/x86/pci/irq.c:pirq_finali_set",
        "arch/x86/pci/irq.c:pirq_finali_get",
        "arch/x86/pci/irq.c:elcr_set_level_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592027365,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:334",
      "file": "arch/x86/pci/early.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap"
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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
u8 inb(long unsigned int port)
```

```json
{
  "name": "inb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055282592372,
      "name": "inb",
      "external": false,
      "loc": "arch/powerpc/include/asm/io-defs.h:23",
      "file": "arch/powerpc/kernel/udbg_16550.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/udbg_16550.c:udbg_uart_in_pio"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282921860,
      "name": "inb",
      "external": false,
      "loc": "arch/powerpc/include/asm/io-defs.h:23",
      "file": "arch/powerpc/sysdev/i8259.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/sysdev/i8259.c:i8259_mask_and_ack_irq",
        "arch/powerpc/sysdev/i8259.c:i8259_mask_and_ack_irq",
        "arch/powerpc/sysdev/i8259.c:i8259_mask_and_ack_irq",
        "arch/powerpc/sysdev/i8259.c:i8259_mask_and_ack_irq",
        "arch/powerpc/sysdev/i8259.c:i8259_irq",
        "arch/powerpc/sysdev/i8259.c:i8259_irq",
        "arch/powerpc/sysdev/i8259.c:i8259_irq",
        "arch/powerpc/sysdev/i8259.c:i8259_irq",
        "arch/powerpc/sysdev/i8259.c:i8259_irq",
        "arch/powerpc/sysdev/i8259.c:i8259_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284797192,
      "name": "inb",
      "external": false,
      "loc": "arch/powerpc/include/asm/io-defs.h:23",
      "file": "kernel/debug/kdb/kdb_keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290444348,
      "name": "inb",
      "external": false,
      "loc": "arch/powerpc/include/asm/io-defs.h:23",
      "file": "lib/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055290992440,
      "name": "inb",
      "external": false,
      "loc": "arch/powerpc/include/asm/io-defs.h:23",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291194692,
      "name": "inb",
      "external": false,
      "loc": "arch/powerpc/include/asm/io-defs.h:23",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_doresize",
        "drivers/video/console/vgacon.c:vgacon_doresize",
        "drivers/video/console/vgacon.c:vgacon_doresize",
        "drivers/video/console/vgacon.c:vgacon_doresize",
        "drivers/video/console/vgacon.c:vgacon_doresize",
        "drivers/video/console/vgacon.c:vgacon_doresize",
        "drivers/video/console/vgacon.c:vgacon_doresize",
        "drivers/video/console/vgacon.c:vgacon_doresize",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291812136,
      "name": "inb",
      "external": false,
      "loc": "arch/powerpc/include/asm/io-defs.h:23",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:io_serial_in",
        "drivers/tty/serial/8250/8250_port.c:io_serial_in",
        "drivers/tty/serial/8250/8250_port.c:hub6_serial_in",
        "drivers/tty/serial/8250/8250_port.c:hub6_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291831500,
      "name": "inb",
      "external": false,
      "loc": "arch/powerpc/include/asm/io-defs.h:23",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:kt_serial_in",
        "drivers/tty/serial/8250/8250_pci.c:kt_serial_in",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqmcr",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqmcr",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqmcr",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqmcr",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqopr",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqopr",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqopr",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqopr",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqopr",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqopr",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqopr",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqopr",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291840160,
      "name": "inb",
      "external": false,
      "loc": "arch/powerpc/include/asm/io-defs.h:23",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_in"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291873380,
      "name": "inb",
      "external": false,
      "loc": "arch/powerpc/include/asm/io-defs.h:23",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_port"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293147932,
      "name": "inb",
      "external": false,
      "loc": "arch/powerpc/include/asm/io-defs.h:23",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293800648,
      "name": "inb",
      "external": false,
      "loc": "arch/powerpc/include/asm/io-defs.h:23",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293948712,
      "name": "inb",
      "external": false,
      "loc": "arch/powerpc/include/asm/io-defs.h:23",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_show_status"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294159016,
      "name": "inb",
      "external": false,
      "loc": "arch/powerpc/include/asm/io-defs.h:23",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_wait_write",
        "drivers/input/serio/i8042.c:i8042_wait_write"
      ],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq"
      ]
    },
    {
      "addr": 13835058055294283844,
      "name": "inb",
      "external": false,
      "loc": "arch/powerpc/include/asm/io-defs.h:23",
      "file": "drivers/rtc/rtc-mc146818-lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294156944,
      "name": "inb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578972378,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/xen/platform-pci-unplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579071840,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/x86_init.c:default_get_nmi_reason"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579072938,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/i8259.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/i8259.c:probe_8259A",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579079627,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579090802,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579094806,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604653035,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/i8237.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/i8237.c:i8237A_init_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604676856,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger",
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579249464,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604681996,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/early-quirks.c:ati_bugs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604686049,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/mpparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604694561,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579276944,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:irq_trigger"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322000,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/early_printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/early_printk.c:io_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580449677,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "kernel/debug/kdb/kdb_keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584258738,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "lib/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iomap.c:ioread8"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584604753,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584795777,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_startup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584913858,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584970595,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_space_handler",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585156225,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_idle_do_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585617032,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:io_serial_in",
        "drivers/tty/serial/8250/8250_port.c:hub6_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585624151,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585625061,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:kt_serial_in",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585635432,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585662862,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586613112,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587033914,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587123775,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605019581,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_wait_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587354438,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605029987,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/eisa/eisa-bus.c:eisa_init_device",
        "drivers/eisa/eisa-bus.c:eisa_init_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605060006,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/pci/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_conf2_read",
        "arch/x86/pci/direct.c:pci_conf1_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587914193,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587917045,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/pci/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/irq.c:pirq_pico_set",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_serverworks_get",
        "arch/x86/pci/irq.c:elcr_set_level_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587923716,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/pci/early.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589731230,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/lib/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/kaslr.c:kaslr_get_random_long",
        "arch/x86/lib/kaslr.c:kaslr_get_random_long",
        "arch/x86/lib/kaslr.c:kaslr_get_random_long"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579004736,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/x86_init.c:default_get_nmi_reason"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579005834,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/i8259.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/i8259.c:probe_8259A",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579012315,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579023301,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579026854,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604620670,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/i8237.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/i8237.c:i8237A_init_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604644410,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger",
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579184904,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604649550,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/early-quirks.c:ati_bugs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604653603,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/mpparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604662057,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579212272,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:irq_trigger"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256512,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/early_printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/early_printk.c:io_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580396749,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "kernel/debug/kdb/kdb_keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584193938,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "lib/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iomap.c:ioread8"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584534561,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584726561,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_startup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584819794,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584879395,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_space_handler",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585070575,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_idle_do_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585482088,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:io_serial_in",
        "drivers/tty/serial/8250/8250_port.c:hub6_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585489207,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585490117,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:kt_serial_in",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585500504,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585522782,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586481624,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586894442,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604983844,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_wait_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587122710,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604995916,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/eisa/eisa-bus.c:eisa_init_device",
        "drivers/eisa/eisa-bus.c:eisa_init_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605028772,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/pci/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_conf2_read",
        "arch/x86/pci/direct.c:pci_conf1_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587630337,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587633173,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/pci/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/irq.c:pirq_pico_set",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_serverworks_get",
        "arch/x86/pci/irq.c:elcr_set_level_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587639572,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/pci/early.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589456910,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/lib/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/kaslr.c:kaslr_get_random_long",
        "arch/x86/lib/kaslr.c:kaslr_get_random_long",
        "arch/x86/lib/kaslr.c:kaslr_get_random_long"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578971962,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/xen/platform-pci-unplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579071424,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/x86_init.c:default_get_nmi_reason"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579072522,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/i8259.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/i8259.c:probe_8259A",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579079211,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579090386,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579094358,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604730798,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/i8237.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/i8237.c:i8237A_init_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604754421,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger",
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579250664,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604759580,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/early-quirks.c:ati_bugs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604763633,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/mpparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604772145,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579278144,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:irq_trigger"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321920,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/early_printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/early_printk.c:io_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580440925,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "kernel/debug/kdb/kdb_keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584242498,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "lib/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iomap.c:ioread8"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584604433,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584797201,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_startup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584915266,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584979795,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_space_handler",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585306481,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_idle_do_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585806424,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:io_serial_in",
        "drivers/tty/serial/8250/8250_port.c:hub6_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585813543,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585814453,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:kt_serial_in",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585824840,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585852270,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586809144,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587282394,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587372255,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605100981,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_wait_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587621926,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605114011,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/eisa/eisa-bus.c:eisa_init_device",
        "drivers/eisa/eisa-bus.c:eisa_init_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605147554,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/pci/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_conf2_read",
        "arch/x86/pci/direct.c:pci_conf1_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588247601,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588250453,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/pci/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/irq.c:pirq_pico_set",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_serverworks_get",
        "arch/x86/pci/irq.c:elcr_set_level_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588257124,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/pci/early.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590174606,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/lib/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/kaslr.c:kaslr_get_random_long",
        "arch/x86/lib/kaslr.c:kaslr_get_random_long",
        "arch/x86/lib/kaslr.c:kaslr_get_random_long"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578972554,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/xen/platform-pci-unplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579075520,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/x86_init.c:default_get_nmi_reason"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076618,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/i8259.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/i8259.c:probe_8259A",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:i8259A_suspend",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending",
        "arch/x86/kernel/i8259.c:i8259A_irq_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579083307,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet",
        "arch/x86/kernel/quirks.c:ati_force_enable_hpet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579094562,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579098598,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/rtc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "arch/x86/kernel/rtc.c:mach_get_cmos_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604730844,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/i8237.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/i8237.c:i8237A_init_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604754652,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger",
        "arch/x86/kernel/acpi/boot.c:acpi_pic_sci_set_trigger"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256232,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604759811,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/early-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/early-quirks.c:ati_bugs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604763890,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/mpparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604772402,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "arch/x86/kernel/apic/vector.c:print_ICs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579284160,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:irq_trigger"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579330208,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/kernel/early_printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/early_printk.c:io_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604843667,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_hubless",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580496557,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "kernel/debug/kdb/kdb_keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584347330,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "lib/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iomap.c:ioread8"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584712129,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584902337,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_startup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585021346,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585085971,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_space_handler",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585412625,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_idle_do_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585914088,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:io_serial_in",
        "drivers/tty/serial/8250/8250_port.c:hub6_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585921159,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585922069,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:kt_serial_in",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585932456,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585960190,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586915240,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587389162,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587480495,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605126784,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_aux_test_irq",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_wait_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587729766,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_nvram_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605141169,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/eisa/eisa-bus.c:eisa_init_device",
        "drivers/eisa/eisa-bus.c:eisa_init_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605175545,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/pci/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_conf2_read",
        "arch/x86/pci/direct.c:pci_conf1_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588383025,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588385877,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/pci/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/irq.c:pirq_pico_set",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_pico_get",
        "arch/x86/pci/irq.c:pirq_serverworks_get",
        "arch/x86/pci/irq.c:elcr_set_level_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588392644,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/pci/early.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590225054,
      "name": "inb",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:339",
      "file": "arch/x86/lib/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/kaslr.c:kaslr_get_random_long",
        "arch/x86/lib/kaslr.c:kaslr_get_random_long",
        "arch/x86/lib/kaslr.c:kaslr_get_random_long"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
u8 inb(long unsigned int port)
```
</details>
</li>
</ul>
