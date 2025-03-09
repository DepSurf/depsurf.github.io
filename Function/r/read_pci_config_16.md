# Function: <code>read_pci_config_16</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586162864,
      "name": "read_pci_config_16",
      "external": true,
      "loc": "arch/x86/pci/early.c:26",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/early-quirks.c:gen9_stolen_size",
        "arch/x86/kernel/early-quirks.c:chv_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen8_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen6_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_size",
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_size",
        "arch/x86/kernel/early-quirks.c:intel_graphics_stolen",
        "arch/x86/kernel/early-quirks.c:intel_graphics_stolen",
        "arch/x86/kernel/early-quirks.c:intel_graphics_stolen",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:early_quirks",
        "arch/x86/kernel/early-quirks.c:early_quirks",
        "arch/x86/kernel/early-quirks.c:early_quirks",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586162864,
      "name": "read_pci_config_16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586576176,
      "name": "read_pci_config_16",
      "external": true,
      "loc": "arch/x86/pci/early.c:26",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/early-quirks.c:gen9_stolen_size",
        "arch/x86/kernel/early-quirks.c:chv_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen8_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen6_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_size",
        "arch/x86/kernel/early-quirks.c:i830_stolen_size",
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586576176,
      "name": "read_pci_config_16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586757744,
      "name": "read_pci_config_16",
      "external": true,
      "loc": "arch/x86/pci/early.c:26",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/early-quirks.c:gen9_stolen_size",
        "arch/x86/kernel/early-quirks.c:chv_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen8_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen6_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_size",
        "arch/x86/kernel/early-quirks.c:i830_stolen_size",
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586757744,
      "name": "read_pci_config_16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586884656,
      "name": "read_pci_config_16",
      "external": true,
      "loc": "arch/x86/pci/early.c:26",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/early-quirks.c:gen9_stolen_size",
        "arch/x86/kernel/early-quirks.c:chv_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen8_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen6_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_size",
        "arch/x86/kernel/early-quirks.c:i830_stolen_size",
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586884656,
      "name": "read_pci_config_16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587373344,
      "name": "read_pci_config_16",
      "external": true,
      "loc": "arch/x86/pci/early.c:27",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/early-quirks.c:gen9_stolen_size",
        "arch/x86/kernel/early-quirks.c:chv_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen8_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen6_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_size",
        "arch/x86/kernel/early-quirks.c:i830_stolen_size",
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587373344,
      "name": "read_pci_config_16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587677168,
      "name": "read_pci_config_16",
      "external": true,
      "loc": "arch/x86/pci/early.c:27",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/early-quirks.c:gen9_stolen_size",
        "arch/x86/kernel/early-quirks.c:chv_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen8_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen6_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_size",
        "arch/x86/kernel/early-quirks.c:i830_stolen_size",
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587677168,
      "name": "read_pci_config_16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_16",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587808773,
      "name": "read_pci_config_16",
      "external": true,
      "loc": "arch/x86/pci/early.c:27",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/early-quirks.c:gen9_stolen_size",
        "arch/x86/kernel/early-quirks.c:chv_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen8_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen6_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_size",
        "arch/x86/kernel/early-quirks.c:i830_stolen_size",
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587808464,
      "name": "read_pci_config_16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_16",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588114245,
      "name": "read_pci_config_16",
      "external": true,
      "loc": "arch/x86/pci/early.c:27",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/early-quirks.c:gen9_stolen_size",
        "arch/x86/kernel/early-quirks.c:chv_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen8_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen6_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_size",
        "arch/x86/kernel/early-quirks.c:i830_stolen_size",
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588113936,
      "name": "read_pci_config_16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_16",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588319941,
      "name": "read_pci_config_16",
      "external": true,
      "loc": "arch/x86/pci/early.c:27",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/early-quirks.c:gen9_stolen_size",
        "arch/x86/kernel/early-quirks.c:chv_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen8_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen6_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_size",
        "arch/x86/kernel/early-quirks.c:i830_stolen_size",
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588319632,
      "name": "read_pci_config_16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_16",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591140261,
      "name": "read_pci_config_16",
      "external": true,
      "loc": "arch/x86/pci/early.c:27",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/early-quirks.c:gen9_stolen_size",
        "arch/x86/kernel/early-quirks.c:chv_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen8_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen6_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_size",
        "arch/x86/kernel/early-quirks.c:i830_stolen_size",
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/aperture_64.c:read_agp",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591139968,
      "name": "read_pci_config_16",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_16",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591224485,
      "name": "read_pci_config_16",
      "external": true,
      "loc": "arch/x86/pci/early.c:27",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/early-quirks.c:gen9_stolen_size",
        "arch/x86/kernel/early-quirks.c:chv_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen8_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen6_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_size",
        "arch/x86/kernel/early-quirks.c:i830_stolen_size",
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/aperture_64.c:read_agp",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591224192,
      "name": "read_pci_config_16",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_16",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591173717,
      "name": "read_pci_config_16",
      "external": true,
      "loc": "arch/x86/pci/early.c:27",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/early-quirks.c:gen9_stolen_size",
        "arch/x86/kernel/early-quirks.c:chv_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen8_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen6_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_size",
        "arch/x86/kernel/early-quirks.c:i830_stolen_size",
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/aperture_64.c:read_agp",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591173440,
      "name": "read_pci_config_16",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_16",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592027237,
      "name": "read_pci_config_16",
      "external": true,
      "loc": "arch/x86/pci/early.c:27",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/early-quirks.c:gen9_stolen_size",
        "arch/x86/kernel/early-quirks.c:chv_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen8_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen6_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_size",
        "arch/x86/kernel/early-quirks.c:i830_stolen_size",
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/aperture_64.c:read_agp",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592026960,
      "name": "read_pci_config_16",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_16",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593794389,
      "name": "read_pci_config_16",
      "external": true,
      "loc": "arch/x86/pci/early.c:27",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/early-quirks.c:gen9_stolen_size",
        "arch/x86/kernel/early-quirks.c:chv_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen8_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen6_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_size",
        "arch/x86/kernel/early-quirks.c:i830_stolen_size",
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/aperture_64.c:read_agp",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593794032,
      "name": "read_pci_config_16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_16",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595737669,
      "name": "read_pci_config_16",
      "external": true,
      "loc": "arch/x86/pci/early.c:27",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/early-quirks.c:gen9_stolen_size",
        "arch/x86/kernel/early-quirks.c:chv_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen8_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen6_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_size",
        "arch/x86/kernel/early-quirks.c:i830_stolen_size",
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/aperture_64.c:read_agp",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595737248,
      "name": "read_pci_config_16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_16",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596263653,
      "name": "read_pci_config_16",
      "external": true,
      "loc": "arch/x86/pci/early.c:27",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/early-quirks.c:gen9_stolen_size",
        "arch/x86/kernel/early-quirks.c:chv_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen8_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen6_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_size",
        "arch/x86/kernel/early-quirks.c:i830_stolen_size",
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/aperture_64.c:read_agp",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596263232,
      "name": "read_pci_config_16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_16",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597146309,
      "name": "read_pci_config_16",
      "external": true,
      "loc": "arch/x86/pci/early.c:27",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/early-quirks.c:gen9_stolen_size",
        "arch/x86/kernel/early-quirks.c:chv_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen8_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen6_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_size",
        "arch/x86/kernel/early-quirks.c:i830_stolen_size",
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/aperture_64.c:read_agp",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597145888,
      "name": "read_pci_config_16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_16",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587923589,
      "name": "read_pci_config_16",
      "external": true,
      "loc": "arch/x86/pci/early.c:27",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/early-quirks.c:gen9_stolen_size",
        "arch/x86/kernel/early-quirks.c:chv_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen8_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen6_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_size",
        "arch/x86/kernel/early-quirks.c:i830_stolen_size",
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587923280,
      "name": "read_pci_config_16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_16",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587639445,
      "name": "read_pci_config_16",
      "external": true,
      "loc": "arch/x86/pci/early.c:27",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/early-quirks.c:gen9_stolen_size",
        "arch/x86/kernel/early-quirks.c:chv_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen8_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen6_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_size",
        "arch/x86/kernel/early-quirks.c:i830_stolen_size",
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587639136,
      "name": "read_pci_config_16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_16",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588256997,
      "name": "read_pci_config_16",
      "external": true,
      "loc": "arch/x86/pci/early.c:27",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/early-quirks.c:gen9_stolen_size",
        "arch/x86/kernel/early-quirks.c:chv_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen8_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen6_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_size",
        "arch/x86/kernel/early-quirks.c:i830_stolen_size",
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588256688,
      "name": "read_pci_config_16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_16",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588392517,
      "name": "read_pci_config_16",
      "external": true,
      "loc": "arch/x86/pci/early.c:27",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/early-quirks.c:gen9_stolen_size",
        "arch/x86/kernel/early-quirks.c:chv_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen8_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen6_stolen_size",
        "arch/x86/kernel/early-quirks.c:gen3_stolen_size",
        "arch/x86/kernel/early-quirks.c:i830_stolen_size",
        "arch/x86/kernel/early-quirks.c:i865_stolen_base",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588392208,
      "name": "read_pci_config_16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset)
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
