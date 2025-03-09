# Function: <code>dw_pcie_writel_rc</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_writel_rc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583716763,
      "name": "dw_pcie_writel_rc",
      "external": false,
      "loc": "drivers/pci/host/pcie-designware.c:126",
      "file": "drivers/pci/host/pcie-designware.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc",
        "drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc",
        "drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc",
        "drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc",
        "drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc",
        "drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc",
        "drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc",
        "drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc",
        "drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc",
        "drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc",
        "drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc",
        "drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc",
        "drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc",
        "drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc",
        "drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dw_pcie_writel_rc(struct pcie_port * pp, u32 reg, u32 val)
```

```json
{
  "name": "dw_pcie_writel_rc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583856739,
      "name": "dw_pcie_writel_rc",
      "external": true,
      "loc": "drivers/pci/host/pcie-designware.c:152",
      "file": "drivers/pci/host/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc",
        "drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc",
        "drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc",
        "drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc",
        "drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc",
        "drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc",
        "drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc",
        "drivers/pci/host/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/host/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/host/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/host/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/host/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/host/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/host/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/host/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/host/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/host/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/host/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/host/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/host/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/host/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/host/pcie-designware.c:dw_pcie_prog_outbound_atu"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583855888,
      "name": "dw_pcie_writel_rc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void dw_pcie_writel_rc(struct pcie_port * pp, u32 reg, u32 val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void dw_pcie_writel_rc(struct pcie_port * pp, u32 reg, u32 val)
```
</details>
</li>
</ul>
