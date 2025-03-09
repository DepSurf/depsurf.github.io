# Function: <code>pm_runtime_force_suspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int pm_runtime_force_suspend(struct device * dev)
```

```json
{
  "name": "pm_runtime_force_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584447792,
      "name": "pm_runtime_force_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1443",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584447792,
      "name": "pm_runtime_force_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int pm_runtime_force_suspend(struct device * dev)
```

```json
{
  "name": "pm_runtime_force_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584783840,
      "name": "pm_runtime_force_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1461",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_freeze_noirq",
        "drivers/base/power/domain.c:pm_genpd_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584783840,
      "name": "pm_runtime_force_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pm_runtime_force_suspend(struct device * dev)
```

```json
{
  "name": "pm_runtime_force_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584974032,
      "name": "pm_runtime_force_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1637",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_freeze_noirq",
        "drivers/base/power/domain.c:pm_genpd_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584974032,
      "name": "pm_runtime_force_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pm_runtime_force_suspend(struct device * dev)
```

```json
{
  "name": "pm_runtime_force_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585059008,
      "name": "pm_runtime_force_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1637",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_freeze_noirq",
        "drivers/base/power/domain.c:genpd_finish_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585059008,
      "name": "pm_runtime_force_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pm_runtime_force_suspend(struct device * dev)
```

```json
{
  "name": "pm_runtime_force_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585481840,
      "name": "pm_runtime_force_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1628",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_freeze_noirq",
        "drivers/base/power/domain.c:genpd_finish_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585481840,
      "name": "pm_runtime_force_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int pm_runtime_force_suspend(struct device * dev)
```

```json
{
  "name": "pm_runtime_force_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585725104,
      "name": "pm_runtime_force_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1642",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585725104,
      "name": "pm_runtime_force_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
int pm_runtime_force_suspend(struct device * dev)
```

```json
{
  "name": "pm_runtime_force_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585857088,
      "name": "pm_runtime_force_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1650",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585857088,
      "name": "pm_runtime_force_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pm_runtime_force_suspend(struct device * dev)
```

```json
{
  "name": "pm_runtime_force_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586094400,
      "name": "pm_runtime_force_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1735",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586094400,
      "name": "pm_runtime_force_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pm_runtime_force_suspend(struct device * dev)
```

```json
{
  "name": "pm_runtime_force_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586241952,
      "name": "pm_runtime_force_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1740",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586241952,
      "name": "pm_runtime_force_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int pm_runtime_force_suspend(struct device * dev)
```

```json
{
  "name": "pm_runtime_force_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587010224,
      "name": "pm_runtime_force_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1765",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587010224,
      "name": "pm_runtime_force_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int pm_runtime_force_suspend(struct device * dev)
```

```json
{
  "name": "pm_runtime_force_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587094960,
      "name": "pm_runtime_force_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1786",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587094960,
      "name": "pm_runtime_force_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int pm_runtime_force_suspend(struct device * dev)
```

```json
{
  "name": "pm_runtime_force_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586981296,
      "name": "pm_runtime_force_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1787",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586981296,
      "name": "pm_runtime_force_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int pm_runtime_force_suspend(struct device * dev)
```

```json
{
  "name": "pm_runtime_force_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587545952,
      "name": "pm_runtime_force_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1821",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587545952,
      "name": "pm_runtime_force_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int pm_runtime_force_suspend(struct device * dev)
```

```json
{
  "name": "pm_runtime_force_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588879648,
      "name": "pm_runtime_force_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1854",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588879648,
      "name": "pm_runtime_force_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
int pm_runtime_force_suspend(struct device * dev)
```

```json
{
  "name": "pm_runtime_force_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590388160,
      "name": "pm_runtime_force_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1868",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590388160,
      "name": "pm_runtime_force_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
int pm_runtime_force_suspend(struct device * dev)
```

```json
{
  "name": "pm_runtime_force_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590707888,
      "name": "pm_runtime_force_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1872",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590707888,
      "name": "pm_runtime_force_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
int pm_runtime_force_suspend(struct device * dev)
```

```json
{
  "name": "pm_runtime_force_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591069744,
      "name": "pm_runtime_force_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1873",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591069744,
      "name": "pm_runtime_force_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int pm_runtime_force_suspend(struct device * dev)
```

```json
{
  "name": "pm_runtime_force_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499058112,
      "name": "pm_runtime_force_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1740",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/arm-smmu.c:arm_smmu_device_shutdown",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_shutdown",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_device_remove",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_suspend",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499058112,
      "name": "pm_runtime_force_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int pm_runtime_force_suspend(struct device * dev)
```

```json
{
  "name": "pm_runtime_force_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231615272,
      "name": "pm_runtime_force_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1740",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/bus/ti-sysc.c:sysc_noirq_suspend",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_shutdown",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_device_remove",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_suspend",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231615272,
      "name": "pm_runtime_force_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int pm_runtime_force_suspend(struct device * dev)
```

```json
{
  "name": "pm_runtime_force_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292231408,
      "name": "pm_runtime_force_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1740",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292231408,
      "name": "pm_runtime_force_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int pm_runtime_force_suspend(struct device * dev)
```

```json
{
  "name": "pm_runtime_force_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276415166,
      "name": "pm_runtime_force_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1740",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276415166,
      "name": "pm_runtime_force_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int pm_runtime_force_suspend(struct device * dev)
```

```json
{
  "name": "pm_runtime_force_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586002160,
      "name": "pm_runtime_force_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1740",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586002160,
      "name": "pm_runtime_force_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int pm_runtime_force_suspend(struct device * dev)
```

```json
{
  "name": "pm_runtime_force_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585851312,
      "name": "pm_runtime_force_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1740",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585851312,
      "name": "pm_runtime_force_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int pm_runtime_force_suspend(struct device * dev)
```

```json
{
  "name": "pm_runtime_force_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586191968,
      "name": "pm_runtime_force_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1740",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586191968,
      "name": "pm_runtime_force_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int pm_runtime_force_suspend(struct device * dev)
```

```json
{
  "name": "pm_runtime_force_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586301632,
      "name": "pm_runtime_force_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1740",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586301632,
      "name": "pm_runtime_force_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
