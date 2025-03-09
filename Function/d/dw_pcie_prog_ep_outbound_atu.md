# Function: <code>dw_pcie_prog_ep_outbound_atu</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void dw_pcie_prog_ep_outbound_atu(struct dw_pcie * pci, u8 func_no, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size)
```

```json
{
  "name": "dw_pcie_prog_ep_outbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585640528,
      "name": "dw_pcie_prog_ep_outbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:322",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585640528,
      "name": "dw_pcie_prog_ep_outbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void dw_pcie_prog_ep_outbound_atu(struct dw_pcie * pci, u8 func_no, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size)
```

```json
{
  "name": "dw_pcie_prog_ep_outbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585520304,
      "name": "dw_pcie_prog_ep_outbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:372",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585520304,
      "name": "dw_pcie_prog_ep_outbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void dw_pcie_prog_ep_outbound_atu(struct dw_pcie * pci, u8 func_no, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size)
```

```json
{
  "name": "dw_pcie_prog_ep_outbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585989920,
      "name": "dw_pcie_prog_ep_outbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:372",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585989920,
      "name": "dw_pcie_prog_ep_outbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void dw_pcie_prog_ep_outbound_atu(struct dw_pcie * pci, u8 func_no, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size)
```

```json
{
  "name": "dw_pcie_prog_ep_outbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587206160,
      "name": "dw_pcie_prog_ep_outbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:376",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587206160,
      "name": "dw_pcie_prog_ep_outbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int dw_pcie_prog_ep_outbound_atu(struct dw_pcie * pci, u8 func_no, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size)
```

```json
{
  "name": "dw_pcie_prog_ep_outbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588435856,
      "name": "dw_pcie_prog_ep_outbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:522",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588435856,
      "name": "dw_pcie_prog_ep_outbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int dw_pcie_prog_ep_outbound_atu(struct dw_pcie * pci, u8 func_no, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size)
```

```json
{
  "name": "dw_pcie_prog_ep_outbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588713792,
      "name": "dw_pcie_prog_ep_outbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:535",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588713792,
      "name": "dw_pcie_prog_ep_outbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int dw_pcie_prog_ep_outbound_atu(struct dw_pcie * pci, u8 func_no, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size)
```

```json
{
  "name": "dw_pcie_prog_ep_outbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589014768,
      "name": "dw_pcie_prog_ep_outbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:536",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589014768,
      "name": "dw_pcie_prog_ep_outbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void dw_pcie_prog_ep_outbound_atu(struct dw_pcie * pci, u8 func_no, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u32 size</code> ➡️ <code>u64 size</code>
</li>
</ul>
</details>
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
