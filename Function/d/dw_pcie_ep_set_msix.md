# Function: <code>dw_pcie_ep_set_msix</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_ep_set_msix",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_set_msix",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:305",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_ep_set_msix",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_set_msix",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:305",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_ep_set_msix",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_set_msix",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:272",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_ep_set_msix",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_set_msix",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:283",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int dw_pcie_ep_set_msix(struct pci_epc * epc, u8 func_no, u16 interrupts, enum pci_barno bir, u32 offset)
```

```json
{
  "name": "dw_pcie_ep_set_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585648736,
      "name": "dw_pcie_ep_set_msix",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:385",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585648736,
      "name": "dw_pcie_ep_set_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
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
int dw_pcie_ep_set_msix(struct pci_epc * epc, u8 func_no, u16 interrupts, enum pci_barno bir, u32 offset)
```

```json
{
  "name": "dw_pcie_ep_set_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585529568,
      "name": "dw_pcie_ep_set_msix",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:385",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585529568,
      "name": "dw_pcie_ep_set_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
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
int dw_pcie_ep_set_msix(struct pci_epc * epc, u8 func_no, u8 vfunc_no, u16 interrupts, enum pci_barno bir, u32 offset)
```

```json
{
  "name": "dw_pcie_ep_set_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585999616,
      "name": "dw_pcie_ep_set_msix",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:385",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585999616,
      "name": "dw_pcie_ep_set_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
int dw_pcie_ep_set_msix(struct pci_epc * epc, u8 func_no, u8 vfunc_no, u16 interrupts, enum pci_barno bir, u32 offset)
```

```json
{
  "name": "dw_pcie_ep_set_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587217392,
      "name": "dw_pcie_ep_set_msix",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:386",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587217392,
      "name": "dw_pcie_ep_set_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
int dw_pcie_ep_set_msix(struct pci_epc * epc, u8 func_no, u8 vfunc_no, u16 interrupts, enum pci_barno bir, u32 offset)
```

```json
{
  "name": "dw_pcie_ep_set_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588448544,
      "name": "dw_pcie_ep_set_msix",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:392",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588448544,
      "name": "dw_pcie_ep_set_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
int dw_pcie_ep_set_msix(struct pci_epc * epc, u8 func_no, u8 vfunc_no, u16 interrupts, enum pci_barno bir, u32 offset)
```

```json
{
  "name": "dw_pcie_ep_set_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588727648,
      "name": "dw_pcie_ep_set_msix",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:392",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588727648,
      "name": "dw_pcie_ep_set_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
int dw_pcie_ep_set_msix(struct pci_epc * epc, u8 func_no, u8 vfunc_no, u16 interrupts, enum pci_barno bir, u32 offset)
```

```json
{
  "name": "dw_pcie_ep_set_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589029632,
      "name": "dw_pcie_ep_set_msix",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:356",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589029632,
      "name": "dw_pcie_ep_set_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
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
int dw_pcie_ep_set_msix(struct pci_epc * epc, u8 func_no, u16 interrupts)
```

```json
{
  "name": "dw_pcie_ep_set_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497166064,
      "name": "dw_pcie_ep_set_msix",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:272",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497166064,
      "name": "dw_pcie_ep_set_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
int dw_pcie_ep_set_msix(struct pci_epc * epc, u8 func_no, u16 interrupts)
```

```json
{
  "name": "dw_pcie_ep_set_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230370456,
      "name": "dw_pcie_ep_set_msix",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:272",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230370456,
      "name": "dw_pcie_ep_set_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int dw_pcie_ep_set_msix(struct pci_epc * epc, u8 func_no, u16 interrupts)
```

```json
{
  "name": "dw_pcie_ep_set_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275748772,
      "name": "dw_pcie_ep_set_msix",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:272",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275748772,
      "name": "dw_pcie_ep_set_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
  "name": "dw_pcie_ep_set_msix",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_set_msix",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:272",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_ep_set_msix",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_set_msix",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:272",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_ep_set_msix",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_set_msix",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:272",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_ep_set_msix",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_set_msix",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:272",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
int dw_pcie_ep_set_msix(struct pci_epc * epc, u8 func_no, u16 interrupts, enum pci_barno bir, u32 offset)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 vfunc_no</code>
</li>
<li>
<b>Param reordered. </b>
<code>epc, func_no, interrupts, bir, offset</code> ➡️ <code>epc, func_no, vfunc_no, interrupts, bir, offset</code>
</li>
</ul>
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int dw_pcie_ep_set_msix(struct pci_epc * epc, u8 func_no, u16 interrupts)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int dw_pcie_ep_set_msix(struct pci_epc * epc, u8 func_no, u16 interrupts)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int dw_pcie_ep_set_msix(struct pci_epc * epc, u8 func_no, u16 interrupts)
```
</details>
</li>
</ul>
