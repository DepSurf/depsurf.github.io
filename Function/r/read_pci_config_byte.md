# Function: <code>read_pci_config_byte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586162800,
      "name": "read_pci_config_byte",
      "external": true,
      "loc": "arch/x86/pci/early.c:18",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:early_dump_pci_devices"
      ],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:early_quirks",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586162800,
      "name": "read_pci_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586576912,
      "name": "read_pci_config_byte",
      "external": true,
      "loc": "arch/x86/pci/early.c:18",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:early_dump_pci_devices"
      ],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586576112,
      "name": "read_pci_config_byte",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586758480,
      "name": "read_pci_config_byte",
      "external": true,
      "loc": "arch/x86/pci/early.c:18",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:early_dump_pci_devices"
      ],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_tseg_size",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586757680,
      "name": "read_pci_config_byte",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586885358,
      "name": "read_pci_config_byte",
      "external": true,
      "loc": "arch/x86/pci/early.c:18",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:early_dump_pci_devices"
      ],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_tseg_size",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586884592,
      "name": "read_pci_config_byte",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587374046,
      "name": "read_pci_config_byte",
      "external": true,
      "loc": "arch/x86/pci/early.c:19",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:early_dump_pci_devices"
      ],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_tseg_size",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587373280,
      "name": "read_pci_config_byte",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587677918,
      "name": "read_pci_config_byte",
      "external": true,
      "loc": "arch/x86/pci/early.c:19",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:early_dump_pci_devices"
      ],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_tseg_size",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587677104,
      "name": "read_pci_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587808880,
      "name": "read_pci_config_byte",
      "external": true,
      "loc": "arch/x86/pci/early.c:19",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_tseg_size",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587808400,
      "name": "read_pci_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588114363,
      "name": "read_pci_config_byte",
      "external": true,
      "loc": "arch/x86/pci/early.c:19",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_tseg_size",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588113872,
      "name": "read_pci_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588320059,
      "name": "read_pci_config_byte",
      "external": true,
      "loc": "arch/x86/pci/early.c:19",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_tseg_size",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588319568,
      "name": "read_pci_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591140376,
      "name": "read_pci_config_byte",
      "external": true,
      "loc": "arch/x86/pci/early.c:19",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_mem_size",
        "arch/x86/kernel/early-quirks.c:i845_tseg_size",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "drivers/iommu/intel/irq_remapping.c:ir_parse_one_ioapic_scope",
        "drivers/iommu/intel/irq_remapping.c:ir_parse_one_hpet_scope",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591139904,
      "name": "read_pci_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591224600,
      "name": "read_pci_config_byte",
      "external": true,
      "loc": "arch/x86/pci/early.c:19",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_mem_size",
        "arch/x86/kernel/early-quirks.c:i845_tseg_size",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "drivers/iommu/intel/irq_remapping.c:ir_parse_one_ioapic_scope",
        "drivers/iommu/intel/irq_remapping.c:ir_parse_one_hpet_scope",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591224128,
      "name": "read_pci_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591173834,
      "name": "read_pci_config_byte",
      "external": true,
      "loc": "arch/x86/pci/early.c:19",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_mem_size",
        "arch/x86/kernel/early-quirks.c:i845_tseg_size",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591173376,
      "name": "read_pci_config_byte",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592027354,
      "name": "read_pci_config_byte",
      "external": true,
      "loc": "arch/x86/pci/early.c:19",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_mem_size",
        "arch/x86/kernel/early-quirks.c:i845_tseg_size",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592026896,
      "name": "read_pci_config_byte",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593794502,
      "name": "read_pci_config_byte",
      "external": true,
      "loc": "arch/x86/pci/early.c:19",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_mem_size",
        "arch/x86/kernel/early-quirks.c:i845_tseg_size",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593793952,
      "name": "read_pci_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595737782,
      "name": "read_pci_config_byte",
      "external": true,
      "loc": "arch/x86/pci/early.c:19",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_tseg_size",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595737152,
      "name": "read_pci_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596263766,
      "name": "read_pci_config_byte",
      "external": true,
      "loc": "arch/x86/pci/early.c:19",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_tseg_size",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596263136,
      "name": "read_pci_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597146422,
      "name": "read_pci_config_byte",
      "external": true,
      "loc": "arch/x86/pci/early.c:19",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:check_dev_quirk",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_tseg_size",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597145792,
      "name": "read_pci_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587923707,
      "name": "read_pci_config_byte",
      "external": true,
      "loc": "arch/x86/pci/early.c:19",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_tseg_size",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587923216,
      "name": "read_pci_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587639563,
      "name": "read_pci_config_byte",
      "external": true,
      "loc": "arch/x86/pci/early.c:19",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_tseg_size",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587639072,
      "name": "read_pci_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588257115,
      "name": "read_pci_config_byte",
      "external": true,
      "loc": "arch/x86/pci/early.c:19",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_tseg_size",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588256624,
      "name": "read_pci_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset)
```

```json
{
  "name": "read_pci_config_byte",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588392635,
      "name": "read_pci_config_byte",
      "external": true,
      "loc": "arch/x86/pci/early.c:19",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap",
        "arch/x86/pci/early.c:pci_early_find_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:early_pci_scan_bus",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i85x_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i830_stolen_base",
        "arch/x86/kernel/early-quirks.c:i845_tseg_size",
        "arch/x86/kernel/early-quirks.c:intel_remapping_check",
        "arch/x86/kernel/early-quirks.c:ati_bugs",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588392144,
      "name": "read_pci_config_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset)
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
