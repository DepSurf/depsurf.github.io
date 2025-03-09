# Function: <code>dw_pcie_access_other_conf</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_access_other_conf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_access_other_conf",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:510",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
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
  "name": "dw_pcie_access_other_conf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_access_other_conf",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:527",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
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
  "name": "dw_pcie_access_other_conf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_access_other_conf",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:519",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_access_other_conf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497160576,
      "name": "dw_pcie_access_other_conf",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:527",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_wr_conf",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_rd_conf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497160576,
      "name": "dw_pcie_access_other_conf.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int dw_pcie_access_other_conf(struct pcie_port * pp, struct pci_bus * bus, u32 devfn, int where, int size, u32 * val, bool write)
```

```json
{
  "name": "dw_pcie_access_other_conf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230364752,
      "name": "dw_pcie_access_other_conf",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:527",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_wr_conf",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_rd_conf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230364752,
      "name": "dw_pcie_access_other_conf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int dw_pcie_access_other_conf(struct pcie_port * pp, struct pci_bus * bus, u32 devfn, int where, int size, u32 * val, bool write)
```

```json
{
  "name": "dw_pcie_access_other_conf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275743630,
      "name": "dw_pcie_access_other_conf",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:527",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_wr_conf",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_rd_conf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275743630,
      "name": "dw_pcie_access_other_conf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
  "name": "dw_pcie_access_other_conf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_access_other_conf",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:527",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
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
  "name": "dw_pcie_access_other_conf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_access_other_conf",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:527",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
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
  "name": "dw_pcie_access_other_conf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_access_other_conf",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:527",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
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
  "name": "dw_pcie_access_other_conf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_access_other_conf",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:527",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int dw_pcie_access_other_conf(struct pcie_port * pp, struct pci_bus * bus, u32 devfn, int where, int size, u32 * val, bool write)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int dw_pcie_access_other_conf(struct pcie_port * pp, struct pci_bus * bus, u32 devfn, int where, int size, u32 * val, bool write)
```
</details>
</li>
</ul>
