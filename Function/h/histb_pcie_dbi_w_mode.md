# Function: <code>histb_pcie_dbi_w_mode</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void histb_pcie_dbi_w_mode(struct pcie_port * pp, bool enable)
```

```json
{
  "name": "histb_pcie_dbi_w_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497197088,
      "name": "histb_pcie_dbi_w_mode",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-histb.c:77",
      "file": "drivers/pci/controller/dwc/pcie-histb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_wr_own_conf",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_wr_own_conf",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_write_dbi",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_write_dbi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497197088,
      "name": "histb_pcie_dbi_w_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "histb_pcie_dbi_w_mode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230394056,
      "name": "histb_pcie_dbi_w_mode",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-histb.c:77",
      "file": "drivers/pci/controller/dwc/pcie-histb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_wr_own_conf",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_wr_own_conf",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_write_dbi",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_write_dbi"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void histb_pcie_dbi_w_mode(struct pcie_port * pp, bool enable)
```
</details>
</li>
</ul>
