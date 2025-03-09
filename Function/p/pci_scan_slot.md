# Function: <code>pci_scan_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_scan_slot(struct pci_bus * bus, int devfn)
```

```json
{
  "name": "pci_scan_slot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583242288,
      "name": "pci_scan_slot",
      "external": true,
      "loc": "drivers/pci/probe.c:1845",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_child_bus",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583242288,
      "name": "pci_scan_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int pci_scan_slot(struct pci_bus * bus, int devfn)
```

```json
{
  "name": "pci_scan_slot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583551520,
      "name": "pci_scan_slot",
      "external": true,
      "loc": "drivers/pci/probe.c:1874",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_child_bus",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583551520,
      "name": "pci_scan_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int pci_scan_slot(struct pci_bus * bus, int devfn)
```

```json
{
  "name": "pci_scan_slot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583688080,
      "name": "pci_scan_slot",
      "external": true,
      "loc": "drivers/pci/probe.c:2024",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_child_bus",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583688080,
      "name": "pci_scan_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int pci_scan_slot(struct pci_bus * bus, int devfn)
```

```json
{
  "name": "pci_scan_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583728656,
      "name": "pci_scan_slot",
      "external": true,
      "loc": "drivers/pci/probe.c:2150",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_child_bus",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583728656,
      "name": "pci_scan_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int pci_scan_slot(struct pci_bus * bus, int devfn)
```

```json
{
  "name": "pci_scan_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583986768,
      "name": "pci_scan_slot",
      "external": true,
      "loc": "drivers/pci/probe.c:2286",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583986768,
      "name": "pci_scan_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
int pci_scan_slot(struct pci_bus * bus, int devfn)
```

```json
{
  "name": "pci_scan_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584180880,
      "name": "pci_scan_slot",
      "external": true,
      "loc": "drivers/pci/probe.c:2437",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584180880,
      "name": "pci_scan_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int pci_scan_slot(struct pci_bus * bus, int devfn)
```

```json
{
  "name": "pci_scan_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584269552,
      "name": "pci_scan_slot",
      "external": true,
      "loc": "drivers/pci/probe.c:2563",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584269552,
      "name": "pci_scan_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int pci_scan_slot(struct pci_bus * bus, int devfn)
```

```json
{
  "name": "pci_scan_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584460416,
      "name": "pci_scan_slot",
      "external": true,
      "loc": "drivers/pci/probe.c:2789",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584460416,
      "name": "pci_scan_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int pci_scan_slot(struct pci_bus * bus, int devfn)
```

```json
{
  "name": "pci_scan_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584595744,
      "name": "pci_scan_slot",
      "external": true,
      "loc": "drivers/pci/probe.c:2523",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584595744,
      "name": "pci_scan_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int pci_scan_slot(struct pci_bus * bus, int devfn)
```

```json
{
  "name": "pci_scan_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585273360,
      "name": "pci_scan_slot",
      "external": true,
      "loc": "drivers/pci/probe.c:2575",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585273360,
      "name": "pci_scan_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int pci_scan_slot(struct pci_bus * bus, int devfn)
```

```json
{
  "name": "pci_scan_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585431968,
      "name": "pci_scan_slot",
      "external": true,
      "loc": "drivers/pci/probe.c:2582",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585431968,
      "name": "pci_scan_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int pci_scan_slot(struct pci_bus * bus, int devfn)
```

```json
{
  "name": "pci_scan_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585312192,
      "name": "pci_scan_slot",
      "external": true,
      "loc": "drivers/pci/probe.c:2626",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585312192,
      "name": "pci_scan_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int pci_scan_slot(struct pci_bus * bus, int devfn)
```

```json
{
  "name": "pci_scan_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585768080,
      "name": "pci_scan_slot",
      "external": true,
      "loc": "drivers/pci/probe.c:2668",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585768080,
      "name": "pci_scan_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int pci_scan_slot(struct pci_bus * bus, int devfn)
```

```json
{
  "name": "pci_scan_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586953488,
      "name": "pci_scan_slot",
      "external": true,
      "loc": "drivers/pci/probe.c:2650",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586953488,
      "name": "pci_scan_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 439
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
int pci_scan_slot(struct pci_bus * bus, int devfn)
```

```json
{
  "name": "pci_scan_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588115504,
      "name": "pci_scan_slot",
      "external": true,
      "loc": "drivers/pci/probe.c:2662",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588115504,
      "name": "pci_scan_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 439
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
int pci_scan_slot(struct pci_bus * bus, int devfn)
```

```json
{
  "name": "pci_scan_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588390592,
      "name": "pci_scan_slot",
      "external": true,
      "loc": "drivers/pci/probe.c:2676",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588390592,
      "name": "pci_scan_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 445
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
int pci_scan_slot(struct pci_bus * bus, int devfn)
```

```json
{
  "name": "pci_scan_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588686528,
      "name": "pci_scan_slot",
      "external": true,
      "loc": "drivers/pci/probe.c:2725",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588686528,
      "name": "pci_scan_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 445
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
int pci_scan_slot(struct pci_bus * bus, int devfn)
```

```json
{
  "name": "pci_scan_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496837912,
      "name": "pci_scan_slot",
      "external": true,
      "loc": "drivers/pci/probe.c:2523",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496837912,
      "name": "pci_scan_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int pci_scan_slot(struct pci_bus * bus, int devfn)
```

```json
{
  "name": "pci_scan_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230118300,
      "name": "pci_scan_slot",
      "external": true,
      "loc": "drivers/pci/probe.c:2523",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_child_bus_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230118300,
      "name": "pci_scan_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int pci_scan_slot(struct pci_bus * bus, int devfn)
```

```json
{
  "name": "pci_scan_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290912560,
      "name": "pci_scan_slot",
      "external": true,
      "loc": "drivers/pci/probe.c:2523",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/pci-hotplug.c:pci_hp_add_devices",
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290912560,
      "name": "pci_scan_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int pci_scan_slot(struct pci_bus * bus, int devfn)
```

```json
{
  "name": "pci_scan_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275543340,
      "name": "pci_scan_slot",
      "external": true,
      "loc": "drivers/pci/probe.c:2523",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275543340,
      "name": "pci_scan_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int pci_scan_slot(struct pci_bus * bus, int devfn)
```

```json
{
  "name": "pci_scan_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584547904,
      "name": "pci_scan_slot",
      "external": true,
      "loc": "drivers/pci/probe.c:2523",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584547904,
      "name": "pci_scan_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int pci_scan_slot(struct pci_bus * bus, int devfn)
```

```json
{
  "name": "pci_scan_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584476064,
      "name": "pci_scan_slot",
      "external": true,
      "loc": "drivers/pci/probe.c:2523",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584476064,
      "name": "pci_scan_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int pci_scan_slot(struct pci_bus * bus, int devfn)
```

```json
{
  "name": "pci_scan_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584545904,
      "name": "pci_scan_slot",
      "external": true,
      "loc": "drivers/pci/probe.c:2523",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584545904,
      "name": "pci_scan_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int pci_scan_slot(struct pci_bus * bus, int devfn)
```

```json
{
  "name": "pci_scan_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584653648,
      "name": "pci_scan_slot",
      "external": true,
      "loc": "drivers/pci/probe.c:2523",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584653648,
      "name": "pci_scan_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
