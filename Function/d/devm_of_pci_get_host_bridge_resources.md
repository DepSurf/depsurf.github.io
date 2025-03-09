# Function: <code>devm_of_pci_get_host_bridge_resources</code>

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
  "name": "devm_of_pci_get_host_bridge_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "devm_of_pci_get_host_bridge_resources",
      "external": false,
      "loc": "drivers/pci/pci.h:462",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "declared, inlined",
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
  "name": "devm_of_pci_get_host_bridge_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "devm_of_pci_get_host_bridge_resources",
      "external": false,
      "loc": "drivers/pci/pci.h:582",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "declared, inlined",
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
  "name": "devm_of_pci_get_host_bridge_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "devm_of_pci_get_host_bridge_resources",
      "external": false,
      "loc": "drivers/pci/pci.h:587",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "declared, inlined",
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
  "name": "devm_of_pci_get_host_bridge_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "devm_of_pci_get_host_bridge_resources",
      "external": false,
      "loc": "drivers/pci/pci.h:634",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "declared, inlined",
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
int devm_of_pci_get_host_bridge_resources(struct device * dev, unsigned char busno, unsigned char bus_max, struct list_head * resources, resource_size_t * io_base)
```

```json
{
  "name": "devm_of_pci_get_host_bridge_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496944960,
      "name": "devm_of_pci_get_host_bridge_resources",
      "external": true,
      "loc": "drivers/pci/of.c:258",
      "file": "drivers/pci/of.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/of.c:pci_parse_request_of_pci_ranges",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe",
        "drivers/pci/controller/pcie-altera.c:altera_pcie_probe",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe",
        "drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_probe",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init",
        "drivers/pci/controller/pci-xgene.c:xgene_pcie_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496944960,
      "name": "devm_of_pci_get_host_bridge_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 656
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
int devm_of_pci_get_host_bridge_resources(struct device * dev, unsigned char busno, unsigned char bus_max, struct list_head * resources, resource_size_t * io_base)
```

```json
{
  "name": "devm_of_pci_get_host_bridge_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230211372,
      "name": "devm_of_pci_get_host_bridge_resources",
      "external": true,
      "loc": "drivers/pci/of.c:258",
      "file": "drivers/pci/of.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/of.c:pci_parse_request_of_pci_ranges",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/pci/controller/pci-v3-semi.c:v3_pci_probe",
        "drivers/pci/controller/pcie-altera.c:altera_pcie_probe",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230211372,
      "name": "devm_of_pci_get_host_bridge_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 748
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int devm_of_pci_get_host_bridge_resources(struct device * dev, unsigned char busno, unsigned char bus_max, struct list_head * resources, resource_size_t * io_base)
```

```json
{
  "name": "devm_of_pci_get_host_bridge_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291039424,
      "name": "devm_of_pci_get_host_bridge_resources",
      "external": true,
      "loc": "drivers/pci/of.c:258",
      "file": "drivers/pci/of.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/of.c:pci_parse_request_of_pci_ranges",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291039424,
      "name": "devm_of_pci_get_host_bridge_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 876
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int devm_of_pci_get_host_bridge_resources(struct device * dev, unsigned char busno, unsigned char bus_max, struct list_head * resources, resource_size_t * io_base)
```

```json
{
  "name": "devm_of_pci_get_host_bridge_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275618474,
      "name": "devm_of_pci_get_host_bridge_resources",
      "external": true,
      "loc": "drivers/pci/of.c:258",
      "file": "drivers/pci/of.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/of.c:pci_parse_request_of_pci_ranges",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275618474,
      "name": "devm_of_pci_get_host_bridge_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
  "name": "devm_of_pci_get_host_bridge_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "devm_of_pci_get_host_bridge_resources",
      "external": false,
      "loc": "drivers/pci/pci.h:634",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "declared, inlined",
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
  "name": "devm_of_pci_get_host_bridge_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "devm_of_pci_get_host_bridge_resources",
      "external": false,
      "loc": "drivers/pci/pci.h:634",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "declared, inlined",
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
  "name": "devm_of_pci_get_host_bridge_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "devm_of_pci_get_host_bridge_resources",
      "external": false,
      "loc": "drivers/pci/pci.h:634",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "declared, inlined",
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
  "name": "devm_of_pci_get_host_bridge_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "devm_of_pci_get_host_bridge_resources",
      "external": false,
      "loc": "drivers/pci/pci.h:634",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "declared, inlined",
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int devm_of_pci_get_host_bridge_resources(struct device * dev, unsigned char busno, unsigned char bus_max, struct list_head * resources, resource_size_t * io_base)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int devm_of_pci_get_host_bridge_resources(struct device * dev, unsigned char busno, unsigned char bus_max, struct list_head * resources, resource_size_t * io_base)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int devm_of_pci_get_host_bridge_resources(struct device * dev, unsigned char busno, unsigned char bus_max, struct list_head * resources, resource_size_t * io_base)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int devm_of_pci_get_host_bridge_resources(struct device * dev, unsigned char busno, unsigned char bus_max, struct list_head * resources, resource_size_t * io_base)
```
</details>
</li>
</ul>
