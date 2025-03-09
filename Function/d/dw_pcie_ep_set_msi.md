# Function: <code>dw_pcie_ep_set_msi</code>

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
  "name": "dw_pcie_ep_set_msi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_set_msi",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:228",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_ep_set_msi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_set_msi",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:266",
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
  "name": "dw_pcie_ep_set_msi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_set_msi",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:266",
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
  "name": "dw_pcie_ep_set_msi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_set_msi",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:233",
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
  "name": "dw_pcie_ep_set_msi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_set_msi",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:244",
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
int dw_pcie_ep_set_msi(struct pci_epc * epc, u8 func_no, u8 interrupts)
```

```json
{
  "name": "dw_pcie_ep_set_msi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585647392,
      "name": "dw_pcie_ep_set_msi",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:336",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585647392,
      "name": "dw_pcie_ep_set_msi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
int dw_pcie_ep_set_msi(struct pci_epc * epc, u8 func_no, u8 interrupts)
```

```json
{
  "name": "dw_pcie_ep_set_msi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585528208,
      "name": "dw_pcie_ep_set_msi",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:336",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585528208,
      "name": "dw_pcie_ep_set_msi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
int dw_pcie_ep_set_msi(struct pci_epc * epc, u8 func_no, u8 vfunc_no, u8 interrupts)
```

```json
{
  "name": "dw_pcie_ep_set_msi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585998256,
      "name": "dw_pcie_ep_set_msi",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:335",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585998256,
      "name": "dw_pcie_ep_set_msi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
int dw_pcie_ep_set_msi(struct pci_epc * epc, u8 func_no, u8 vfunc_no, u8 interrupts)
```

```json
{
  "name": "dw_pcie_ep_set_msi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587215888,
      "name": "dw_pcie_ep_set_msi",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:336",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587215888,
      "name": "dw_pcie_ep_set_msi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
int dw_pcie_ep_set_msi(struct pci_epc * epc, u8 func_no, u8 vfunc_no, u8 interrupts)
```

```json
{
  "name": "dw_pcie_ep_set_msi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588448224,
      "name": "dw_pcie_ep_set_msi",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:342",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588448224,
      "name": "dw_pcie_ep_set_msi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
int dw_pcie_ep_set_msi(struct pci_epc * epc, u8 func_no, u8 vfunc_no, u8 interrupts)
```

```json
{
  "name": "dw_pcie_ep_set_msi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588727328,
      "name": "dw_pcie_ep_set_msi",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:342",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588727328,
      "name": "dw_pcie_ep_set_msi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
int dw_pcie_ep_set_msi(struct pci_epc * epc, u8 func_no, u8 vfunc_no, u8 interrupts)
```

```json
{
  "name": "dw_pcie_ep_set_msi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589029264,
      "name": "dw_pcie_ep_set_msi",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:313",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589029264,
      "name": "dw_pcie_ep_set_msi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
int dw_pcie_ep_set_msi(struct pci_epc * epc, u8 func_no, u8 interrupts)
```

```json
{
  "name": "dw_pcie_ep_set_msi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497166264,
      "name": "dw_pcie_ep_set_msi",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:233",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497166264,
      "name": "dw_pcie_ep_set_msi",
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int dw_pcie_ep_set_msi(struct pci_epc * epc, u8 func_no, u8 interrupts)
```

```json
{
  "name": "dw_pcie_ep_set_msi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230370636,
      "name": "dw_pcie_ep_set_msi",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:233",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230370636,
      "name": "dw_pcie_ep_set_msi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
int dw_pcie_ep_set_msi(struct pci_epc * epc, u8 func_no, u8 interrupts)
```

```json
{
  "name": "dw_pcie_ep_set_msi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275748964,
      "name": "dw_pcie_ep_set_msi",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:233",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275748964,
      "name": "dw_pcie_ep_set_msi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
  "name": "dw_pcie_ep_set_msi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_set_msi",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:233",
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
  "name": "dw_pcie_ep_set_msi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_set_msi",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:233",
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
  "name": "dw_pcie_ep_set_msi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_set_msi",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:233",
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
  "name": "dw_pcie_ep_set_msi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_set_msi",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:233",
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
int dw_pcie_ep_set_msi(struct pci_epc * epc, u8 func_no, u8 interrupts)
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
<code>epc, func_no, interrupts</code> ➡️ <code>epc, func_no, vfunc_no, interrupts</code>
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
int dw_pcie_ep_set_msi(struct pci_epc * epc, u8 func_no, u8 interrupts)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int dw_pcie_ep_set_msi(struct pci_epc * epc, u8 func_no, u8 interrupts)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int dw_pcie_ep_set_msi(struct pci_epc * epc, u8 func_no, u8 interrupts)
```
</details>
</li>
</ul>
