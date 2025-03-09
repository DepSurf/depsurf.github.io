# Function: <code>pcie_has_flr</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_has_flr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583758030,
      "name": "pcie_has_flr",
      "external": false,
      "loc": "drivers/pci/pci.c:3881",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_has_flr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584017390,
      "name": "pcie_has_flr",
      "external": false,
      "loc": "drivers/pci/pci.c:3918",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_has_flr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584214247,
      "name": "pcie_has_flr",
      "external": false,
      "loc": "drivers/pci/pci.c:4119",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_function"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool pcie_has_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_has_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584304247,
      "name": "pcie_has_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4384",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584288464,
      "name": "pcie_has_flr.part.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071584288544,
      "name": "pcie_has_flr",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool pcie_has_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_has_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584497960,
      "name": "pcie_has_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4481",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584483344,
      "name": "pcie_has_flr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071584483424,
      "name": "pcie_has_flr",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool pcie_has_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_has_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584633864,
      "name": "pcie_has_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4477",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584618800,
      "name": "pcie_has_flr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071584618880,
      "name": "pcie_has_flr",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool pcie_has_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_has_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585316625,
      "name": "pcie_has_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4507",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_function",
        "drivers/pci/pci.c:pci_probe_reset_function"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585292752,
      "name": "pcie_has_flr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
bool pcie_has_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_has_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585471553,
      "name": "pcie_has_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4582",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_function",
        "drivers/pci/pci.c:pci_probe_reset_function"
      ],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_root_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585447648,
      "name": "pcie_has_flr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
bool pcie_has_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_has_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585351473,
      "name": "pcie_has_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4631",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_function",
        "drivers/pci/pci.c:pci_probe_reset_function"
      ],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_root_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585327968,
      "name": "pcie_has_flr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
bool pcie_has_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_has_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496880408,
      "name": "pcie_has_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4477",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496859776,
      "name": "pcie_has_flr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446603336496859872,
      "name": "pcie_has_flr",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
bool pcie_has_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_has_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230157500,
      "name": "pcie_has_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4477",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230140320,
      "name": "pcie_has_flr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 3230140420,
      "name": "pcie_has_flr",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
bool pcie_has_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_has_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290964960,
      "name": "pcie_has_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4477",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290942064,
      "name": "pcie_has_flr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 13835058055290942176,
      "name": "pcie_has_flr",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
bool pcie_has_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_has_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275578368,
      "name": "pcie_has_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4477",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275562130,
      "name": "pcie_has_flr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446743936275562188,
      "name": "pcie_has_flr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
bool pcie_has_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_has_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584586024,
      "name": "pcie_has_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4477",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584570960,
      "name": "pcie_has_flr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071584571040,
      "name": "pcie_has_flr",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool pcie_has_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_has_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584514152,
      "name": "pcie_has_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4477",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584499120,
      "name": "pcie_has_flr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071584499200,
      "name": "pcie_has_flr",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool pcie_has_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_has_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584584024,
      "name": "pcie_has_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4477",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584568960,
      "name": "pcie_has_flr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071584569040,
      "name": "pcie_has_flr",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool pcie_has_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_has_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584691696,
      "name": "pcie_has_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4477",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584676944,
      "name": "pcie_has_flr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071584677024,
      "name": "pcie_has_flr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
bool pcie_has_flr(struct pci_dev * dev)
```
</details>
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
bool pcie_has_flr(struct pci_dev * dev)
```
</details>
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
