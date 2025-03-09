# Function: <code>pnp_get_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * pnp_get_resource(struct pnp_dev * dev, long unsigned int type, unsigned int num)
```

```json
{
  "name": "pnp_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583794352,
      "name": "pnp_get_resource",
      "external": true,
      "loc": "drivers/pnp/resource.c:481",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_dma"
      ],
      "caller_func": [
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583794352,
      "name": "pnp_get_resource",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * pnp_get_resource(struct pnp_dev * dev, long unsigned int type, unsigned int num)
```

```json
{
  "name": "pnp_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584123587,
      "name": "pnp_get_resource",
      "external": true,
      "loc": "drivers/pnp/resource.c:481",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/resource.c:pnp_check_port"
      ],
      "caller_func": [
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584120592,
      "name": "pnp_get_resource",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * pnp_get_resource(struct pnp_dev * dev, long unsigned int type, unsigned int num)
```

```json
{
  "name": "pnp_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584271587,
      "name": "pnp_get_resource",
      "external": true,
      "loc": "drivers/pnp/resource.c:481",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/resource.c:pnp_check_port"
      ],
      "caller_func": [
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584268592,
      "name": "pnp_get_resource",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * pnp_get_resource(struct pnp_dev * dev, long unsigned int type, unsigned int num)
```

```json
{
  "name": "pnp_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584349615,
      "name": "pnp_get_resource",
      "external": true,
      "loc": "drivers/pnp/resource.c:481",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/resource.c:pnp_check_port"
      ],
      "caller_func": [
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584346656,
      "name": "pnp_get_resource",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * pnp_get_resource(struct pnp_dev * dev, long unsigned int type, unsigned int num)
```

```json
{
  "name": "pnp_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584755407,
      "name": "pnp_get_resource",
      "external": true,
      "loc": "drivers/pnp/resource.c:482",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/resource.c:pnp_check_port"
      ],
      "caller_func": [
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584752336,
      "name": "pnp_get_resource",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * pnp_get_resource(struct pnp_dev * dev, long unsigned int type, unsigned int num)
```

```json
{
  "name": "pnp_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584983907,
      "name": "pnp_get_resource",
      "external": true,
      "loc": "drivers/pnp/resource.c:482",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/resource.c:pnp_check_port"
      ],
      "caller_func": [
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584980800,
      "name": "pnp_get_resource",
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
struct resource * pnp_get_resource(struct pnp_dev * dev, long unsigned int type, unsigned int num)
```

```json
{
  "name": "pnp_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585088563,
      "name": "pnp_get_resource",
      "external": true,
      "loc": "drivers/pnp/resource.c:482",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/resource.c:pnp_check_port"
      ],
      "caller_func": [
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585085536,
      "name": "pnp_get_resource",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * pnp_get_resource(struct pnp_dev * dev, long unsigned int type, unsigned int num)
```

```json
{
  "name": "pnp_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585292892,
      "name": "pnp_get_resource",
      "external": true,
      "loc": "drivers/pnp/resource.c:482",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/resource.c:pnp_check_port"
      ],
      "caller_func": [
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585290016,
      "name": "pnp_get_resource",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * pnp_get_resource(struct pnp_dev * dev, long unsigned int type, unsigned int num)
```

```json
{
  "name": "pnp_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585430860,
      "name": "pnp_get_resource",
      "external": true,
      "loc": "drivers/pnp/resource.c:482",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/resource.c:pnp_check_port"
      ],
      "caller_func": [
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585427984,
      "name": "pnp_get_resource",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * pnp_get_resource(struct pnp_dev * dev, long unsigned int type, unsigned int num)
```

```json
{
  "name": "pnp_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586147132,
      "name": "pnp_get_resource",
      "external": true,
      "loc": "drivers/pnp/resource.c:482",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/resource.c:pnp_check_port"
      ],
      "caller_func": [
        "drivers/pnp/manager.c:pnp_assign_dma",
        "drivers/pnp/manager.c:pnp_assign_irq",
        "drivers/pnp/manager.c:pnp_assign_mem",
        "drivers/pnp/manager.c:pnp_assign_port",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/pnp/system.c:reserve_resources_of_dev",
        "drivers/pnp/system.c:reserve_resources_of_dev",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586144160,
      "name": "pnp_get_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct resource * pnp_get_resource(struct pnp_dev * dev, long unsigned int type, unsigned int num)
```

```json
{
  "name": "pnp_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586265980,
      "name": "pnp_get_resource",
      "external": true,
      "loc": "drivers/pnp/resource.c:482",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/resource.c:pnp_check_port"
      ],
      "caller_func": [
        "drivers/pnp/manager.c:pnp_assign_dma",
        "drivers/pnp/manager.c:pnp_assign_irq",
        "drivers/pnp/manager.c:pnp_assign_mem",
        "drivers/pnp/manager.c:pnp_assign_port",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/pnp/system.c:reserve_resources_of_dev",
        "drivers/pnp/system.c:reserve_resources_of_dev",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586263008,
      "name": "pnp_get_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct resource * pnp_get_resource(struct pnp_dev * dev, long unsigned int type, unsigned int num)
```

```json
{
  "name": "pnp_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586139944,
      "name": "pnp_get_resource",
      "external": true,
      "loc": "drivers/pnp/resource.c:482",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/resource.c:pnp_check_port"
      ],
      "caller_func": [
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_irq",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586136992,
      "name": "pnp_get_resource",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * pnp_get_resource(struct pnp_dev * dev, long unsigned int type, unsigned int num)
```

```json
{
  "name": "pnp_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586641004,
      "name": "pnp_get_resource",
      "external": true,
      "loc": "drivers/pnp/resource.c:482",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/resource.c:pnp_check_port"
      ],
      "caller_func": [
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_irq",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586637792,
      "name": "pnp_get_resource",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * pnp_get_resource(struct pnp_dev * dev, long unsigned int type, unsigned int num)
```

```json
{
  "name": "pnp_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587907596,
      "name": "pnp_get_resource",
      "external": true,
      "loc": "drivers/pnp/resource.c:482",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/resource.c:pnp_check_port"
      ],
      "caller_func": [
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_irq",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587904032,
      "name": "pnp_get_resource",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * pnp_get_resource(struct pnp_dev * dev, long unsigned int type, unsigned int num)
```

```json
{
  "name": "pnp_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589258012,
      "name": "pnp_get_resource",
      "external": true,
      "loc": "drivers/pnp/resource.c:483",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/resource.c:pnp_check_port"
      ],
      "caller_func": [
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_irq",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589254272,
      "name": "pnp_get_resource",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * pnp_get_resource(struct pnp_dev * dev, long unsigned int type, unsigned int num)
```

```json
{
  "name": "pnp_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589554828,
      "name": "pnp_get_resource",
      "external": true,
      "loc": "drivers/pnp/resource.c:483",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/resource.c:pnp_check_port"
      ],
      "caller_func": [
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_irq",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589551104,
      "name": "pnp_get_resource",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * pnp_get_resource(struct pnp_dev * dev, long unsigned int type, unsigned int num)
```

```json
{
  "name": "pnp_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589863804,
      "name": "pnp_get_resource",
      "external": true,
      "loc": "drivers/pnp/resource.c:483",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/resource.c:pnp_check_port"
      ],
      "caller_func": [
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_irq",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589859680,
      "name": "pnp_get_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
struct resource * pnp_get_resource(struct pnp_dev * dev, long unsigned int type, unsigned int num)
```

```json
{
  "name": "pnp_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497713072,
      "name": "pnp_get_resource",
      "external": true,
      "loc": "drivers/pnp/resource.c:482",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/resource.c:pnp_check_port"
      ],
      "caller_func": [
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497710312,
      "name": "pnp_get_resource",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pnp_get_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pnp_get_resource",
      "external": false,
      "loc": "include/linux/pnp.h:30",
      "file": "drivers/char/tpm/tpm_tis.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pnp_get_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pnp_get_resource",
      "external": false,
      "loc": "include/linux/pnp.h:30",
      "file": "drivers/char/tpm/tpm_tis.c",
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
  "name": "pnp_get_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pnp_get_resource",
      "external": false,
      "loc": "include/linux/pnp.h:30",
      "file": "drivers/char/tpm/tpm_tis.c",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * pnp_get_resource(struct pnp_dev * dev, long unsigned int type, unsigned int num)
```

```json
{
  "name": "pnp_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585193388,
      "name": "pnp_get_resource",
      "external": true,
      "loc": "drivers/pnp/resource.c:482",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/resource.c:pnp_check_port"
      ],
      "caller_func": [
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585190512,
      "name": "pnp_get_resource",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * pnp_get_resource(struct pnp_dev * dev, long unsigned int type, unsigned int num)
```

```json
{
  "name": "pnp_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585145596,
      "name": "pnp_get_resource",
      "external": true,
      "loc": "drivers/pnp/resource.c:482",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/resource.c:pnp_check_port"
      ],
      "caller_func": [
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585142720,
      "name": "pnp_get_resource",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * pnp_get_resource(struct pnp_dev * dev, long unsigned int type, unsigned int num)
```

```json
{
  "name": "pnp_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585381260,
      "name": "pnp_get_resource",
      "external": true,
      "loc": "drivers/pnp/resource.c:482",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/resource.c:pnp_check_port"
      ],
      "caller_func": [
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585378384,
      "name": "pnp_get_resource",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * pnp_get_resource(struct pnp_dev * dev, long unsigned int type, unsigned int num)
```

```json
{
  "name": "pnp_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585488604,
      "name": "pnp_get_resource",
      "external": true,
      "loc": "drivers/pnp/resource.c:482",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_dma",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/resource.c:pnp_check_port"
      ],
      "caller_func": [
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/support.c:pnp_is_active",
        "drivers/pnp/quirks.c:quirk_system_pci_resources",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/system.c:system_pnp_probe",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_pnp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585485728,
      "name": "pnp_get_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct resource * pnp_get_resource(struct pnp_dev * dev, long unsigned int type, unsigned int num)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct resource * pnp_get_resource(struct pnp_dev * dev, long unsigned int type, unsigned int num)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct resource * pnp_get_resource(struct pnp_dev * dev, long unsigned int type, unsigned int num)
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
