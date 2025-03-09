# Function: <code>pcie_phy_read</code>

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
int pcie_phy_read(struct imx6_pcie * imx6_pcie, int addr, u16 * data)
```

```json
{
  "name": "pcie_phy_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497172608,
      "name": "pcie_phy_read",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pci-imx6.c:200",
      "file": "drivers/pci/controller/dwc/pci-imx6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_host_init",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_host_init",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497172608,
      "name": "pcie_phy_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
int pcie_phy_read(struct imx6_pcie * imx6_pcie, int addr, u16 * data)
```

```json
{
  "name": "pcie_phy_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230379612,
      "name": "pcie_phy_read",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pci-imx6.c:200",
      "file": "drivers/pci/controller/dwc/pci-imx6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_host_init",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_host_init",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230379612,
      "name": "pcie_phy_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int pcie_phy_read(struct imx6_pcie * imx6_pcie, int addr, u16 * data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int pcie_phy_read(struct imx6_pcie * imx6_pcie, int addr, u16 * data)
```
</details>
</li>
</ul>
