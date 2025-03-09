# Function: <code>pci_remap_iospace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int pci_remap_iospace(const struct resource * res, phys_addr_t phys_addr)
```

```json
{
  "name": "pci_remap_iospace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583268192,
      "name": "pci_remap_iospace",
      "external": true,
      "loc": "drivers/pci/pci.c:3035",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583268192,
      "name": "pci_remap_iospace",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 62
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
int pci_remap_iospace(const struct resource * res, phys_addr_t phys_addr)
```

```json
{
  "name": "pci_remap_iospace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583578592,
      "name": "pci_remap_iospace",
      "external": true,
      "loc": "drivers/pci/pci.c:3328",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583578592,
      "name": "pci_remap_iospace",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 62
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
int pci_remap_iospace(const struct resource * res, phys_addr_t phys_addr)
```

```json
{
  "name": "pci_remap_iospace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583715648,
      "name": "pci_remap_iospace",
      "external": true,
      "loc": "drivers/pci/pci.c:3366",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583715648,
      "name": "pci_remap_iospace",
      "section": ".text",
      "bind": "STB_WEAK",
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
int pci_remap_iospace(const struct resource * res, phys_addr_t phys_addr)
```

```json
{
  "name": "pci_remap_iospace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583745328,
      "name": "pci_remap_iospace",
      "external": true,
      "loc": "drivers/pci/pci.c:3420",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583745328,
      "name": "pci_remap_iospace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int pci_remap_iospace(const struct resource * res, phys_addr_t phys_addr)
```

```json
{
  "name": "pci_remap_iospace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584003584,
      "name": "pci_remap_iospace",
      "external": true,
      "loc": "drivers/pci/pci.c:3435",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584003584,
      "name": "pci_remap_iospace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_remap_iospace(const struct resource * res, phys_addr_t phys_addr)
```

```json
{
  "name": "pci_remap_iospace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584198629,
      "name": "pci_remap_iospace",
      "external": true,
      "loc": "drivers/pci/pci.c:3581",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:devm_pci_remap_iospace"
      ],
      "caller_func": [
        "drivers/pci/pci.c:devm_pci_remap_iospace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584198496,
      "name": "pci_remap_iospace.part.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071584198528,
      "name": "pci_remap_iospace",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_remap_iospace(const struct resource * res, phys_addr_t phys_addr)
```

```json
{
  "name": "pci_remap_iospace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584288085,
      "name": "pci_remap_iospace",
      "external": true,
      "loc": "drivers/pci/pci.c:3846",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:devm_pci_remap_iospace"
      ],
      "caller_func": [
        "drivers/pci/pci.c:devm_pci_remap_iospace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584287952,
      "name": "pci_remap_iospace.part.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071584287984,
      "name": "pci_remap_iospace",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_remap_iospace(const struct resource * res, phys_addr_t phys_addr)
```

```json
{
  "name": "pci_remap_iospace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584482967,
      "name": "pci_remap_iospace",
      "external": true,
      "loc": "drivers/pci/pci.c:3942",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:devm_pci_remap_iospace"
      ],
      "caller_func": [
        "drivers/pci/pci.c:devm_pci_remap_iospace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584482832,
      "name": "pci_remap_iospace.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071584482864,
      "name": "pci_remap_iospace",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_remap_iospace(const struct resource * res, phys_addr_t phys_addr)
```

```json
{
  "name": "pci_remap_iospace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584618423,
      "name": "pci_remap_iospace",
      "external": true,
      "loc": "drivers/pci/pci.c:3938",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:devm_pci_remap_iospace"
      ],
      "caller_func": [
        "drivers/pci/pci.c:devm_pci_remap_iospace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584618288,
      "name": "pci_remap_iospace.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071584618320,
      "name": "pci_remap_iospace",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_remap_iospace(const struct resource * res, phys_addr_t phys_addr)
```

```json
{
  "name": "pci_remap_iospace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585292693,
      "name": "pci_remap_iospace",
      "external": true,
      "loc": "drivers/pci/pci.c:4009",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:devm_pci_remap_iospace",
        "drivers/pci/pci.c:devm_pci_remap_iospace"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585296352,
      "name": "pci_remap_iospace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int pci_remap_iospace(const struct resource * res, phys_addr_t phys_addr)
```

```json
{
  "name": "pci_remap_iospace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585447589,
      "name": "pci_remap_iospace",
      "external": true,
      "loc": "drivers/pci/pci.c:4077",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:devm_pci_remap_iospace",
        "drivers/pci/pci.c:devm_pci_remap_iospace"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585450928,
      "name": "pci_remap_iospace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int pci_remap_iospace(const struct resource * res, phys_addr_t phys_addr)
```

```json
{
  "name": "pci_remap_iospace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585327909,
      "name": "pci_remap_iospace",
      "external": true,
      "loc": "drivers/pci/pci.c:4109",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:devm_pci_remap_iospace",
        "drivers/pci/pci.c:devm_pci_remap_iospace"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585330992,
      "name": "pci_remap_iospace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_remap_iospace(const struct resource * res, phys_addr_t phys_addr)
```

```json
{
  "name": "pci_remap_iospace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585787469,
      "name": "pci_remap_iospace",
      "external": true,
      "loc": "drivers/pci/pci.c:4159",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:devm_pci_remap_iospace",
        "drivers/pci/pci.c:devm_pci_remap_iospace"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592363242,
      "name": "pci_remap_iospace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585784528,
      "name": "pci_remap_iospace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_remap_iospace(const struct resource * res, phys_addr_t phys_addr)
```

```json
{
  "name": "pci_remap_iospace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586974886,
      "name": "pci_remap_iospace",
      "external": true,
      "loc": "drivers/pci/pci.c:4254",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:devm_pci_remap_iospace",
        "drivers/pci/pci.c:devm_pci_remap_iospace"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594225423,
      "name": "pci_remap_iospace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071586972624,
      "name": "pci_remap_iospace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_remap_iospace(const struct resource * res, phys_addr_t phys_addr)
```

```json
{
  "name": "pci_remap_iospace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588140438,
      "name": "pci_remap_iospace",
      "external": true,
      "loc": "drivers/pci/pci.c:4197",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:devm_pci_remap_iospace",
        "drivers/pci/pci.c:devm_pci_remap_iospace"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596208101,
      "name": "pci_remap_iospace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071588138080,
      "name": "pci_remap_iospace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_remap_iospace(const struct resource * res, phys_addr_t phys_addr)
```

```json
{
  "name": "pci_remap_iospace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588414982,
      "name": "pci_remap_iospace",
      "external": true,
      "loc": "drivers/pci/pci.c:4235",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:devm_pci_remap_iospace",
        "drivers/pci/pci.c:devm_pci_remap_iospace"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596733229,
      "name": "pci_remap_iospace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071588413248,
      "name": "pci_remap_iospace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_remap_iospace(const struct resource * res, phys_addr_t phys_addr)
```

```json
{
  "name": "pci_remap_iospace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588710294,
      "name": "pci_remap_iospace",
      "external": true,
      "loc": "drivers/pci/pci.c:4345",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:devm_pci_remap_iospace",
        "drivers/pci/pci.c:devm_pci_remap_iospace"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597641685,
      "name": "pci_remap_iospace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071588708640,
      "name": "pci_remap_iospace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int pci_remap_iospace(const struct resource * res, phys_addr_t phys_addr)
```

```json
{
  "name": "pci_remap_iospace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496864400,
      "name": "pci_remap_iospace",
      "external": true,
      "loc": "drivers/pci/pci.c:3938",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:devm_pci_remap_iospace",
        "drivers/acpi/pci_root.c:acpi_pci_probe_root_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496864400,
      "name": "pci_remap_iospace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int pci_remap_iospace(const struct resource * res, phys_addr_t phys_addr)
```

```json
{
  "name": "pci_remap_iospace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230132796,
      "name": "pci_remap_iospace",
      "external": true,
      "loc": "drivers/pci/pci.c:3938",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:devm_pci_remap_iospace",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230132796,
      "name": "pci_remap_iospace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_remap_iospace(const struct resource * res, phys_addr_t phys_addr)
```

```json
{
  "name": "pci_remap_iospace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290941392,
      "name": "pci_remap_iospace",
      "external": true,
      "loc": "drivers/pci/pci.c:3938",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:devm_pci_remap_iospace"
      ],
      "caller_func": [
        "drivers/pci/pci.c:devm_pci_remap_iospace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290941152,
      "name": "pci_remap_iospace.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 13835058055290941232,
      "name": "pci_remap_iospace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int pci_remap_iospace(const struct resource * res, phys_addr_t phys_addr)
```

```json
{
  "name": "pci_remap_iospace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275555578,
      "name": "pci_remap_iospace",
      "external": true,
      "loc": "drivers/pci/pci.c:3938",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:devm_pci_remap_iospace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275555578,
      "name": "pci_remap_iospace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_remap_iospace(const struct resource * res, phys_addr_t phys_addr)
```

```json
{
  "name": "pci_remap_iospace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584570583,
      "name": "pci_remap_iospace",
      "external": true,
      "loc": "drivers/pci/pci.c:3938",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:devm_pci_remap_iospace"
      ],
      "caller_func": [
        "drivers/pci/pci.c:devm_pci_remap_iospace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584570448,
      "name": "pci_remap_iospace.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071584570480,
      "name": "pci_remap_iospace",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_remap_iospace(const struct resource * res, phys_addr_t phys_addr)
```

```json
{
  "name": "pci_remap_iospace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584498743,
      "name": "pci_remap_iospace",
      "external": true,
      "loc": "drivers/pci/pci.c:3938",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:devm_pci_remap_iospace"
      ],
      "caller_func": [
        "drivers/pci/pci.c:devm_pci_remap_iospace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584498608,
      "name": "pci_remap_iospace.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071584498640,
      "name": "pci_remap_iospace",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_remap_iospace(const struct resource * res, phys_addr_t phys_addr)
```

```json
{
  "name": "pci_remap_iospace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584568583,
      "name": "pci_remap_iospace",
      "external": true,
      "loc": "drivers/pci/pci.c:3938",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:devm_pci_remap_iospace"
      ],
      "caller_func": [
        "drivers/pci/pci.c:devm_pci_remap_iospace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584568448,
      "name": "pci_remap_iospace.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071584568480,
      "name": "pci_remap_iospace",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_remap_iospace(const struct resource * res, phys_addr_t phys_addr)
```

```json
{
  "name": "pci_remap_iospace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584676567,
      "name": "pci_remap_iospace",
      "external": true,
      "loc": "drivers/pci/pci.c:3938",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:devm_pci_remap_iospace"
      ],
      "caller_func": [
        "drivers/pci/pci.c:devm_pci_remap_iospace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584676432,
      "name": "pci_remap_iospace.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071584676464,
      "name": "pci_remap_iospace",
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
