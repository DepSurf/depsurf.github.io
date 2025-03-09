# Function: <code>kstrtou8</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int kstrtou8(const char * s, unsigned int base, u8 * res)
```

```json
{
  "name": "kstrtou8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583047728,
      "name": "kstrtou8",
      "external": true,
      "loc": "lib/kstrtox.c:294",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_byte",
        "lib/kstrtox.c:kstrtou8_from_user",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/usb/core/sysfs.c:usb2_lpm_besl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583047728,
      "name": "kstrtou8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int kstrtou8(const char * s, unsigned int base, u8 * res)
```

```json
{
  "name": "kstrtou8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583341344,
      "name": "kstrtou8",
      "external": true,
      "loc": "lib/kstrtox.c:294",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_byte",
        "lib/kstrtox.c:kstrtou8_from_user",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/usb/core/sysfs.c:usb2_lpm_besl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583341344,
      "name": "kstrtou8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int kstrtou8(const char * s, unsigned int base, u8 * res)
```

```json
{
  "name": "kstrtou8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583466720,
      "name": "kstrtou8",
      "external": true,
      "loc": "lib/kstrtox.c:290",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_byte",
        "lib/kstrtox.c:kstrtou8_from_user",
        "drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/usb/core/sysfs.c:usb2_lpm_besl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583466720,
      "name": "kstrtou8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int kstrtou8(const char * s, unsigned int base, u8 * res)
```

```json
{
  "name": "kstrtou8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583488992,
      "name": "kstrtou8",
      "external": true,
      "loc": "lib/kstrtox.c:292",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_byte",
        "lib/kstrtox.c:kstrtou8_from_user",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store",
        "drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/usb/core/sysfs.c:usb2_lpm_besl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583488992,
      "name": "kstrtou8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int kstrtou8(const char * s, unsigned int base, u8 * res)
```

```json
{
  "name": "kstrtou8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583670032,
      "name": "kstrtou8",
      "external": true,
      "loc": "lib/kstrtox.c:293",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_byte",
        "lib/kstrtox.c:kstrtou8_from_user",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store",
        "drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/usb/core/sysfs.c:usb2_lpm_besl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583670032,
      "name": "kstrtou8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int kstrtou8(const char * s, unsigned int base, u8 * res)
```

```json
{
  "name": "kstrtou8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583887808,
      "name": "kstrtou8",
      "external": true,
      "loc": "lib/kstrtox.c:293",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_byte",
        "lib/kstrtox.c:kstrtou8_from_user",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store",
        "drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/usb/core/sysfs.c:usb2_lpm_besl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583887808,
      "name": "kstrtou8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int kstrtou8(const char * s, unsigned int base, u8 * res)
```

```json
{
  "name": "kstrtou8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583972048,
      "name": "kstrtou8",
      "external": true,
      "loc": "lib/kstrtox.c:293",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_byte",
        "lib/kstrtox.c:kstrtou8_from_user",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store",
        "drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/usb/core/sysfs.c:usb2_lpm_besl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583972048,
      "name": "kstrtou8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int kstrtou8(const char * s, unsigned int base, u8 * res)
```

```json
{
  "name": "kstrtou8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584153264,
      "name": "kstrtou8",
      "external": true,
      "loc": "lib/kstrtox.c:293",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_byte",
        "lib/kstrtox.c:kstrtou8_from_user",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store",
        "drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/usb/core/sysfs.c:usb2_lpm_besl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584153264,
      "name": "kstrtou8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int kstrtou8(const char * s, unsigned int base, u8 * res)
```

```json
{
  "name": "kstrtou8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584275888,
      "name": "kstrtou8",
      "external": true,
      "loc": "lib/kstrtox.c:293",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_byte",
        "lib/kstrtox.c:kstrtou8_from_user",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store",
        "drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/usb/core/sysfs.c:usb2_lpm_besl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584275888,
      "name": "kstrtou8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int kstrtou8(const char * s, unsigned int base, u8 * res)
```

```json
{
  "name": "kstrtou8",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584685355,
      "name": "kstrtou8",
      "external": true,
      "loc": "lib/kstrtox.c:293",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtou8_from_user"
      ],
      "caller_func": [
        "kernel/params.c:param_set_byte",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store",
        "drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes",
        "drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/usb/core/sysfs.c:usb2_lpm_besl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584684960,
      "name": "kstrtou8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int kstrtou8(const char * s, unsigned int base, u8 * res)
```

```json
{
  "name": "kstrtou8",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584802923,
      "name": "kstrtou8",
      "external": true,
      "loc": "lib/kstrtox.c:289",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtou8_from_user"
      ],
      "caller_func": [
        "kernel/params.c:param_set_byte",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store",
        "drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes",
        "drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/usb/core/sysfs.c:usb2_lpm_besl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584802528,
      "name": "kstrtou8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int kstrtou8(const char * s, unsigned int base, u8 * res)
```

```json
{
  "name": "kstrtou8",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584846507,
      "name": "kstrtou8",
      "external": true,
      "loc": "lib/kstrtox.c:296",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtou8_from_user"
      ],
      "caller_func": [
        "kernel/params.c:param_set_byte",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store",
        "drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes",
        "drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store",
        "drivers/usb/core/sysfs.c:usb2_lpm_besl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584846192,
      "name": "kstrtou8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int kstrtou8(const char * s, unsigned int base, u8 * res)
```

```json
{
  "name": "kstrtou8",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585266497,
      "name": "kstrtou8",
      "external": true,
      "loc": "lib/kstrtox.c:297",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtou8_from_user"
      ],
      "caller_func": [
        "kernel/params.c:param_set_byte",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store",
        "drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes",
        "drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store",
        "drivers/usb/core/sysfs.c:usb2_lpm_besl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585266176,
      "name": "kstrtou8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int kstrtou8(const char * s, unsigned int base, u8 * res)
```

```json
{
  "name": "kstrtou8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586111392,
      "name": "kstrtou8",
      "external": true,
      "loc": "lib/kstrtox.c:307",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_byte",
        "lib/kstrtox.c:kstrtou8_from_user",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store",
        "drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes",
        "drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store",
        "drivers/usb/core/sysfs.c:usb2_lpm_besl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586111392,
      "name": "kstrtou8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int kstrtou8(const char * s, unsigned int base, u8 * res)
```

```json
{
  "name": "kstrtou8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587097200,
      "name": "kstrtou8",
      "external": true,
      "loc": "lib/kstrtox.c:307",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_byte",
        "lib/kstrtox.c:kstrtou8_from_user",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store",
        "drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes",
        "drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store",
        "drivers/usb/core/sysfs.c:usb2_lpm_besl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587097200,
      "name": "kstrtou8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int kstrtou8(const char * s, unsigned int base, u8 * res)
```

```json
{
  "name": "kstrtou8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587357264,
      "name": "kstrtou8",
      "external": true,
      "loc": "lib/kstrtox.c:307",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_byte",
        "lib/kstrtox.c:kstrtou8_from_user",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store",
        "drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes",
        "drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store",
        "drivers/usb/core/sysfs.c:usb2_lpm_besl_store",
        "drivers/usb/host/xhci-dbgcap.c:dbc_bInterfaceProtocol_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587357264,
      "name": "kstrtou8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int kstrtou8(const char * s, unsigned int base, u8 * res)
```

```json
{
  "name": "kstrtou8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587643584,
      "name": "kstrtou8",
      "external": true,
      "loc": "lib/kstrtox.c:307",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_byte",
        "lib/kstrtox.c:kstrtou8_from_user",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store",
        "drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes",
        "drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store",
        "drivers/usb/core/sysfs.c:usb2_lpm_besl_store",
        "drivers/usb/host/xhci-dbgcap.c:dbc_bInterfaceProtocol_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587643584,
      "name": "kstrtou8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int kstrtou8(const char * s, unsigned int base, u8 * res)
```

```json
{
  "name": "kstrtou8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496161256,
      "name": "kstrtou8",
      "external": true,
      "loc": "lib/kstrtox.c:293",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_byte",
        "lib/kstrtox.c:kstrtou8_from_user",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store",
        "drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/usb/core/sysfs.c:usb2_lpm_besl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496161256,
      "name": "kstrtou8",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int kstrtou8(const char * s, unsigned int base, u8 * res)
```

```json
{
  "name": "kstrtou8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229482300,
      "name": "kstrtou8",
      "external": true,
      "loc": "lib/kstrtox.c:293",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_byte",
        "lib/kstrtox.c:kstrtou8_from_user",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/usb/core/sysfs.c:usb2_lpm_besl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229482300,
      "name": "kstrtou8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int kstrtou8(const char * s, unsigned int base, u8 * res)
```

```json
{
  "name": "kstrtou8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290425120,
      "name": "kstrtou8",
      "external": true,
      "loc": "lib/kstrtox.c:293",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_byte",
        "lib/kstrtox.c:kstrtou8_from_user",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/usb/core/sysfs.c:usb2_lpm_besl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290425120,
      "name": "kstrtou8",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int kstrtou8(const char * s, unsigned int base, u8 * res)
```

```json
{
  "name": "kstrtou8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275212728,
      "name": "kstrtou8",
      "external": true,
      "loc": "lib/kstrtox.c:293",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_byte",
        "lib/kstrtox.c:kstrtou8_from_user",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/usb/core/sysfs.c:usb2_lpm_besl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275212728,
      "name": "kstrtou8",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int kstrtou8(const char * s, unsigned int base, u8 * res)
```

```json
{
  "name": "kstrtou8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584244624,
      "name": "kstrtou8",
      "external": true,
      "loc": "lib/kstrtox.c:293",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_byte",
        "lib/kstrtox.c:kstrtou8_from_user",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store",
        "drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/usb/core/sysfs.c:usb2_lpm_besl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584244624,
      "name": "kstrtou8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int kstrtou8(const char * s, unsigned int base, u8 * res)
```

```json
{
  "name": "kstrtou8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584179824,
      "name": "kstrtou8",
      "external": true,
      "loc": "lib/kstrtox.c:293",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_byte",
        "lib/kstrtox.c:kstrtou8_from_user",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store",
        "drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/usb/core/sysfs.c:usb2_lpm_besl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584179824,
      "name": "kstrtou8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int kstrtou8(const char * s, unsigned int base, u8 * res)
```

```json
{
  "name": "kstrtou8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584228384,
      "name": "kstrtou8",
      "external": true,
      "loc": "lib/kstrtox.c:293",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_byte",
        "lib/kstrtox.c:kstrtou8_from_user",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store",
        "drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/usb/core/sysfs.c:usb2_lpm_besl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584228384,
      "name": "kstrtou8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int kstrtou8(const char * s, unsigned int base, u8 * res)
```

```json
{
  "name": "kstrtou8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584333216,
      "name": "kstrtou8",
      "external": true,
      "loc": "lib/kstrtox.c:293",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_byte",
        "lib/kstrtox.c:kstrtou8_from_user",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store",
        "drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg",
        "drivers/usb/core/sysfs.c:usb2_lpm_besl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584333216,
      "name": "kstrtou8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
