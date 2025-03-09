# Function: <code>dw_pcie_ep_raise_irq</code>

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
  "name": "dw_pcie_ep_raise_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_raise_irq",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_ep_raise_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_raise_irq",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:325",
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
  "name": "dw_pcie_ep_raise_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_raise_irq",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:325",
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
  "name": "dw_pcie_ep_raise_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_raise_irq",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:292",
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
  "name": "dw_pcie_ep_raise_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_raise_irq",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:314",
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
int dw_pcie_ep_raise_irq(struct pci_epc * epc, u8 func_no, enum pci_epc_irq_type type, u16 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585645552,
      "name": "dw_pcie_ep_raise_irq",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:421",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585645552,
      "name": "dw_pcie_ep_raise_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int dw_pcie_ep_raise_irq(struct pci_epc * epc, u8 func_no, enum pci_epc_irq_type type, u16 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585526352,
      "name": "dw_pcie_ep_raise_irq",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:421",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585526352,
      "name": "dw_pcie_ep_raise_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int dw_pcie_ep_raise_irq(struct pci_epc * epc, u8 func_no, u8 vfunc_no, enum pci_epc_irq_type type, u16 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585996304,
      "name": "dw_pcie_ep_raise_irq",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:421",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585996304,
      "name": "dw_pcie_ep_raise_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int dw_pcie_ep_raise_irq(struct pci_epc * epc, u8 func_no, u8 vfunc_no, enum pci_epc_irq_type type, u16 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587213136,
      "name": "dw_pcie_ep_raise_irq",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:422",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587213136,
      "name": "dw_pcie_ep_raise_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
int dw_pcie_ep_raise_irq(struct pci_epc * epc, u8 func_no, u8 vfunc_no, enum pci_epc_irq_type type, u16 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588444784,
      "name": "dw_pcie_ep_raise_irq",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:428",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588444784,
      "name": "dw_pcie_ep_raise_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
int dw_pcie_ep_raise_irq(struct pci_epc * epc, u8 func_no, u8 vfunc_no, enum pci_epc_irq_type type, u16 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588723824,
      "name": "dw_pcie_ep_raise_irq",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:428",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588723824,
      "name": "dw_pcie_ep_raise_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
int dw_pcie_ep_raise_irq(struct pci_epc * epc, u8 func_no, u8 vfunc_no, unsigned int type, u16 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589025648,
      "name": "dw_pcie_ep_raise_irq",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:389",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589025648,
      "name": "dw_pcie_ep_raise_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
int dw_pcie_ep_raise_irq(struct pci_epc * epc, u8 func_no, enum pci_epc_irq_type type, u16 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497165216,
      "name": "dw_pcie_ep_raise_irq",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:292",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497165216,
      "name": "dw_pcie_ep_raise_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int dw_pcie_ep_raise_irq(struct pci_epc * epc, u8 func_no, enum pci_epc_irq_type type, u16 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230369784,
      "name": "dw_pcie_ep_raise_irq",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:292",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230369784,
      "name": "dw_pcie_ep_raise_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
int dw_pcie_ep_raise_irq(struct pci_epc * epc, u8 func_no, enum pci_epc_irq_type type, u16 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275748042,
      "name": "dw_pcie_ep_raise_irq",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:292",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275748042,
      "name": "dw_pcie_ep_raise_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
  "name": "dw_pcie_ep_raise_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_raise_irq",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:292",
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
  "name": "dw_pcie_ep_raise_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_raise_irq",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:292",
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
  "name": "dw_pcie_ep_raise_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_raise_irq",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:292",
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
  "name": "dw_pcie_ep_raise_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_raise_irq",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:292",
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
int dw_pcie_ep_raise_irq(struct pci_epc * epc, u8 func_no, enum pci_epc_irq_type type, u16 interrupt_num)
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
<code>epc, func_no, type, interrupt_num</code> ➡️ <code>epc, func_no, vfunc_no, type, interrupt_num</code>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>enum pci_epc_irq_type type</code> ➡️ <code>unsigned int type</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int dw_pcie_ep_raise_irq(struct pci_epc * epc, u8 func_no, enum pci_epc_irq_type type, u16 interrupt_num)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int dw_pcie_ep_raise_irq(struct pci_epc * epc, u8 func_no, enum pci_epc_irq_type type, u16 interrupt_num)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int dw_pcie_ep_raise_irq(struct pci_epc * epc, u8 func_no, enum pci_epc_irq_type type, u16 interrupt_num)
```
</details>
</li>
</ul>
