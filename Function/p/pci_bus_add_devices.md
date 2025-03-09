# Function: <code>pci_bus_add_devices</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_bus_add_devices(const struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583233440,
      "name": "pci_bus_add_devices",
      "external": true,
      "loc": "drivers/pci/bus.c:306",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "arch/x86/pci/common.c:pcibios_scan_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583233440,
      "name": "pci_bus_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void pci_bus_add_devices(const struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583543136,
      "name": "pci_bus_add_devices",
      "external": true,
      "loc": "drivers/pci/bus.c:344",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_devices",
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "arch/x86/pci/common.c:pcibios_scan_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583543136,
      "name": "pci_bus_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void pci_bus_add_devices(const struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583679456,
      "name": "pci_bus_add_devices",
      "external": true,
      "loc": "drivers/pci/bus.c:344",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_devices",
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "arch/x86/pci/common.c:pcibios_scan_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583679456,
      "name": "pci_bus_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void pci_bus_add_devices(const struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583719824,
      "name": "pci_bus_add_devices",
      "external": true,
      "loc": "drivers/pci/bus.c:344",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_devices",
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "arch/x86/pci/common.c:pcibios_scan_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583719824,
      "name": "pci_bus_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void pci_bus_add_devices(const struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583977424,
      "name": "pci_bus_add_devices",
      "external": true,
      "loc": "drivers/pci/bus.c:344",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_devices",
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "arch/x86/pci/common.c:pcibios_scan_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583977424,
      "name": "pci_bus_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void pci_bus_add_devices(const struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584171184,
      "name": "pci_bus_add_devices",
      "external": true,
      "loc": "drivers/pci/bus.c:343",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_devices",
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_host_probe",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "arch/x86/pci/common.c:pcibios_scan_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584171184,
      "name": "pci_bus_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void pci_bus_add_devices(const struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584259088,
      "name": "pci_bus_add_devices",
      "external": true,
      "loc": "drivers/pci/bus.c:343",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_devices",
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_host_probe",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "arch/x86/pci/common.c:pcibios_scan_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584259088,
      "name": "pci_bus_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void pci_bus_add_devices(const struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584452112,
      "name": "pci_bus_add_devices",
      "external": true,
      "loc": "drivers/pci/bus.c:342",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_devices",
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_host_probe",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "arch/x86/pci/common.c:pcibios_scan_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584452112,
      "name": "pci_bus_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void pci_bus_add_devices(const struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584588720,
      "name": "pci_bus_add_devices",
      "external": true,
      "loc": "drivers/pci/bus.c:342",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_devices",
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_host_probe",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "arch/x86/pci/common.c:pcibios_scan_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584588720,
      "name": "pci_bus_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void pci_bus_add_devices(const struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585264832,
      "name": "pci_bus_add_devices",
      "external": true,
      "loc": "drivers/pci/bus.c:338",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_devices",
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_host_probe",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "arch/x86/pci/common.c:pcibios_scan_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585264832,
      "name": "pci_bus_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void pci_bus_add_devices(const struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585422512,
      "name": "pci_bus_add_devices",
      "external": true,
      "loc": "drivers/pci/bus.c:338",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_devices",
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_host_probe",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "arch/x86/pci/common.c:pcibios_scan_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585422512,
      "name": "pci_bus_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void pci_bus_add_devices(const struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585303024,
      "name": "pci_bus_add_devices",
      "external": true,
      "loc": "drivers/pci/bus.c:338",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_devices",
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_host_probe",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "arch/x86/pci/common.c:pcibios_scan_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585303024,
      "name": "pci_bus_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void pci_bus_add_devices(const struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585760112,
      "name": "pci_bus_add_devices",
      "external": true,
      "loc": "drivers/pci/bus.c:338",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_devices",
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_host_probe",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "arch/x86/pci/common.c:pcibios_scan_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585760112,
      "name": "pci_bus_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void pci_bus_add_devices(const struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586944608,
      "name": "pci_bus_add_devices",
      "external": true,
      "loc": "drivers/pci/bus.c:338",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_devices",
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_host_probe",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "arch/x86/pci/common.c:pcibios_scan_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586944608,
      "name": "pci_bus_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void pci_bus_add_devices(const struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588102784,
      "name": "pci_bus_add_devices",
      "external": true,
      "loc": "drivers/pci/bus.c:342",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_devices",
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_host_probe",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "arch/x86/pci/common.c:pcibios_scan_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588102784,
      "name": "pci_bus_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void pci_bus_add_devices(const struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588377808,
      "name": "pci_bus_add_devices",
      "external": true,
      "loc": "drivers/pci/bus.c:364",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_devices",
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_host_probe",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "arch/x86/pci/common.c:pcibios_scan_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588377808,
      "name": "pci_bus_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void pci_bus_add_devices(const struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588672992,
      "name": "pci_bus_add_devices",
      "external": true,
      "loc": "drivers/pci/bus.c:366",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_devices",
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_host_probe",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "arch/x86/pci/common.c:pcibios_scan_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588672992,
      "name": "pci_bus_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void pci_bus_add_devices(const struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496827640,
      "name": "pci_bus_add_devices",
      "external": true,
      "loc": "drivers/pci/bus.c:342",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_devices",
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_host_probe",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe",
        "drivers/pci/controller/pcie-altera.c:altera_pcie_probe",
        "drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_probe",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init",
        "drivers/pci/controller/pci-xgene.c:xgene_pcie_probe",
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496827640,
      "name": "pci_bus_add_devices",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void pci_bus_add_devices(const struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230107856,
      "name": "pci_bus_add_devices",
      "external": true,
      "loc": "drivers/pci/bus.c:342",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/bios32.c:pci_common_init_dev",
        "drivers/pci/bus.c:pci_bus_add_devices",
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_host_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/pci/controller/pci-v3-semi.c:v3_pci_probe",
        "drivers/pci/controller/pcie-altera.c:altera_pcie_probe",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230107856,
      "name": "pci_bus_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void pci_bus_add_devices(const struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290900032,
      "name": "pci_bus_add_devices",
      "external": true,
      "loc": "drivers/pci/bus.c:342",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/pci_64.c:pcibios_init",
        "arch/powerpc/kernel/pci-common.c:pcibios_finish_adding_to_bus",
        "arch/powerpc/kernel/pci-common.c:pcibios_finish_adding_to_bus",
        "drivers/pci/bus.c:pci_bus_add_devices",
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_host_probe",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290900032,
      "name": "pci_bus_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void pci_bus_add_devices(const struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275534186,
      "name": "pci_bus_add_devices",
      "external": true,
      "loc": "drivers/pci/bus.c:342",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_devices",
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_host_probe",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275534186,
      "name": "pci_bus_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void pci_bus_add_devices(const struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584540864,
      "name": "pci_bus_add_devices",
      "external": true,
      "loc": "drivers/pci/bus.c:342",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_devices",
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_host_probe",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "arch/x86/pci/common.c:pcibios_scan_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584540864,
      "name": "pci_bus_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void pci_bus_add_devices(const struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584469040,
      "name": "pci_bus_add_devices",
      "external": true,
      "loc": "drivers/pci/bus.c:342",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_devices",
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_host_probe",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "arch/x86/pci/common.c:pcibios_scan_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584469040,
      "name": "pci_bus_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void pci_bus_add_devices(const struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584538880,
      "name": "pci_bus_add_devices",
      "external": true,
      "loc": "drivers/pci/bus.c:342",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_devices",
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_host_probe",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "arch/x86/pci/common.c:pcibios_scan_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584538880,
      "name": "pci_bus_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void pci_bus_add_devices(const struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584646624,
      "name": "pci_bus_add_devices",
      "external": true,
      "loc": "drivers/pci/bus.c:342",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_devices",
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_host_probe",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "arch/x86/pci/common.c:pcibios_scan_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584646624,
      "name": "pci_bus_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
