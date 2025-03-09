# Function: <code>pci_epc_linkup</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_epc_linkup(struct pci_epc * epc)
```

```json
{
  "name": "pci_epc_linkup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583900416,
      "name": "pci_epc_linkup",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:423",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583900416,
      "name": "pci_epc_linkup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void pci_epc_linkup(struct pci_epc * epc)
```

```json
{
  "name": "pci_epc_linkup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584163648,
      "name": "pci_epc_linkup",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:429",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584163648,
      "name": "pci_epc_linkup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void pci_epc_linkup(struct pci_epc * epc)
```

```json
{
  "name": "pci_epc_linkup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584381472,
      "name": "pci_epc_linkup",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:428",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_linkup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584381472,
      "name": "pci_epc_linkup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void pci_epc_linkup(struct pci_epc * epc)
```

```json
{
  "name": "pci_epc_linkup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584473520,
      "name": "pci_epc_linkup",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:486",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_linkup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584473520,
      "name": "pci_epc_linkup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void pci_epc_linkup(struct pci_epc * epc)
```

```json
{
  "name": "pci_epc_linkup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584669456,
      "name": "pci_epc_linkup",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:540",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_linkup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584669456,
      "name": "pci_epc_linkup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void pci_epc_linkup(struct pci_epc * epc)
```

```json
{
  "name": "pci_epc_linkup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584807728,
      "name": "pci_epc_linkup",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:540",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_linkup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584807728,
      "name": "pci_epc_linkup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void pci_epc_linkup(struct pci_epc * epc)
```

```json
{
  "name": "pci_epc_linkup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585500576,
      "name": "pci_epc_linkup",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:541",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_linkup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585500576,
      "name": "pci_epc_linkup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void pci_epc_linkup(struct pci_epc * epc)
```

```json
{
  "name": "pci_epc_linkup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585632672,
      "name": "pci_epc_linkup",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:541",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_linkup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585632672,
      "name": "pci_epc_linkup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void pci_epc_linkup(struct pci_epc * epc)
```

```json
{
  "name": "pci_epc_linkup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585512288,
      "name": "pci_epc_linkup",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:635",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_linkup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585512288,
      "name": "pci_epc_linkup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void pci_epc_linkup(struct pci_epc * epc)
```

```json
{
  "name": "pci_epc_linkup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585981056,
      "name": "pci_epc_linkup",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:691",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_linkup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585981056,
      "name": "pci_epc_linkup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void pci_epc_linkup(struct pci_epc * epc)
```

```json
{
  "name": "pci_epc_linkup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587196752,
      "name": "pci_epc_linkup",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:691",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_linkup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587196752,
      "name": "pci_epc_linkup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void pci_epc_linkup(struct pci_epc * epc)
```

```json
{
  "name": "pci_epc_linkup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588423936,
      "name": "pci_epc_linkup",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:691",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_linkup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588423936,
      "name": "pci_epc_linkup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void pci_epc_linkup(struct pci_epc * epc)
```

```json
{
  "name": "pci_epc_linkup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588700704,
      "name": "pci_epc_linkup",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:691",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_linkup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588700704,
      "name": "pci_epc_linkup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void pci_epc_linkup(struct pci_epc * epc)
```

```json
{
  "name": "pci_epc_linkup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589001520,
      "name": "pci_epc_linkup",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:690",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_linkup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589001520,
      "name": "pci_epc_linkup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void pci_epc_linkup(struct pci_epc * epc)
```

```json
{
  "name": "pci_epc_linkup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497083608,
      "name": "pci_epc_linkup",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:540",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_linkup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497083608,
      "name": "pci_epc_linkup",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void pci_epc_linkup(struct pci_epc * epc)
```

```json
{
  "name": "pci_epc_linkup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230289244,
      "name": "pci_epc_linkup",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:540",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_linkup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230289244,
      "name": "pci_epc_linkup",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void pci_epc_linkup(struct pci_epc * epc)
```

```json
{
  "name": "pci_epc_linkup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291123680,
      "name": "pci_epc_linkup",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:540",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291123680,
      "name": "pci_epc_linkup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void pci_epc_linkup(struct pci_epc * epc)
```

```json
{
  "name": "pci_epc_linkup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275720210,
      "name": "pci_epc_linkup",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:540",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_linkup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275720210,
      "name": "pci_epc_linkup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void pci_epc_linkup(struct pci_epc * epc)
```

```json
{
  "name": "pci_epc_linkup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584756464,
      "name": "pci_epc_linkup",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:540",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_linkup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584756464,
      "name": "pci_epc_linkup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void pci_epc_linkup(struct pci_epc * epc)
```

```json
{
  "name": "pci_epc_linkup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584687248,
      "name": "pci_epc_linkup",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:540",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_linkup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584687248,
      "name": "pci_epc_linkup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void pci_epc_linkup(struct pci_epc * epc)
```

```json
{
  "name": "pci_epc_linkup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584757888,
      "name": "pci_epc_linkup",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:540",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_linkup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584757888,
      "name": "pci_epc_linkup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void pci_epc_linkup(struct pci_epc * epc)
```

```json
{
  "name": "pci_epc_linkup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584865408,
      "name": "pci_epc_linkup",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:540",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_linkup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584865408,
      "name": "pci_epc_linkup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void pci_epc_linkup(struct pci_epc * epc)
```
</details>
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
