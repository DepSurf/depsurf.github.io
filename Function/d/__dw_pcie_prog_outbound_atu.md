# Function: <code>__dw_pcie_prog_outbound_atu</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void __dw_pcie_prog_outbound_atu(struct dw_pcie * pci, u8 func_no, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size)
```

```json
{
  "name": "__dw_pcie_prog_outbound_atu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dw_pcie_prog_outbound_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:270",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_ep_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585639584,
      "name": "__dw_pcie_prog_outbound_atu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    },
    {
      "addr": 18446744071591419412,
      "name": "__dw_pcie_prog_outbound_atu.cold",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void __dw_pcie_prog_outbound_atu(struct dw_pcie * pci, u8 func_no, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size)
```

```json
{
  "name": "__dw_pcie_prog_outbound_atu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dw_pcie_prog_outbound_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:313",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_ep_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585518976,
      "name": "__dw_pcie_prog_outbound_atu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 749
    },
    {
      "addr": 18446744071591361838,
      "name": "__dw_pcie_prog_outbound_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void __dw_pcie_prog_outbound_atu(struct dw_pcie * pci, u8 func_no, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size)
```

```json
{
  "name": "__dw_pcie_prog_outbound_atu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dw_pcie_prog_outbound_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:313",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_ep_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585988592,
      "name": "__dw_pcie_prog_outbound_atu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 749
    },
    {
      "addr": 18446744071592391555,
      "name": "__dw_pcie_prog_outbound_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void __dw_pcie_prog_outbound_atu(struct dw_pcie * pci, u8 func_no, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size)
```

```json
{
  "name": "__dw_pcie_prog_outbound_atu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dw_pcie_prog_outbound_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:313",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_ep_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587204704,
      "name": "__dw_pcie_prog_outbound_atu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 710
    },
    {
      "addr": 18446744071594256286,
      "name": "__dw_pcie_prog_outbound_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
int __dw_pcie_prog_outbound_atu(struct dw_pcie * pci, u8 func_no, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size)
```

```json
{
  "name": "__dw_pcie_prog_outbound_atu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588433344,
      "name": "__dw_pcie_prog_outbound_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:454",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_ep_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588433344,
      "name": "__dw_pcie_prog_outbound_atu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 558
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
int __dw_pcie_prog_outbound_atu(struct dw_pcie * pci, u8 func_no, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size)
```

```json
{
  "name": "__dw_pcie_prog_outbound_atu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588711184,
      "name": "__dw_pcie_prog_outbound_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:467",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_ep_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588711184,
      "name": "__dw_pcie_prog_outbound_atu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 558
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
int __dw_pcie_prog_outbound_atu(struct dw_pcie * pci, u8 func_no, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size)
```

```json
{
  "name": "__dw_pcie_prog_outbound_atu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589012304,
      "name": "__dw_pcie_prog_outbound_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:468",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_ep_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589012304,
      "name": "__dw_pcie_prog_outbound_atu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 558
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void __dw_pcie_prog_outbound_atu(struct dw_pcie * pci, u8 func_no, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size)
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
