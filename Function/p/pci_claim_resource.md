# Function: <code>pci_claim_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int pci_claim_resource(struct pci_dev * dev, int resource)
```

```json
{
  "name": "pci_claim_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583289840,
      "name": "pci_claim_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:113",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_claim_bridge_resource",
        "drivers/pci/setup-bus.c:pci_claim_bridge_resource",
        "drivers/pci/quirks.c:quirk_io_region",
        "arch/x86/pci/i386.c:pcibios_allocate_rom_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583289840,
      "name": "pci_claim_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int pci_claim_resource(struct pci_dev * dev, int resource)
```

```json
{
  "name": "pci_claim_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583600736,
      "name": "pci_claim_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:113",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources",
        "drivers/pci/quirks.c:quirk_io_region",
        "arch/x86/pci/i386.c:pcibios_allocate_rom_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583600736,
      "name": "pci_claim_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int pci_claim_resource(struct pci_dev * dev, int resource)
```

```json
{
  "name": "pci_claim_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583737904,
      "name": "pci_claim_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:133",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources",
        "drivers/pci/quirks.c:quirk_io_region",
        "arch/x86/pci/i386.c:pcibios_allocate_rom_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583737904,
      "name": "pci_claim_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
int pci_claim_resource(struct pci_dev * dev, int resource)
```

```json
{
  "name": "pci_claim_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583779712,
      "name": "pci_claim_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:133",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources",
        "drivers/pci/quirks.c:quirk_io_region",
        "arch/x86/pci/i386.c:pcibios_allocate_rom_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583779712,
      "name": "pci_claim_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int pci_claim_resource(struct pci_dev * dev, int resource)
```

```json
{
  "name": "pci_claim_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584039872,
      "name": "pci_claim_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:134",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources",
        "drivers/pci/quirks.c:quirk_io_region",
        "arch/x86/pci/i386.c:pcibios_allocate_rom_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584039872,
      "name": "pci_claim_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int pci_claim_resource(struct pci_dev * dev, int resource)
```

```json
{
  "name": "pci_claim_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584236656,
      "name": "pci_claim_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:130",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources",
        "drivers/pci/quirks.c:quirk_io_region",
        "arch/x86/pci/i386.c:pcibios_allocate_rom_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584236656,
      "name": "pci_claim_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int pci_claim_resource(struct pci_dev * dev, int resource)
```

```json
{
  "name": "pci_claim_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584326384,
      "name": "pci_claim_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:130",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources",
        "drivers/pci/quirks.c:quirk_io_region",
        "arch/x86/pci/i386.c:pcibios_allocate_rom_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584326384,
      "name": "pci_claim_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int pci_claim_resource(struct pci_dev * dev, int resource)
```

```json
{
  "name": "pci_claim_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_claim_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:130",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources",
        "drivers/pci/quirks.c:quirk_io_region",
        "arch/x86/pci/i386.c:pcibios_allocate_rom_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584523506,
      "name": "pci_claim_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071584521584,
      "name": "pci_claim_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int pci_claim_resource(struct pci_dev * dev, int resource)
```

```json
{
  "name": "pci_claim_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_claim_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:130",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources",
        "drivers/pci/quirks.c:quirk_io_region",
        "arch/x86/pci/i386.c:pcibios_allocate_rom_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584658626,
      "name": "pci_claim_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071584656704,
      "name": "pci_claim_resource",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int pci_claim_resource(struct pci_dev * dev, int resource)
```

```json
{
  "name": "pci_claim_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_claim_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:130",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources",
        "drivers/pci/quirks.c:quirk_io_region",
        "arch/x86/pci/i386.c:pcibios_allocate_rom_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_dev_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585342777,
      "name": "pci_claim_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071585341088,
      "name": "pci_claim_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int pci_claim_resource(struct pci_dev * dev, int resource)
```

```json
{
  "name": "pci_claim_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_claim_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:131",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources",
        "drivers/pci/quirks.c:quirk_io_region",
        "arch/x86/pci/i386.c:pcibios_allocate_rom_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_dev_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591395861,
      "name": "pci_claim_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071585494176,
      "name": "pci_claim_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int pci_claim_resource(struct pci_dev * dev, int resource)
```

```json
{
  "name": "pci_claim_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_claim_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:131",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources",
        "drivers/pci/quirks.c:quirk_io_region",
        "arch/x86/pci/i386.c:pcibios_allocate_rom_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_dev_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591338164,
      "name": "pci_claim_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071585373712,
      "name": "pci_claim_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int pci_claim_resource(struct pci_dev * dev, int resource)
```

```json
{
  "name": "pci_claim_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_claim_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:131",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources",
        "drivers/pci/quirks.c:quirk_io_region",
        "arch/x86/pci/i386.c:pcibios_allocate_rom_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_dev_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592365747,
      "name": "pci_claim_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071585834464,
      "name": "pci_claim_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int pci_claim_resource(struct pci_dev * dev, int resource)
```

```json
{
  "name": "pci_claim_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_claim_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:135",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources",
        "drivers/pci/setup-bus.c:pci_claim_bridge_resource",
        "drivers/pci/setup-bus.c:pci_claim_bridge_resource",
        "drivers/pci/quirks.c:quirk_io_region",
        "arch/x86/pci/i386.c:pcibios_allocate_rom_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_dev_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594228030,
      "name": "pci_claim_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071587026112,
      "name": "pci_claim_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int pci_claim_resource(struct pci_dev * dev, int resource)
```

```json
{
  "name": "pci_claim_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588202928,
      "name": "pci_claim_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:135",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources",
        "drivers/pci/setup-bus.c:pci_claim_bridge_resource",
        "drivers/pci/setup-bus.c:pci_claim_bridge_resource",
        "drivers/pci/quirks.c:quirk_io_region",
        "arch/x86/pci/i386.c:pcibios_allocate_rom_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_dev_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588202928,
      "name": "pci_claim_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
int pci_claim_resource(struct pci_dev * dev, int resource)
```

```json
{
  "name": "pci_claim_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588478608,
      "name": "pci_claim_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:135",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources",
        "drivers/pci/setup-bus.c:pci_claim_bridge_resource",
        "drivers/pci/setup-bus.c:pci_claim_bridge_resource",
        "drivers/pci/quirks.c:quirk_io_region",
        "arch/x86/pci/i386.c:pcibios_allocate_rom_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_dev_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588478608,
      "name": "pci_claim_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
int pci_claim_resource(struct pci_dev * dev, int resource)
```

```json
{
  "name": "pci_claim_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588775952,
      "name": "pci_claim_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:136",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources",
        "drivers/pci/setup-bus.c:pci_claim_bridge_resource",
        "drivers/pci/setup-bus.c:pci_claim_bridge_resource",
        "drivers/pci/quirks.c:quirk_io_region",
        "arch/x86/pci/i386.c:pcibios_allocate_rom_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_dev_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588775952,
      "name": "pci_claim_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
int pci_claim_resource(struct pci_dev * dev, int resource)
```

```json
{
  "name": "pci_claim_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496904704,
      "name": "pci_claim_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:130",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources",
        "drivers/pci/quirks.c:quirk_io_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496904704,
      "name": "pci_claim_resource",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int pci_claim_resource(struct pci_dev * dev, int resource)
```

```json
{
  "name": "pci_claim_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230180760,
      "name": "pci_claim_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:130",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources",
        "drivers/pci/quirks.c:quirk_io_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230180760,
      "name": "pci_claim_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int pci_claim_resource(struct pci_dev * dev, int resource)
```

```json
{
  "name": "pci_claim_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290997840,
      "name": "pci_claim_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:130",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/pci-common.c:pcibios_claim_one_bus",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources",
        "drivers/pci/quirks.c:quirk_io_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290997840,
      "name": "pci_claim_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int pci_claim_resource(struct pci_dev * dev, int resource)
```

```json
{
  "name": "pci_claim_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275593214,
      "name": "pci_claim_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:130",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources",
        "drivers/pci/quirks.c:quirk_io_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275593214,
      "name": "pci_claim_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int pci_claim_resource(struct pci_dev * dev, int resource)
```

```json
{
  "name": "pci_claim_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_claim_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:130",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources",
        "drivers/pci/quirks.c:quirk_io_region",
        "arch/x86/pci/i386.c:pcibios_allocate_rom_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584609090,
      "name": "pci_claim_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071584607168,
      "name": "pci_claim_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int pci_claim_resource(struct pci_dev * dev, int resource)
```

```json
{
  "name": "pci_claim_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_claim_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:130",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources",
        "drivers/pci/quirks.c:quirk_io_region",
        "arch/x86/pci/i386.c:pcibios_allocate_rom_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584538914,
      "name": "pci_claim_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071584536992,
      "name": "pci_claim_resource",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int pci_claim_resource(struct pci_dev * dev, int resource)
```

```json
{
  "name": "pci_claim_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_claim_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:130",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources",
        "drivers/pci/quirks.c:quirk_io_region",
        "arch/x86/pci/i386.c:pcibios_allocate_rom_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584608786,
      "name": "pci_claim_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071584606864,
      "name": "pci_claim_resource",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int pci_claim_resource(struct pci_dev * dev, int resource)
```

```json
{
  "name": "pci_claim_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_claim_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:130",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources",
        "drivers/pci/quirks.c:quirk_io_region",
        "arch/x86/pci/i386.c:pcibios_allocate_rom_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584716482,
      "name": "pci_claim_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071584714560,
      "name": "pci_claim_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
