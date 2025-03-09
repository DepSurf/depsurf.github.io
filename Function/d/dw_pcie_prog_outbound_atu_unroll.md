# Function: <code>dw_pcie_prog_outbound_atu_unroll</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void dw_pcie_prog_outbound_atu_unroll(struct dw_pcie * pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size)
```

```json
{
  "name": "dw_pcie_prog_outbound_atu_unroll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583903744,
      "name": "dw_pcie_prog_outbound_atu_unroll",
      "external": true,
      "loc": "drivers/pci/dwc/pcie-designware.c:110",
      "file": "drivers/pci/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583903744,
      "name": "dw_pcie_prog_outbound_atu_unroll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_prog_outbound_atu_unroll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584167466,
      "name": "dw_pcie_prog_outbound_atu_unroll",
      "external": false,
      "loc": "drivers/pci/dwc/pcie-designware.c:110",
      "file": "drivers/pci/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_prog_outbound_atu_unroll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584385546,
      "name": "dw_pcie_prog_outbound_atu_unroll",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:107",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
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
  "name": "dw_pcie_prog_outbound_atu_unroll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584477395,
      "name": "dw_pcie_prog_outbound_atu_unroll",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:107",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
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
  "name": "dw_pcie_prog_outbound_atu_unroll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584675605,
      "name": "dw_pcie_prog_outbound_atu_unroll",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:161",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
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
  "name": "dw_pcie_prog_outbound_atu_unroll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584814213,
      "name": "dw_pcie_prog_outbound_atu_unroll",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:241",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void dw_pcie_prog_outbound_atu_unroll(struct dw_pcie * pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size)
```

```json
{
  "name": "dw_pcie_prog_outbound_atu_unroll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_prog_outbound_atu_unroll",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:242",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585508160,
      "name": "dw_pcie_prog_outbound_atu_unroll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
    },
    {
      "addr": 18446744071585509819,
      "name": "dw_pcie_prog_outbound_atu_unroll.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void dw_pcie_prog_outbound_atu_unroll(struct dw_pcie * pci, u8 func_no, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size)
```

```json
{
  "name": "dw_pcie_prog_outbound_atu_unroll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_prog_outbound_atu_unroll",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:228",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585638496,
      "name": "dw_pcie_prog_outbound_atu_unroll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    },
    {
      "addr": 18446744071591419303,
      "name": "dw_pcie_prog_outbound_atu_unroll.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_prog_outbound_atu_unroll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585519493,
      "name": "dw_pcie_prog_outbound_atu_unroll",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:269",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_prog_outbound_atu_unroll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585989109,
      "name": "dw_pcie_prog_outbound_atu_unroll",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:269",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_prog_outbound_atu_unroll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587205196,
      "name": "dw_pcie_prog_outbound_atu_unroll",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:269",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_prog_outbound_atu_unroll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336497157556,
      "name": "dw_pcie_prog_outbound_atu_unroll",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:241",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_prog_outbound_atu_unroll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230362904,
      "name": "dw_pcie_prog_outbound_atu_unroll",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:241",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_prog_outbound_atu_unroll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275741860,
      "name": "dw_pcie_prog_outbound_atu_unroll",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:241",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_prog_outbound_atu_unroll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584762949,
      "name": "dw_pcie_prog_outbound_atu_unroll",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:241",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
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
  "name": "dw_pcie_prog_outbound_atu_unroll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584693733,
      "name": "dw_pcie_prog_outbound_atu_unroll",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:241",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
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
  "name": "dw_pcie_prog_outbound_atu_unroll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584764373,
      "name": "dw_pcie_prog_outbound_atu_unroll",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:241",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
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
  "name": "dw_pcie_prog_outbound_atu_unroll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584871893,
      "name": "dw_pcie_prog_outbound_atu_unroll",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:241",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void dw_pcie_prog_outbound_atu_unroll(struct dw_pcie * pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void dw_pcie_prog_outbound_atu_unroll(struct dw_pcie * pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void dw_pcie_prog_outbound_atu_unroll(struct dw_pcie * pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 func_no</code>
</li>
<li>
<b>Param reordered. </b>
<code>pci, index, type, cpu_addr, pci_addr, size</code> ➡️ <code>pci, func_no, index, type, cpu_addr, pci_addr, size</code>
</li>
<li>
<b>Param type changed. </b>
<code>u32 size</code> ➡️ <code>u64 size</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void dw_pcie_prog_outbound_atu_unroll(struct dw_pcie * pci, u8 func_no, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size)
```
</details>
</li>
</ul>
