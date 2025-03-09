# Function: <code>device_link_add</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct device_link * device_link_add(struct device * consumer, struct device * supplier, u32 flags)
```

```json
{
  "name": "device_link_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584906848,
      "name": "device_link_add",
      "external": true,
      "loc": "drivers/base/core.c:177",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584906848,
      "name": "device_link_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 666
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct device_link * device_link_add(struct device * consumer, struct device * supplier, u32 flags)
```

```json
{
  "name": "device_link_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584991968,
      "name": "device_link_add",
      "external": true,
      "loc": "drivers/base/core.c:178",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584991968,
      "name": "device_link_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 674
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct device_link * device_link_add(struct device * consumer, struct device * supplier, u32 flags)
```

```json
{
  "name": "device_link_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585413856,
      "name": "device_link_add",
      "external": true,
      "loc": "drivers/base/core.c:178",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585413856,
      "name": "device_link_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 674
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct device_link * device_link_add(struct device * consumer, struct device * supplier, u32 flags)
```

```json
{
  "name": "device_link_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585656544,
      "name": "device_link_add",
      "external": true,
      "loc": "drivers/base/core.c:195",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_gpu_hda",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585656544,
      "name": "device_link_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 693
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct device_link * device_link_add(struct device * consumer, struct device * supplier, u32 flags)
```

```json
{
  "name": "device_link_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585788704,
      "name": "device_link_add",
      "external": true,
      "loc": "drivers/base/core.c:196",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_gpu_hda",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/regulator/core.c:_regulator_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585788704,
      "name": "device_link_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 703
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct device_link * device_link_add(struct device * consumer, struct device * supplier, u32 flags)
```

```json
{
  "name": "device_link_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586020560,
      "name": "device_link_add",
      "external": true,
      "loc": "drivers/base/core.c:217",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/pwm/core.c:pwm_get",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/regulator/core.c:_regulator_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586019696,
      "name": "device_link_add.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 860
    },
    {
      "addr": 18446744071586025861,
      "name": "device_link_add.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071586020560,
      "name": "device_link_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct device_link * device_link_add(struct device * consumer, struct device * supplier, u32 flags)
```

```json
{
  "name": "device_link_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586167440,
      "name": "device_link_add",
      "external": true,
      "loc": "drivers/base/core.c:288",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/pwm/core.c:pwm_get",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/regulator/core.c:_regulator_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586167440,
      "name": "device_link_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 978
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct device_link * device_link_add(struct device * consumer, struct device * supplier, u32 flags)
```

```json
{
  "name": "device_link_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586927280,
      "name": "device_link_add",
      "external": true,
      "loc": "drivers/base/core.c:303",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_get",
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/pwm/core.c:pwm_get",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer",
        "drivers/regulator/core.c:_regulator_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586927280,
      "name": "device_link_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1324
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct device_link * device_link_add(struct device * consumer, struct device * supplier, u32 flags)
```

```json
{
  "name": "device_link_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587010976,
      "name": "device_link_add",
      "external": true,
      "loc": "drivers/base/core.c:629",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_get",
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/pwm/core.c:pwm_get",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer",
        "drivers/regulator/core.c:_regulator_get",
        "drivers/base/core.c:fw_devlink_create_devlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587010976,
      "name": "device_link_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1677
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
struct device_link * device_link_add(struct device * consumer, struct device * supplier, u32 flags)
```

```json
{
  "name": "device_link_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586894224,
      "name": "device_link_add",
      "external": true,
      "loc": "drivers/base/core.c:673",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_get",
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/pwm/core.c:pwm_get",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/regulator/core.c:_regulator_get",
        "drivers/base/core.c:fw_devlink_create_devlink",
        "drivers/base/core.c:fw_devlink_create_devlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586894224,
      "name": "device_link_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1725
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
struct device_link * device_link_add(struct device * consumer, struct device * supplier, u32 flags)
```

```json
{
  "name": "device_link_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587456128,
      "name": "device_link_add",
      "external": true,
      "loc": "drivers/base/core.c:684",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_get",
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/pwm/core.c:pwm_get",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/regulator/core.c:_regulator_get",
        "drivers/base/core.c:fw_devlink_create_devlink",
        "drivers/base/core.c:fw_devlink_create_devlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587456128,
      "name": "device_link_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1716
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
struct device_link * device_link_add(struct device * consumer, struct device * supplier, u32 flags)
```

```json
{
  "name": "device_link_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588775040,
      "name": "device_link_add",
      "external": true,
      "loc": "drivers/base/core.c:696",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_get",
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/pwm/core.c:pwm_get",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/regulator/core.c:_regulator_get",
        "drivers/base/core.c:fw_devlink_create_devlink",
        "drivers/base/core.c:fw_devlink_create_devlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588775040,
      "name": "device_link_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1790
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
struct device_link * device_link_add(struct device * consumer, struct device * supplier, u32 flags)
```

```json
{
  "name": "device_link_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590268160,
      "name": "device_link_add",
      "external": true,
      "loc": "drivers/base/core.c:769",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_get",
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/pwm/core.c:pwm_get",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/base/core.c:fw_devlink_create_devlink",
        "drivers/net/phy/phy_device.c:phy_attach_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590268160,
      "name": "device_link_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1910
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
struct device_link * device_link_add(struct device * consumer, struct device * supplier, u32 flags)
```

```json
{
  "name": "device_link_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590588560,
      "name": "device_link_add",
      "external": true,
      "loc": "drivers/base/core.c:711",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_get",
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/pwm/core.c:pwm_get",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/base/core.c:fw_devlink_create_devlink",
        "drivers/net/phy/phy_device.c:phy_attach_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590588560,
      "name": "device_link_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1960
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
struct device_link * device_link_add(struct device * consumer, struct device * supplier, u32 flags)
```

```json
{
  "name": "device_link_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590947232,
      "name": "device_link_add",
      "external": true,
      "loc": "drivers/base/core.c:714",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_get",
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/pwm/core.c:pwm_get",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/base/core.c:fw_devlink_create_devlink",
        "drivers/ata/libata-scsi.c:ata_scsi_slave_alloc",
        "drivers/net/phy/phy_device.c:phy_attach_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590947232,
      "name": "device_link_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2007
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct device_link * device_link_add(struct device * consumer, struct device * supplier, u32 flags)
```

```json
{
  "name": "device_link_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498963400,
      "name": "device_link_add",
      "external": true,
      "loc": "drivers/base/core.c:288",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/bus/fsl-mc/mc-io.c:fsl_mc_portal_allocate",
        "drivers/bus/fsl-mc/fsl-mc-allocator.c:fsl_mc_object_allocate",
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/pci/controller/pcie-cadence.c:cdns_pcie_init_phy",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe",
        "drivers/regulator/core.c:_regulator_get",
        "drivers/iommu/arm-smmu.c:arm_smmu_add_device",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_add_device",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498963400,
      "name": "device_link_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 964
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
struct device_link * device_link_add(struct device * consumer, struct device * supplier, u32 flags)
```

```json
{
  "name": "device_link_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231533576,
      "name": "device_link_add",
      "external": true,
      "loc": "drivers/base/core.c:288",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/pci/controller/pcie-cadence.c:cdns_pcie_init_phy",
        "drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe",
        "drivers/soc/imx/gpc.c:imx_pgc_power_domain_probe",
        "drivers/regulator/core.c:_regulator_get",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_add_device",
        "drivers/iommu/exynos-iommu.c:exynos_iommu_add_device",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231533576,
      "name": "device_link_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 948
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
struct device_link * device_link_add(struct device * consumer, struct device * supplier, u32 flags)
```

```json
{
  "name": "device_link_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292108960,
      "name": "device_link_add",
      "external": true,
      "loc": "drivers/base/core.c:288",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/pci/controller/pcie-cadence.c:cdns_pcie_init_phy",
        "drivers/regulator/core.c:_regulator_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292108960,
      "name": "device_link_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1380
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
struct device_link * device_link_add(struct device * consumer, struct device * supplier, u32 flags)
```

```json
{
  "name": "device_link_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276344386,
      "name": "device_link_add",
      "external": true,
      "loc": "drivers/base/core.c:288",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/pci/controller/pcie-cadence.c:cdns_pcie_init_phy",
        "drivers/regulator/core.c:_regulator_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276344386,
      "name": "device_link_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 820
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct device_link * device_link_add(struct device * consumer, struct device * supplier, u32 flags)
```

```json
{
  "name": "device_link_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585927808,
      "name": "device_link_add",
      "external": true,
      "loc": "drivers/base/core.c:288",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/pwm/core.c:pwm_get",
        "drivers/regulator/core.c:_regulator_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585927808,
      "name": "device_link_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 978
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct device_link * device_link_add(struct device * consumer, struct device * supplier, u32 flags)
```

```json
{
  "name": "device_link_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585776944,
      "name": "device_link_add",
      "external": true,
      "loc": "drivers/base/core.c:288",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/regulator/core.c:_regulator_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585776944,
      "name": "device_link_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 978
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct device_link * device_link_add(struct device * consumer, struct device * supplier, u32 flags)
```

```json
{
  "name": "device_link_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586117456,
      "name": "device_link_add",
      "external": true,
      "loc": "drivers/base/core.c:288",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/pwm/core.c:pwm_get",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/regulator/core.c:_regulator_get",
        "drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586117456,
      "name": "device_link_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 978
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct device_link * device_link_add(struct device * consumer, struct device * supplier, u32 flags)
```

```json
{
  "name": "device_link_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586226064,
      "name": "device_link_add",
      "external": true,
      "loc": "drivers/base/core.c:288",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/pwm/core.c:pwm_get",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/regulator/core.c:_regulator_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586226064,
      "name": "device_link_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 978
    }
  ]
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
struct device_link * device_link_add(struct device * consumer, struct device * supplier, u32 flags)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
