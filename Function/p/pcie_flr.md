# Function: <code>pcie_flr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_flr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583269490,
      "name": "pcie_flr",
      "external": false,
      "loc": "drivers/pci/pci.c:3417",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_flr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583579922,
      "name": "pcie_flr",
      "external": false,
      "loc": "drivers/pci/pci.c:3738",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_flr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583716978,
      "name": "pcie_flr",
      "external": false,
      "loc": "drivers/pci/pci.c:3776",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void pcie_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_flr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583748976,
      "name": "pcie_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:3900",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583748976,
      "name": "pcie_flr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void pcie_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_flr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584008000,
      "name": "pcie_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:3937",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584008000,
      "name": "pcie_flr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int pcie_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_flr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584203520,
      "name": "pcie_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4138",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584203520,
      "name": "pcie_flr",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pcie_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584291792,
      "name": "pcie_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4404",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584291792,
      "name": "pcie_flr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int pcie_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584486056,
      "name": "pcie_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4501",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584500431,
      "name": "pcie_flr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071584486000,
      "name": "pcie_flr",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pcie_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584621672,
      "name": "pcie_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4497",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584636394,
      "name": "pcie_flr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071584621616,
      "name": "pcie_flr",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pcie_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585299759,
      "name": "pcie_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4527",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585320012,
      "name": "pcie_flr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071585299680,
      "name": "pcie_flr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pcie_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585454543,
      "name": "pcie_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4602",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_root_reset",
        "drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591394771,
      "name": "pcie_flr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071585454464,
      "name": "pcie_flr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pcie_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585334623,
      "name": "pcie_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4651",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_root_reset",
        "drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591337082,
      "name": "pcie_flr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071585334544,
      "name": "pcie_flr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
int pcie_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585792735,
      "name": "pcie_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4681",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_reset_flr",
        "drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592363897,
      "name": "pcie_flr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071585792656,
      "name": "pcie_flr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
int pcie_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586980527,
      "name": "pcie_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4777",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_reset_flr",
        "drivers/pci/quirks.c:reset_hinic_vf_dev",
        "drivers/pci/quirks.c:nvme_disable_and_flr",
        "drivers/pci/quirks.c:reset_chelsio_generic_dev",
        "drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594226084,
      "name": "pcie_flr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071586980448,
      "name": "pcie_flr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
int pcie_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588145936,
      "name": "pcie_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4720",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_reset_flr",
        "drivers/pci/quirks.c:reset_hinic_vf_dev",
        "drivers/pci/quirks.c:nvme_disable_and_flr",
        "drivers/pci/quirks.c:reset_chelsio_generic_dev",
        "drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588145936,
      "name": "pcie_flr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
int pcie_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588421488,
      "name": "pcie_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4758",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_reset_flr",
        "drivers/pci/quirks.c:reset_hinic_vf_dev",
        "drivers/pci/quirks.c:nvme_disable_and_flr",
        "drivers/pci/quirks.c:reset_chelsio_generic_dev",
        "drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588421488,
      "name": "pcie_flr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
int pcie_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588717776,
      "name": "pcie_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4868",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_reset_flr",
        "drivers/pci/quirks.c:reset_hinic_vf_dev",
        "drivers/pci/quirks.c:nvme_disable_and_flr",
        "drivers/pci/quirks.c:reset_chelsio_generic_dev",
        "drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588717776,
      "name": "pcie_flr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
int pcie_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496865136,
      "name": "pcie_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4497",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496865136,
      "name": "pcie_flr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int pcie_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230143124,
      "name": "pcie_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4497",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230143124,
      "name": "pcie_flr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int pcie_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290945568,
      "name": "pcie_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4497",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290945568,
      "name": "pcie_flr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int pcie_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275565302,
      "name": "pcie_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4497",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275565302,
      "name": "pcie_flr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int pcie_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584573832,
      "name": "pcie_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4497",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584588554,
      "name": "pcie_flr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071584573776,
      "name": "pcie_flr",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pcie_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584501992,
      "name": "pcie_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4497",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584516682,
      "name": "pcie_flr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071584501936,
      "name": "pcie_flr",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pcie_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584571832,
      "name": "pcie_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4497",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584586554,
      "name": "pcie_flr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071584571776,
      "name": "pcie_flr",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pcie_flr(struct pci_dev * dev)
```

```json
{
  "name": "pcie_flr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584679576,
      "name": "pcie_flr",
      "external": true,
      "loc": "drivers/pci/pci.c:4497",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584694250,
      "name": "pcie_flr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071584679520,
      "name": "pcie_flr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void pcie_flr(struct pci_dev * dev)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
