# Function: <code>pci_alloc_host_bridge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_alloc_host_bridge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583244132,
      "name": "pci_alloc_host_bridge",
      "external": false,
      "loc": "drivers/pci/probe.c:521",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_create_root_bus"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_alloc_host_bridge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583553447,
      "name": "pci_alloc_host_bridge",
      "external": false,
      "loc": "drivers/pci/probe.c:524",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_create_root_bus"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pci_host_bridge * pci_alloc_host_bridge(size_t priv)
```

```json
{
  "name": "pci_alloc_host_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583690923,
      "name": "pci_alloc_host_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:525",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_create_root_bus_msi"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583682800,
      "name": "pci_alloc_host_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
struct pci_host_bridge * pci_alloc_host_bridge(size_t priv)
```

```json
{
  "name": "pci_alloc_host_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583731451,
      "name": "pci_alloc_host_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:527",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_create_root_bus"
      ],
      "caller_func": [
        "drivers/pci/dwc/pcie-designware-host.c:dw_pcie_host_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583723504,
      "name": "pci_alloc_host_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct pci_host_bridge * pci_alloc_host_bridge(size_t priv)
```

```json
{
  "name": "pci_alloc_host_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583989547,
      "name": "pci_alloc_host_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:527",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_create_root_bus"
      ],
      "caller_func": [
        "drivers/pci/dwc/pcie-designware-host.c:dw_pcie_host_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583979840,
      "name": "pci_alloc_host_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct pci_host_bridge * pci_alloc_host_bridge(size_t priv)
```

```json
{
  "name": "pci_alloc_host_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584173520,
      "name": "pci_alloc_host_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:539",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_create_root_bus",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584173520,
      "name": "pci_alloc_host_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct pci_host_bridge * pci_alloc_host_bridge(size_t priv)
```

```json
{
  "name": "pci_alloc_host_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584261360,
      "name": "pci_alloc_host_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:538",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_create_root_bus",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584261360,
      "name": "pci_alloc_host_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct pci_host_bridge * pci_alloc_host_bridge(size_t priv)
```

```json
{
  "name": "pci_alloc_host_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584455712,
      "name": "pci_alloc_host_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:606",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_create_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584455712,
      "name": "pci_alloc_host_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
struct pci_host_bridge * pci_alloc_host_bridge(size_t priv)
```

```json
{
  "name": "pci_alloc_host_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584590992,
      "name": "pci_alloc_host_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:602",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_create_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584590992,
      "name": "pci_alloc_host_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
struct pci_host_bridge * pci_alloc_host_bridge(size_t priv)
```

```json
{
  "name": "pci_alloc_host_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585275301,
      "name": "pci_alloc_host_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:601",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_create_root_bus",
        "drivers/pci/probe.c:devm_pci_alloc_host_bridge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585269552,
      "name": "pci_alloc_host_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
struct pci_host_bridge * pci_alloc_host_bridge(size_t priv)
```

```json
{
  "name": "pci_alloc_host_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585434005,
      "name": "pci_alloc_host_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:601",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_create_root_bus",
        "drivers/pci/probe.c:devm_pci_alloc_host_bridge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585427424,
      "name": "pci_alloc_host_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
struct pci_host_bridge * pci_alloc_host_bridge(size_t priv)
```

```json
{
  "name": "pci_alloc_host_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585305472,
      "name": "pci_alloc_host_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:602",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_create_root_bus",
        "drivers/pci/probe.c:devm_pci_alloc_host_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585305472,
      "name": "pci_alloc_host_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
struct pci_host_bridge * pci_alloc_host_bridge(size_t priv)
```

```json
{
  "name": "pci_alloc_host_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585762640,
      "name": "pci_alloc_host_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:604",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_create_root_bus",
        "drivers/pci/probe.c:devm_pci_alloc_host_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585762640,
      "name": "pci_alloc_host_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
struct pci_host_bridge * pci_alloc_host_bridge(size_t priv)
```

```json
{
  "name": "pci_alloc_host_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586947728,
      "name": "pci_alloc_host_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:603",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_create_root_bus",
        "drivers/pci/probe.c:devm_pci_alloc_host_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586947728,
      "name": "pci_alloc_host_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct pci_host_bridge * pci_alloc_host_bridge(size_t priv)
```

```json
{
  "name": "pci_alloc_host_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588106672,
      "name": "pci_alloc_host_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:603",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_create_root_bus",
        "drivers/pci/probe.c:devm_pci_alloc_host_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588106672,
      "name": "pci_alloc_host_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct pci_host_bridge * pci_alloc_host_bridge(size_t priv)
```

```json
{
  "name": "pci_alloc_host_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588381280,
      "name": "pci_alloc_host_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:604",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_create_root_bus",
        "drivers/pci/probe.c:devm_pci_alloc_host_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588381280,
      "name": "pci_alloc_host_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct pci_host_bridge * pci_alloc_host_bridge(size_t priv)
```

```json
{
  "name": "pci_alloc_host_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588678960,
      "name": "pci_alloc_host_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:615",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_create_root_bus",
        "drivers/pci/probe.c:devm_pci_alloc_host_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588678960,
      "name": "pci_alloc_host_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct pci_host_bridge * pci_alloc_host_bridge(size_t priv)
```

```json
{
  "name": "pci_alloc_host_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496830360,
      "name": "pci_alloc_host_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:602",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_create_root_bus",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496830360,
      "name": "pci_alloc_host_bridge",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pci_host_bridge * pci_alloc_host_bridge(size_t priv)
```

```json
{
  "name": "pci_alloc_host_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230110364,
      "name": "pci_alloc_host_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:602",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/bios32.c:pci_common_init_dev",
        "drivers/pci/probe.c:pci_create_root_bus",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pci-v3-semi.c:v3_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230110364,
      "name": "pci_alloc_host_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct pci_host_bridge * pci_alloc_host_bridge(size_t priv)
```

```json
{
  "name": "pci_alloc_host_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290903168,
      "name": "pci_alloc_host_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:602",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_create_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290903168,
      "name": "pci_alloc_host_bridge",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct pci_host_bridge * pci_alloc_host_bridge(size_t priv)
```

```json
{
  "name": "pci_alloc_host_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275536424,
      "name": "pci_alloc_host_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:602",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_create_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275536424,
      "name": "pci_alloc_host_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct pci_host_bridge * pci_alloc_host_bridge(size_t priv)
```

```json
{
  "name": "pci_alloc_host_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584543152,
      "name": "pci_alloc_host_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:602",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_create_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584543152,
      "name": "pci_alloc_host_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
struct pci_host_bridge * pci_alloc_host_bridge(size_t priv)
```

```json
{
  "name": "pci_alloc_host_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584471312,
      "name": "pci_alloc_host_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:602",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_create_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584471312,
      "name": "pci_alloc_host_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
struct pci_host_bridge * pci_alloc_host_bridge(size_t priv)
```

```json
{
  "name": "pci_alloc_host_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584541152,
      "name": "pci_alloc_host_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:602",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_create_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584541152,
      "name": "pci_alloc_host_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
struct pci_host_bridge * pci_alloc_host_bridge(size_t priv)
```

```json
{
  "name": "pci_alloc_host_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584648896,
      "name": "pci_alloc_host_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:602",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_create_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584648896,
      "name": "pci_alloc_host_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
struct pci_host_bridge * pci_alloc_host_bridge(size_t priv)
```
</details>
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
