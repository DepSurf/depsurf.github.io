# Function: <code>pci_scan_child_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int pci_scan_child_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_scan_child_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583247008,
      "name": "pci_scan_child_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2029",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_msi",
        "drivers/pci/probe.c:pci_scan_root_bus_msi",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583247008,
      "name": "pci_scan_child_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
unsigned int pci_scan_child_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_scan_child_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583556320,
      "name": "pci_scan_child_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2058",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_msi",
        "drivers/pci/probe.c:pci_scan_root_bus_msi",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583556320,
      "name": "pci_scan_child_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
unsigned int pci_scan_child_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_scan_child_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583693216,
      "name": "pci_scan_child_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2208",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_msi",
        "drivers/pci/probe.c:pci_scan_root_bus_msi",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583693216,
      "name": "pci_scan_child_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
unsigned int pci_scan_child_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_scan_child_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583733584,
      "name": "pci_scan_child_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2334",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583733584,
      "name": "pci_scan_child_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
unsigned int pci_scan_child_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_scan_child_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583992614,
      "name": "pci_scan_child_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2606",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583992384,
      "name": "pci_scan_child_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int pci_scan_child_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_scan_child_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584186725,
      "name": "pci_scan_child_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2790",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584186496,
      "name": "pci_scan_child_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int pci_scan_child_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_scan_child_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584275429,
      "name": "pci_scan_child_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2916",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584275200,
      "name": "pci_scan_child_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int pci_scan_child_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_scan_child_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584465765,
      "name": "pci_scan_child_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:3142",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584465536,
      "name": "pci_scan_child_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int pci_scan_child_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_scan_child_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584601141,
      "name": "pci_scan_child_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2876",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584600912,
      "name": "pci_scan_child_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int pci_scan_child_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_scan_child_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585278501,
      "name": "pci_scan_child_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2928",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend"
      ],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585278272,
      "name": "pci_scan_child_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int pci_scan_child_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_scan_child_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585437218,
      "name": "pci_scan_child_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2935",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend"
      ],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585436976,
      "name": "pci_scan_child_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int pci_scan_child_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_scan_child_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585317346,
      "name": "pci_scan_child_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2979",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend"
      ],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585317104,
      "name": "pci_scan_child_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int pci_scan_child_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_scan_child_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585773234,
      "name": "pci_scan_child_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:3021",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend"
      ],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585772992,
      "name": "pci_scan_child_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int pci_scan_child_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_scan_child_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586958965,
      "name": "pci_scan_child_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2992",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend"
      ],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586958720,
      "name": "pci_scan_child_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
unsigned int pci_scan_child_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_scan_child_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588122117,
      "name": "pci_scan_child_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:3002",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge"
      ],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588121840,
      "name": "pci_scan_child_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
unsigned int pci_scan_child_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_scan_child_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588397381,
      "name": "pci_scan_child_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:3016",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge"
      ],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588397104,
      "name": "pci_scan_child_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
unsigned int pci_scan_child_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_scan_child_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588693365,
      "name": "pci_scan_child_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:3065",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge"
      ],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588693088,
      "name": "pci_scan_child_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
unsigned int pci_scan_child_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_scan_child_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496843744,
      "name": "pci_scan_child_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2876",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496843464,
      "name": "pci_scan_child_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
unsigned int pci_scan_child_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_scan_child_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230124380,
      "name": "pci_scan_child_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2876",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bridge_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230124120,
      "name": "pci_scan_child_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
unsigned int pci_scan_child_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_scan_child_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290920132,
      "name": "pci_scan_child_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2876",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge"
      ],
      "caller_func": [
        "arch/powerpc/kernel/pci-common.c:pcibios_scan_phb",
        "arch/powerpc/kernel/pci_of_scan.c:of_scan_pci_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290919808,
      "name": "pci_scan_child_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
unsigned int pci_scan_child_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_scan_child_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275548460,
      "name": "pci_scan_child_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2876",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275548214,
      "name": "pci_scan_child_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int pci_scan_child_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_scan_child_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584553301,
      "name": "pci_scan_child_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2876",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584553072,
      "name": "pci_scan_child_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int pci_scan_child_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_scan_child_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584481461,
      "name": "pci_scan_child_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2876",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584481232,
      "name": "pci_scan_child_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int pci_scan_child_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_scan_child_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584551301,
      "name": "pci_scan_child_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2876",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584551072,
      "name": "pci_scan_child_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int pci_scan_child_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_scan_child_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584659045,
      "name": "pci_scan_child_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2876",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584658816,
      "name": "pci_scan_child_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
