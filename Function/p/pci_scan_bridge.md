# Function: <code>pci_scan_bridge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int pci_scan_bridge(struct pci_bus * bus, struct pci_dev * dev, int max, int pass)
```

```json
{
  "name": "pci_scan_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583245344,
      "name": "pci_scan_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:818",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_child_bus",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583245344,
      "name": "pci_scan_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1657
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
int pci_scan_bridge(struct pci_bus * bus, struct pci_dev * dev, int max, int pass)
```

```json
{
  "name": "pci_scan_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583554624,
      "name": "pci_scan_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:827",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_child_bus",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583554624,
      "name": "pci_scan_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1689
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
int pci_scan_bridge(struct pci_bus * bus, struct pci_dev * dev, int max, int pass)
```

```json
{
  "name": "pci_scan_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583691520,
      "name": "pci_scan_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:946",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_child_bus",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583691520,
      "name": "pci_scan_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1689
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
int pci_scan_bridge(struct pci_bus * bus, struct pci_dev * dev, int max, int pass)
```

```json
{
  "name": "pci_scan_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583731984,
      "name": "pci_scan_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:972",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_child_bus",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583731984,
      "name": "pci_scan_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1585
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
int pci_scan_bridge(struct pci_bus * bus, struct pci_dev * dev, int max, int pass)
```

```json
{
  "name": "pci_scan_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583992755,
      "name": "pci_scan_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:1209",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583991696,
      "name": "pci_scan_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int pci_scan_bridge(struct pci_bus * bus, struct pci_dev * dev, int max, int pass)
```

```json
{
  "name": "pci_scan_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584186864,
      "name": "pci_scan_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:1286",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584185712,
      "name": "pci_scan_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int pci_scan_bridge(struct pci_bus * bus, struct pci_dev * dev, int max, int pass)
```

```json
{
  "name": "pci_scan_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584275568,
      "name": "pci_scan_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:1286",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584274416,
      "name": "pci_scan_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int pci_scan_bridge(struct pci_bus * bus, struct pci_dev * dev, int max, int pass)
```

```json
{
  "name": "pci_scan_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584465904,
      "name": "pci_scan_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:1389",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584464752,
      "name": "pci_scan_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int pci_scan_bridge(struct pci_bus * bus, struct pci_dev * dev, int max, int pass)
```

```json
{
  "name": "pci_scan_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584601280,
      "name": "pci_scan_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:1391",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584600128,
      "name": "pci_scan_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int pci_scan_bridge(struct pci_bus * bus, struct pci_dev * dev, int max, int pass)
```

```json
{
  "name": "pci_scan_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585278640,
      "name": "pci_scan_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:1439",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585277488,
      "name": "pci_scan_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int pci_scan_bridge(struct pci_bus * bus, struct pci_dev * dev, int max, int pass)
```

```json
{
  "name": "pci_scan_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585437344,
      "name": "pci_scan_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:1458",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585436192,
      "name": "pci_scan_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int pci_scan_bridge(struct pci_bus * bus, struct pci_dev * dev, int max, int pass)
```

```json
{
  "name": "pci_scan_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585317472,
      "name": "pci_scan_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:1501",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585316320,
      "name": "pci_scan_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int pci_scan_bridge(struct pci_bus * bus, struct pci_dev * dev, int max, int pass)
```

```json
{
  "name": "pci_scan_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585773360,
      "name": "pci_scan_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:1510",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585772208,
      "name": "pci_scan_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int pci_scan_bridge(struct pci_bus * bus, struct pci_dev * dev, int max, int pass)
```

```json
{
  "name": "pci_scan_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586959112,
      "name": "pci_scan_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:1491",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586957952,
      "name": "pci_scan_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int pci_scan_bridge(struct pci_bus * bus, struct pci_dev * dev, int max, int pass)
```

```json
{
  "name": "pci_scan_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588122280,
      "name": "pci_scan_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:1497",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588121056,
      "name": "pci_scan_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int pci_scan_bridge(struct pci_bus * bus, struct pci_dev * dev, int max, int pass)
```

```json
{
  "name": "pci_scan_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588397544,
      "name": "pci_scan_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:1500",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588396320,
      "name": "pci_scan_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int pci_scan_bridge(struct pci_bus * bus, struct pci_dev * dev, int max, int pass)
```

```json
{
  "name": "pci_scan_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588693528,
      "name": "pci_scan_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:1511",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588692304,
      "name": "pci_scan_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int pci_scan_bridge(struct pci_bus * bus, struct pci_dev * dev, int max, int pass)
```

```json
{
  "name": "pci_scan_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496843880,
      "name": "pci_scan_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:1391",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496842528,
      "name": "pci_scan_bridge",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int pci_scan_bridge(struct pci_bus * bus, struct pci_dev * dev, int max, int pass)
```

```json
{
  "name": "pci_scan_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230124504,
      "name": "pci_scan_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:1391",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230123172,
      "name": "pci_scan_bridge",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int pci_scan_bridge(struct pci_bus * bus, struct pci_dev * dev, int max, int pass)
```

```json
{
  "name": "pci_scan_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290920336,
      "name": "pci_scan_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:1391",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge"
      ],
      "caller_func": [
        "arch/powerpc/kernel/pci-hotplug.c:pci_hp_add_devices",
        "arch/powerpc/kernel/pci-hotplug.c:pci_hp_add_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290918608,
      "name": "pci_scan_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int pci_scan_bridge(struct pci_bus * bus, struct pci_dev * dev, int max, int pass)
```

```json
{
  "name": "pci_scan_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275548578,
      "name": "pci_scan_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:1391",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275547360,
      "name": "pci_scan_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int pci_scan_bridge(struct pci_bus * bus, struct pci_dev * dev, int max, int pass)
```

```json
{
  "name": "pci_scan_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584553440,
      "name": "pci_scan_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:1391",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584552288,
      "name": "pci_scan_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int pci_scan_bridge(struct pci_bus * bus, struct pci_dev * dev, int max, int pass)
```

```json
{
  "name": "pci_scan_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584481600,
      "name": "pci_scan_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:1391",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584480448,
      "name": "pci_scan_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int pci_scan_bridge(struct pci_bus * bus, struct pci_dev * dev, int max, int pass)
```

```json
{
  "name": "pci_scan_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584551440,
      "name": "pci_scan_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:1391",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584550288,
      "name": "pci_scan_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int pci_scan_bridge(struct pci_bus * bus, struct pci_dev * dev, int max, int pass)
```

```json
{
  "name": "pci_scan_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584659184,
      "name": "pci_scan_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:1391",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584658032,
      "name": "pci_scan_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
