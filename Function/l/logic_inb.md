# Function: <code>logic_inb</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
u8 logic_inb(long unsigned int addr)
```

```json
{
  "name": "logic_inb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496177704,
      "name": "logic_inb",
      "external": true,
      "loc": "lib/logic_pio.c:297",
      "file": "lib/logic_pio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char",
        "drivers/pci/pci-sysfs.c:pci_read_resource_io",
        "drivers/acpi/ec.c:acpi_ec_space_handler",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:io_serial_in",
        "drivers/tty/serial/8250/8250_port.c:hub6_serial_in",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:sio_write_mask_reg",
        "drivers/tty/serial/8250/8250_pci.c:kt_serial_in",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_in",
        "drivers/char/mem.c:read_port",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496177704,
      "name": "logic_inb",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
u8 logic_inb(long unsigned int addr)
```
</details>
</li>
</ul>
