# Function: <code>acpi_match_device_ids</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int acpi_match_device_ids(struct acpi_device * device, const struct acpi_device_id * ids)
```

```json
{
  "name": "acpi_match_device_ids",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583558140,
      "name": "acpi_match_device_ids",
      "external": true,
      "loc": "drivers/acpi/bus.c:674",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/pci_root.c:acpi_pci_find_root",
        "drivers/acpi/acpi_pnp.c:is_cmos_rtc_device",
        "drivers/mfd/mfd-core.c:mfd_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583558140,
      "name": "acpi_match_device_ids",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
int acpi_match_device_ids(struct acpi_device * device, const struct acpi_device_id * ids)
```

```json
{
  "name": "acpi_match_device_ids",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583879700,
      "name": "acpi_match_device_ids",
      "external": true,
      "loc": "drivers/acpi/bus.c:750",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_root.c:acpi_pci_find_root",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/acpi_pnp.c:acpi_is_pnp_device",
        "drivers/mfd/mfd-core.c:mfd_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583879700,
      "name": "acpi_match_device_ids",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
int acpi_match_device_ids(struct acpi_device * device, const struct acpi_device_id * ids)
```

```json
{
  "name": "acpi_match_device_ids",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584018754,
      "name": "acpi_match_device_ids",
      "external": true,
      "loc": "drivers/acpi/bus.c:760",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_root.c:acpi_pci_find_root",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/acpi_pnp.c:acpi_is_pnp_device",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/firmware/efi/dev-path-parser.c:match_acpi_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584018754,
      "name": "acpi_match_device_ids",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
int acpi_match_device_ids(struct acpi_device * device, const struct acpi_device_id * ids)
```

```json
{
  "name": "acpi_match_device_ids",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584071698,
      "name": "acpi_match_device_ids",
      "external": true,
      "loc": "drivers/acpi/bus.c:788",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_bus_match"
      ],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_root.c:acpi_pci_find_root",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/acpi_pnp.c:acpi_is_pnp_device",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup",
        "drivers/firmware/efi/dev-path-parser.c:match_acpi_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584071648,
      "name": "acpi_match_device_ids",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
int acpi_match_device_ids(struct acpi_device * device, const struct acpi_device_id * ids)
```

```json
{
  "name": "acpi_match_device_ids",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584341378,
      "name": "acpi_match_device_ids",
      "external": true,
      "loc": "drivers/acpi/bus.c:815",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_bus_match"
      ],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/pci_root.c:acpi_pci_find_root",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/acpi_pnp.c:acpi_is_pnp_device",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup",
        "drivers/firmware/efi/dev-path-parser.c:match_acpi_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584341328,
      "name": "acpi_match_device_ids",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
int acpi_match_device_ids(struct acpi_device * device, const struct acpi_device_id * ids)
```

```json
{
  "name": "acpi_match_device_ids",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584562704,
      "name": "acpi_match_device_ids",
      "external": true,
      "loc": "drivers/acpi/bus.c:845",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_bus_match"
      ],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/pci_root.c:acpi_pci_find_root",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/acpi_pnp.c:acpi_is_pnp_device",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup",
        "drivers/firmware/efi/dev-path-parser.c:match_acpi_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584562752,
      "name": "acpi_match_device_ids",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_match_device_ids(struct acpi_device * device, const struct acpi_device_id * ids)
```

```json
{
  "name": "acpi_match_device_ids",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584660016,
      "name": "acpi_match_device_ids",
      "external": true,
      "loc": "drivers/acpi/bus.c:814",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_bus_match"
      ],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/pci_root.c:acpi_pci_find_root",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/acpi_pnp.c:acpi_is_pnp_device",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup",
        "drivers/firmware/efi/dev-path-parser.c:match_acpi_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584660064,
      "name": "acpi_match_device_ids",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_match_device_ids(struct acpi_device * device, const struct acpi_device_id * ids)
```

```json
{
  "name": "acpi_match_device_ids",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584860064,
      "name": "acpi_match_device_ids",
      "external": true,
      "loc": "drivers/acpi/bus.c:815",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_bus_match"
      ],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/pci_root.c:acpi_pci_find_root",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/acpi_pnp.c:acpi_is_pnp_device",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup",
        "drivers/firmware/efi/dev-path-parser.c:match_acpi_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584860112,
      "name": "acpi_match_device_ids",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_match_device_ids(struct acpi_device * device, const struct acpi_device_id * ids)
```

```json
{
  "name": "acpi_match_device_ids",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584995936,
      "name": "acpi_match_device_ids",
      "external": true,
      "loc": "drivers/acpi/bus.c:815",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_bus_match"
      ],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/pci_root.c:acpi_pci_find_root",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/acpi_pnp.c:acpi_is_pnp_device",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup",
        "drivers/firmware/efi/dev-path-parser.c:match_acpi_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584995984,
      "name": "acpi_match_device_ids",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_match_device_ids(struct acpi_device * device, const struct acpi_device_id * ids)
```

```json
{
  "name": "acpi_match_device_ids",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585694225,
      "name": "acpi_match_device_ids",
      "external": true,
      "loc": "drivers/acpi/bus.c:815",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_bus_match"
      ],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/scan.c:acpi_device_enumeration_by_parent",
        "drivers/acpi/scan.c:acpi_device_enumeration_by_parent",
        "drivers/acpi/scan.c:acpi_bus_get_wakeup_device_flags",
        "drivers/acpi/scan.c:acpi_bus_get_wakeup_device_flags",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/acpi_pnp.c:acpi_is_pnp_device",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup",
        "drivers/firmware/efi/dev-path-parser.c:match_acpi_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585693728,
      "name": "acpi_match_device_ids",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_match_device_ids(struct acpi_device * device, const struct acpi_device_id * ids)
```

```json
{
  "name": "acpi_match_device_ids",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585816465,
      "name": "acpi_match_device_ids",
      "external": true,
      "loc": "drivers/acpi/bus.c:820",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_bus_match"
      ],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/scan.c:acpi_device_enumeration_by_parent",
        "drivers/acpi/scan.c:acpi_device_enumeration_by_parent",
        "drivers/acpi/scan.c:acpi_bus_get_wakeup_device_flags",
        "drivers/acpi/scan.c:acpi_bus_get_wakeup_device_flags",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/acpi_pnp.c:acpi_is_pnp_device",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup",
        "drivers/firmware/efi/dev-path-parser.c:match_acpi_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585815952,
      "name": "acpi_match_device_ids",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int acpi_match_device_ids(struct acpi_device * device, const struct acpi_device_id * ids)
```

```json
{
  "name": "acpi_match_device_ids",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585696481,
      "name": "acpi_match_device_ids",
      "external": true,
      "loc": "drivers/acpi/bus.c:899",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_bus_match"
      ],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/acpi_pnp.c:acpi_is_pnp_device",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585696400,
      "name": "acpi_match_device_ids",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int acpi_match_device_ids(struct acpi_device * device, const struct acpi_device_id * ids)
```

```json
{
  "name": "acpi_match_device_ids",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586176801,
      "name": "acpi_match_device_ids",
      "external": true,
      "loc": "drivers/acpi/bus.c:901",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_bus_match"
      ],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/acpi_pnp.c:acpi_is_pnp_device",
        "drivers/acpi/x86/utils.c:acpi_device_override_status",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586176720,
      "name": "acpi_match_device_ids",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int acpi_match_device_ids(struct acpi_device * device, const struct acpi_device_id * ids)
```

```json
{
  "name": "acpi_match_device_ids",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587412125,
      "name": "acpi_match_device_ids",
      "external": true,
      "loc": "drivers/acpi/bus.c:938",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_bus_match"
      ],
      "caller_func": [
        "drivers/acpi/utils.c:acpi_dev_match_cb",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/acpi_platform.c:acpi_create_platform_device",
        "drivers/acpi/acpi_pnp.c:acpi_is_pnp_device",
        "drivers/acpi/x86/utils.c:acpi_device_override_status",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587411808,
      "name": "acpi_match_device_ids",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int acpi_match_device_ids(struct acpi_device * device, const struct acpi_device_id * ids)
```

```json
{
  "name": "acpi_match_device_ids",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588667949,
      "name": "acpi_match_device_ids",
      "external": true,
      "loc": "drivers/acpi/bus.c:945",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_bus_match"
      ],
      "caller_func": [
        "drivers/acpi/utils.c:acpi_dev_match_cb",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/acpi_platform.c:acpi_create_platform_device",
        "drivers/acpi/acpi_pnp.c:acpi_is_pnp_device",
        "drivers/acpi/x86/utils.c:acpi_device_override_status",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/mfd/mfd-core.c:match_device_ids",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588667504,
      "name": "acpi_match_device_ids",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int acpi_match_device_ids(struct acpi_device * device, const struct acpi_device_id * ids)
```

```json
{
  "name": "acpi_match_device_ids",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588955677,
      "name": "acpi_match_device_ids",
      "external": true,
      "loc": "drivers/acpi/bus.c:918",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_bus_match"
      ],
      "caller_func": [
        "drivers/acpi/utils.c:acpi_dev_match_cb",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/acpi_pnp.c:acpi_is_pnp_device",
        "drivers/acpi/acpi_pnp.c:acpi_pnp_attach",
        "drivers/acpi/x86/utils.c:acpi_device_override_status",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/mfd/mfd-core.c:match_device_ids",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588954672,
      "name": "acpi_match_device_ids",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int acpi_match_device_ids(struct acpi_device * device, const struct acpi_device_id * ids)
```

```json
{
  "name": "acpi_match_device_ids",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589252973,
      "name": "acpi_match_device_ids",
      "external": true,
      "loc": "drivers/acpi/bus.c:968",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_bus_match"
      ],
      "caller_func": [
        "drivers/acpi/utils.c:acpi_dev_match_cb",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/acpi_pnp.c:acpi_is_pnp_device",
        "drivers/acpi/acpi_pnp.c:acpi_pnp_attach",
        "drivers/acpi/x86/utils.c:acpi_device_override_status",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/mfd/mfd-core.c:match_device_ids",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589251424,
      "name": "acpi_match_device_ids",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int acpi_match_device_ids(struct acpi_device * device, const struct acpi_device_id * ids)
```

```json
{
  "name": "acpi_match_device_ids",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497405184,
      "name": "acpi_match_device_ids",
      "external": true,
      "loc": "drivers/acpi/bus.c:815",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_bus_match"
      ],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/pci_root.c:acpi_pci_find_root",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/acpi_pnp.c:acpi_is_pnp_device",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup",
        "drivers/perf/xgene_pmu.c:acpi_pmu_dev_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497405256,
      "name": "acpi_match_device_ids",
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_match_device_ids(struct acpi_device * device, const struct acpi_device_id * ids)
```

```json
{
  "name": "acpi_match_device_ids",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584939840,
      "name": "acpi_match_device_ids",
      "external": true,
      "loc": "drivers/acpi/bus.c:815",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_bus_match"
      ],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/pci_root.c:acpi_pci_find_root",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/acpi_pnp.c:acpi_is_pnp_device",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/firmware/efi/dev-path-parser.c:match_acpi_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584939888,
      "name": "acpi_match_device_ids",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_match_device_ids(struct acpi_device * device, const struct acpi_device_id * ids)
```

```json
{
  "name": "acpi_match_device_ids",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584848640,
      "name": "acpi_match_device_ids",
      "external": true,
      "loc": "drivers/acpi/bus.c:815",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_bus_match"
      ],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/pci_root.c:acpi_pci_find_root",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/acpi_pnp.c:acpi_is_pnp_device",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/firmware/efi/dev-path-parser.c:match_acpi_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584848688,
      "name": "acpi_match_device_ids",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_match_device_ids(struct acpi_device * device, const struct acpi_device_id * ids)
```

```json
{
  "name": "acpi_match_device_ids",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584947520,
      "name": "acpi_match_device_ids",
      "external": true,
      "loc": "drivers/acpi/bus.c:815",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_bus_match"
      ],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/pci_root.c:acpi_pci_find_root",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/acpi_pnp.c:acpi_is_pnp_device",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup",
        "drivers/firmware/efi/dev-path-parser.c:match_acpi_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584947568,
      "name": "acpi_match_device_ids",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_match_device_ids(struct acpi_device * device, const struct acpi_device_id * ids)
```

```json
{
  "name": "acpi_match_device_ids",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585053696,
      "name": "acpi_match_device_ids",
      "external": true,
      "loc": "drivers/acpi/bus.c:815",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_bus_match"
      ],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/pci_root.c:acpi_pci_find_root",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/acpi_pnp.c:acpi_is_pnp_device",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup",
        "drivers/firmware/efi/dev-path-parser.c:match_acpi_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585053744,
      "name": "acpi_match_device_ids",
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
int acpi_match_device_ids(struct acpi_device * device, const struct acpi_device_id * ids)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_match_device_ids(struct acpi_device * device, const struct acpi_device_id * ids)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_match_device_ids(struct acpi_device * device, const struct acpi_device_id * ids)
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
