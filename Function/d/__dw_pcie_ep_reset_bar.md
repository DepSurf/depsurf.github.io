# Function: <code>__dw_pcie_ep_reset_bar</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dw_pcie_ep_reset_bar",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584389717,
      "name": "__dw_pcie_ep_reset_bar",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:22",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dw_pcie_ep_reset_bar",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584481909,
      "name": "__dw_pcie_ep_reset_bar",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:22",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dw_pcie_ep_reset_bar",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584679605,
      "name": "__dw_pcie_ep_reset_bar",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:22",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dw_pcie_ep_reset_bar",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584818149,
      "name": "__dw_pcie_ep_reset_bar",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:22",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dw_pcie_ep_reset_bar",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585513221,
      "name": "__dw_pcie_ep_reset_bar",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:31",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __dw_pcie_ep_reset_bar(struct dw_pcie * pci, u8 func_no, enum pci_barno bar, int flags)
```

```json
{
  "name": "__dw_pcie_ep_reset_bar",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585647040,
      "name": "__dw_pcie_ep_reset_bar",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:57",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585647040,
      "name": "__dw_pcie_ep_reset_bar",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
void __dw_pcie_ep_reset_bar(struct dw_pcie * pci, u8 func_no, enum pci_barno bar, int flags)
```

```json
{
  "name": "__dw_pcie_ep_reset_bar",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585527856,
      "name": "__dw_pcie_ep_reset_bar",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:57",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585527856,
      "name": "__dw_pcie_ep_reset_bar",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
void __dw_pcie_ep_reset_bar(struct dw_pcie * pci, u8 func_no, enum pci_barno bar, int flags)
```

```json
{
  "name": "__dw_pcie_ep_reset_bar",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585997856,
      "name": "__dw_pcie_ep_reset_bar",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:57",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585997856,
      "name": "__dw_pcie_ep_reset_bar",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
void __dw_pcie_ep_reset_bar(struct dw_pcie * pci, u8 func_no, enum pci_barno bar, int flags)
```

```json
{
  "name": "__dw_pcie_ep_reset_bar",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587215360,
      "name": "__dw_pcie_ep_reset_bar",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:57",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587215360,
      "name": "__dw_pcie_ep_reset_bar",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
void __dw_pcie_ep_reset_bar(struct dw_pcie * pci, u8 func_no, enum pci_barno bar, int flags)
```

```json
{
  "name": "__dw_pcie_ep_reset_bar",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588447616,
      "name": "__dw_pcie_ep_reset_bar",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:55",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588447616,
      "name": "__dw_pcie_ep_reset_bar",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
void __dw_pcie_ep_reset_bar(struct dw_pcie * pci, u8 func_no, enum pci_barno bar, int flags)
```

```json
{
  "name": "__dw_pcie_ep_reset_bar",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588726704,
      "name": "__dw_pcie_ep_reset_bar",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:55",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588726704,
      "name": "__dw_pcie_ep_reset_bar",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dw_pcie_ep_reset_bar",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589031433,
      "name": "__dw_pcie_ep_reset_bar",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:47",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void __dw_pcie_ep_reset_bar(struct dw_pcie * pci, enum pci_barno bar, int flags)
```

```json
{
  "name": "__dw_pcie_ep_reset_bar",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497166472,
      "name": "__dw_pcie_ep_reset_bar",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:22",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497166472,
      "name": "__dw_pcie_ep_reset_bar",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
void __dw_pcie_ep_reset_bar(struct dw_pcie * pci, enum pci_barno bar, int flags)
```

```json
{
  "name": "__dw_pcie_ep_reset_bar",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230370828,
      "name": "__dw_pcie_ep_reset_bar",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:22",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230370828,
      "name": "__dw_pcie_ep_reset_bar",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void __dw_pcie_ep_reset_bar(struct dw_pcie * pci, enum pci_barno bar, int flags)
```

```json
{
  "name": "__dw_pcie_ep_reset_bar",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275749162,
      "name": "__dw_pcie_ep_reset_bar",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:22",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275749162,
      "name": "__dw_pcie_ep_reset_bar",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dw_pcie_ep_reset_bar",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584766885,
      "name": "__dw_pcie_ep_reset_bar",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:22",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dw_pcie_ep_reset_bar",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584697669,
      "name": "__dw_pcie_ep_reset_bar",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:22",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dw_pcie_ep_reset_bar",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584768309,
      "name": "__dw_pcie_ep_reset_bar",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:22",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dw_pcie_ep_reset_bar",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584875829,
      "name": "__dw_pcie_ep_reset_bar",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:22",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void __dw_pcie_ep_reset_bar(struct dw_pcie * pci, u8 func_no, enum pci_barno bar, int flags)
```
</details>
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void __dw_pcie_ep_reset_bar(struct dw_pcie * pci, u8 func_no, enum pci_barno bar, int flags)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void __dw_pcie_ep_reset_bar(struct dw_pcie * pci, enum pci_barno bar, int flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void __dw_pcie_ep_reset_bar(struct dw_pcie * pci, enum pci_barno bar, int flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void __dw_pcie_ep_reset_bar(struct dw_pcie * pci, enum pci_barno bar, int flags)
```
</details>
</li>
</ul>
