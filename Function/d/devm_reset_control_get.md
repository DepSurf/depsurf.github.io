# Function: <code>devm_reset_control_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct reset_control * devm_reset_control_get(struct device * dev, const char * id)
```

```json
{
  "name": "devm_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583954128,
      "name": "devm_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:260",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583954128,
      "name": "devm_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devm_reset_control_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584484856,
      "name": "devm_reset_control_get",
      "external": false,
      "loc": "include/linux/reset.h:366",
      "file": "drivers/pci/controller/dwc/pci-meson.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe"
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
  "name": "devm_reset_control_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584681847,
      "name": "devm_reset_control_get",
      "external": false,
      "loc": "include/linux/reset.h:423",
      "file": "drivers/pci/controller/dwc/pci-meson.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "devm_reset_control_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336497184236,
      "name": "devm_reset_control_get",
      "external": false,
      "loc": "include/linux/reset.h:423",
      "file": "drivers/pci/controller/dwc/pcie-qcom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_3_3"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497195732,
      "name": "devm_reset_control_get",
      "external": false,
      "loc": "include/linux/reset.h:423",
      "file": "drivers/pci/controller/dwc/pcie-histb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe"
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
  "name": "devm_reset_control_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230386996,
      "name": "devm_reset_control_get",
      "external": false,
      "loc": "include/linux/reset.h:423",
      "file": "drivers/pci/controller/dwc/pcie-qcom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_3_3"
      ],
      "caller_func": []
    },
    {
      "addr": 3230394956,
      "name": "devm_reset_control_get",
      "external": false,
      "loc": "include/linux/reset.h:423",
      "file": "drivers/pci/controller/dwc/pcie-histb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3230715236,
      "name": "devm_reset_control_get",
      "external": false,
      "loc": "include/linux/reset.h:423",
      "file": "drivers/clk/tegra/clk-dfll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_register"
      ],
      "caller_func": []
    },
    {
      "addr": 3230836120,
      "name": "devm_reset_control_get",
      "external": false,
      "loc": "include/linux/reset.h:423",
      "file": "drivers/dma/tegra20-apb-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_probe"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devm_reset_control_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584769127,
      "name": "devm_reset_control_get",
      "external": false,
      "loc": "include/linux/reset.h:423",
      "file": "drivers/pci/controller/dwc/pci-meson.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe"
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
  "name": "devm_reset_control_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584699911,
      "name": "devm_reset_control_get",
      "external": false,
      "loc": "include/linux/reset.h:423",
      "file": "drivers/pci/controller/dwc/pci-meson.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe"
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
  "name": "devm_reset_control_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584770551,
      "name": "devm_reset_control_get",
      "external": false,
      "loc": "include/linux/reset.h:423",
      "file": "drivers/pci/controller/dwc/pci-meson.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe"
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
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
struct reset_control * devm_reset_control_get(struct device * dev, const char * id)
```
</details>
</li>
</ul>
