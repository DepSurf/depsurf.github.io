# Function: <code>write_pci_config</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val)
```

```json
{
  "name": "write_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586162944,
      "name": "write_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:34",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586162944,
      "name": "write_pci_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val)
```

```json
{
  "name": "write_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586576256,
      "name": "write_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:34",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586576256,
      "name": "write_pci_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val)
```

```json
{
  "name": "write_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586757824,
      "name": "write_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:34",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586757824,
      "name": "write_pci_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val)
```

```json
{
  "name": "write_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586884736,
      "name": "write_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:34",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586884736,
      "name": "write_pci_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val)
```

```json
{
  "name": "write_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587373424,
      "name": "write_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:35",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587373424,
      "name": "write_pci_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val)
```

```json
{
  "name": "write_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587677248,
      "name": "write_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:35",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587677248,
      "name": "write_pci_config",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val)
```

```json
{
  "name": "write_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587808544,
      "name": "write_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:35",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587808544,
      "name": "write_pci_config",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val)
```

```json
{
  "name": "write_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588114016,
      "name": "write_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:35",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588114016,
      "name": "write_pci_config",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val)
```

```json
{
  "name": "write_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588319712,
      "name": "write_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:35",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588319712,
      "name": "write_pci_config",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val)
```

```json
{
  "name": "write_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591140032,
      "name": "write_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:35",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "arch/x86/pci/amd_bus.c:pci_enable_pci_io_ecs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591140032,
      "name": "write_pci_config",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val)
```

```json
{
  "name": "write_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591224256,
      "name": "write_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:35",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "arch/x86/pci/amd_bus.c:pci_enable_pci_io_ecs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591224256,
      "name": "write_pci_config",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val)
```

```json
{
  "name": "write_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591173504,
      "name": "write_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:35",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591173504,
      "name": "write_pci_config",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val)
```

```json
{
  "name": "write_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592027024,
      "name": "write_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:35",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592027024,
      "name": "write_pci_config",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val)
```

```json
{
  "name": "write_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593794112,
      "name": "write_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:35",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593794112,
      "name": "write_pci_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val)
```

```json
{
  "name": "write_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595737344,
      "name": "write_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:35",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595737344,
      "name": "write_pci_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val)
```

```json
{
  "name": "write_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596263328,
      "name": "write_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:35",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596263328,
      "name": "write_pci_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val)
```

```json
{
  "name": "write_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597145984,
      "name": "write_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:35",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597145984,
      "name": "write_pci_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val)
```

```json
{
  "name": "write_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587923360,
      "name": "write_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:35",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587923360,
      "name": "write_pci_config",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val)
```

```json
{
  "name": "write_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587639216,
      "name": "write_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:35",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587639216,
      "name": "write_pci_config",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val)
```

```json
{
  "name": "write_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588256768,
      "name": "write_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:35",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588256768,
      "name": "write_pci_config",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val)
```

```json
{
  "name": "write_pci_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588392288,
      "name": "write_pci_config",
      "external": true,
      "loc": "arch/x86/pci/early.c:35",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/early-quirks.c:fix_hypertransport_config",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588392288,
      "name": "write_pci_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val)
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
