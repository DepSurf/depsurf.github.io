# Function: <code>of_find_device_by_node</code>

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
  "name": "of_find_device_by_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_find_device_by_node",
      "external": false,
      "loc": "include/linux/of_platform.h:58",
      "file": "drivers/media/cec/cec-notifier.c",
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
  "name": "of_find_device_by_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_find_device_by_node",
      "external": false,
      "loc": "include/linux/of_platform.h:58",
      "file": "drivers/media/cec/cec-notifier.c",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct platform_device * of_find_device_by_node(struct device_node * np)
```

```json
{
  "name": "of_find_device_by_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501612576,
      "name": "of_find_device_by_node",
      "external": true,
      "loc": "drivers/of/platform.c:49",
      "file": "drivers/of/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/genalloc.c:of_gen_pool_get",
        "lib/genalloc.c:of_gen_pool_get",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_of_xlate",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_of_xlate",
        "drivers/ata/libahci_platform.c:ahci_platform_get_resources",
        "drivers/net/ethernet/freescale/fman/fman_port.c:fman_port_probe",
        "drivers/net/ethernet/freescale/fman/mac.c:mac_probe",
        "drivers/net/ethernet/freescale/fman/mac.c:mac_probe",
        "drivers/usb/common/common.c:usb_of_get_companion_dev",
        "drivers/media/cec/cec-notifier.c:cec_notifier_parse_hdmi_phandle",
        "drivers/firmware/raspberrypi.c:rpi_firmware_get",
        "drivers/memory/mtk-smi.c:mtk_smi_larb_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501612576,
      "name": "of_find_device_by_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct platform_device * of_find_device_by_node(struct device_node * np)
```

```json
{
  "name": "of_find_device_by_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234136028,
      "name": "of_find_device_by_node",
      "external": true,
      "loc": "drivers/of/platform.c:49",
      "file": "drivers/of/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-imx/pm-imx6.c:imx6q_suspend_init",
        "lib/genalloc.c:of_gen_pool_get",
        "lib/genalloc.c:of_gen_pool_get",
        "drivers/clk/tegra/clk-emc.c:emc_set_timing",
        "drivers/dma/ti/dma-crossbar.c:ti_dra7_xbar_route_allocate",
        "drivers/dma/ti/dma-crossbar.c:ti_am335x_xbar_route_allocate",
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_of_xlate",
        "drivers/iommu/omap-iommu.c:_omap_iommu_add_device",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_of_xlate",
        "drivers/iommu/tegra-smmu.c:tegra_smmu_add_device",
        "drivers/iommu/exynos-iommu.c:exynos_iommu_of_xlate",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_of_xlate",
        "drivers/ata/libahci_platform.c:ahci_platform_get_resources",
        "drivers/mtd/nand/raw/omap2.c:omap_nand_attach_chip",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_probe_dt",
        "drivers/usb/common/common.c:usb_of_get_companion_dev",
        "drivers/media/cec/cec-notifier.c:cec_notifier_parse_hdmi_phandle",
        "drivers/firmware/tegra/bpmp.c:tegra_bpmp_get",
        "drivers/memory/mtk-smi.c:mtk_smi_larb_probe",
        "drivers/memory/tegra/tegra124-emc.c:tegra_emc_probe",
        "sound/soc/fsl/imx-sgtl5000.c:imx_sgtl5000_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234136028,
      "name": "of_find_device_by_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct platform_device * of_find_device_by_node(struct device_node * np)
```

```json
{
  "name": "of_find_device_by_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295039328,
      "name": "of_find_device_by_node",
      "external": true,
      "loc": "drivers/of/platform.c:49",
      "file": "drivers/of/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/genalloc.c:of_gen_pool_get",
        "lib/genalloc.c:of_gen_pool_get",
        "drivers/usb/common/common.c:usb_of_get_companion_dev",
        "drivers/media/cec/cec-notifier.c:cec_notifier_parse_hdmi_phandle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295039328,
      "name": "of_find_device_by_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct platform_device * of_find_device_by_node(struct device_node * np)
```

```json
{
  "name": "of_find_device_by_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278077012,
      "name": "of_find_device_by_node",
      "external": true,
      "loc": "drivers/of/platform.c:49",
      "file": "drivers/of/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/genalloc.c:of_gen_pool_get",
        "lib/genalloc.c:of_gen_pool_get",
        "drivers/usb/common/common.c:usb_of_get_companion_dev",
        "drivers/media/cec/cec-notifier.c:cec_notifier_parse_hdmi_phandle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278077012,
      "name": "of_find_device_by_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
  "name": "of_find_device_by_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_find_device_by_node",
      "external": false,
      "loc": "include/linux/of_platform.h:58",
      "file": "drivers/media/cec/cec-notifier.c",
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
  "name": "of_find_device_by_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_find_device_by_node",
      "external": false,
      "loc": "include/linux/of_platform.h:58",
      "file": "drivers/media/cec/cec-notifier.c",
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
  "name": "of_find_device_by_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_find_device_by_node",
      "external": false,
      "loc": "include/linux/of_platform.h:58",
      "file": "drivers/media/cec/cec-notifier.c",
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
  "name": "of_find_device_by_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_find_device_by_node",
      "external": false,
      "loc": "include/linux/of_platform.h:58",
      "file": "drivers/media/cec/cec-notifier.c",
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
struct platform_device * of_find_device_by_node(struct device_node * np)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct platform_device * of_find_device_by_node(struct device_node * np)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct platform_device * of_find_device_by_node(struct device_node * np)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct platform_device * of_find_device_by_node(struct device_node * np)
```
</details>
</li>
</ul>
