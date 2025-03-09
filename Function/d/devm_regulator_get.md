# Function: <code>devm_regulator_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct regulator * devm_regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "devm_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583951184,
      "name": "devm_regulator_get",
      "external": true,
      "loc": "drivers/regulator/devres.c:75",
      "file": "drivers/regulator/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/devres.c:devm_regulator_bulk_get"
      ],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/phy/phy-generic.c:usb_phy_gen_create_phy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583951184,
      "name": "devm_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct regulator * devm_regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "devm_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584283360,
      "name": "devm_regulator_get",
      "external": true,
      "loc": "drivers/regulator/devres.c:75",
      "file": "drivers/regulator/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584283360,
      "name": "devm_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct regulator * devm_regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "devm_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584466087,
      "name": "devm_regulator_get",
      "external": true,
      "loc": "drivers/regulator/devres.c:75",
      "file": "drivers/regulator/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/devres.c:devm_regulator_bulk_get"
      ],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584465216,
      "name": "devm_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct regulator * devm_regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "devm_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584549824,
      "name": "devm_regulator_get",
      "external": true,
      "loc": "drivers/regulator/devres.c:56",
      "file": "drivers/regulator/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584549824,
      "name": "devm_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct regulator * devm_regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "devm_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584960096,
      "name": "devm_regulator_get",
      "external": true,
      "loc": "drivers/regulator/devres.c:56",
      "file": "drivers/regulator/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584960096,
      "name": "devm_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct regulator * devm_regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "devm_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585193056,
      "name": "devm_regulator_get",
      "external": true,
      "loc": "drivers/regulator/devres.c:56",
      "file": "drivers/regulator/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585193056,
      "name": "devm_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct regulator * devm_regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "devm_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585310592,
      "name": "devm_regulator_get",
      "external": true,
      "loc": "drivers/regulator/devres.c:56",
      "file": "drivers/regulator/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585310592,
      "name": "devm_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct regulator * devm_regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "devm_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585522496,
      "name": "devm_regulator_get",
      "external": true,
      "loc": "drivers/regulator/devres.c:51",
      "file": "drivers/regulator/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585522496,
      "name": "devm_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct regulator * devm_regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "devm_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585663664,
      "name": "devm_regulator_get",
      "external": true,
      "loc": "drivers/regulator/devres.c:51",
      "file": "drivers/regulator/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585663664,
      "name": "devm_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct regulator * devm_regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "devm_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586389040,
      "name": "devm_regulator_get",
      "external": true,
      "loc": "drivers/regulator/devres.c:51",
      "file": "drivers/regulator/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586389040,
      "name": "devm_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct regulator * devm_regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "devm_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586504016,
      "name": "devm_regulator_get",
      "external": true,
      "loc": "drivers/regulator/devres.c:51",
      "file": "drivers/regulator/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586504016,
      "name": "devm_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct regulator * devm_regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "devm_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586388176,
      "name": "devm_regulator_get",
      "external": true,
      "loc": "drivers/regulator/devres.c:51",
      "file": "drivers/regulator/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586388176,
      "name": "devm_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct regulator * devm_regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "devm_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586912640,
      "name": "devm_regulator_get",
      "external": true,
      "loc": "drivers/regulator/devres.c:51",
      "file": "drivers/regulator/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586912640,
      "name": "devm_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct regulator * devm_regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "devm_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588204816,
      "name": "devm_regulator_get",
      "external": true,
      "loc": "drivers/regulator/devres.c:51",
      "file": "drivers/regulator/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588204816,
      "name": "devm_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
struct regulator * devm_regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "devm_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589610960,
      "name": "devm_regulator_get",
      "external": true,
      "loc": "drivers/regulator/devres.c:51",
      "file": "drivers/regulator/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589610960,
      "name": "devm_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
struct regulator * devm_regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "devm_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589914496,
      "name": "devm_regulator_get",
      "external": true,
      "loc": "drivers/regulator/devres.c:51",
      "file": "drivers/regulator/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589914496,
      "name": "devm_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
struct regulator * devm_regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "devm_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590252528,
      "name": "devm_regulator_get",
      "external": true,
      "loc": "drivers/regulator/devres.c:51",
      "file": "drivers/regulator/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590252528,
      "name": "devm_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
struct regulator * devm_regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "devm_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498325216,
      "name": "devm_regulator_get",
      "external": true,
      "loc": "drivers/regulator/devres.c:51",
      "file": "drivers/regulator/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_1_0_0",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/ata/libahci_platform.c:ahci_platform_get_resources",
        "drivers/ata/libahci_platform.c:ahci_platform_get_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498325216,
      "name": "devm_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct regulator * devm_regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "devm_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231005964,
      "name": "devm_regulator_get",
      "external": true,
      "loc": "drivers/regulator/devres.c:51",
      "file": "drivers/regulator/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_1_0_0",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_register",
        "drivers/clk/tegra/clk-tegra124-dfll-fcpu.c:tegra124_dfll_fcpu_probe",
        "drivers/soc/imx/gpc.c:imx_gpc_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/ata/libahci_platform.c:ahci_platform_get_resources",
        "drivers/ata/libahci_platform.c:ahci_platform_get_resources",
        "drivers/usb/phy/phy-generic.c:usb_phy_gen_create_phy",
        "sound/soc/soc-dapm.c:snd_soc_dapm_new_control_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231005964,
      "name": "devm_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct regulator * devm_regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "devm_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291502320,
      "name": "devm_regulator_get",
      "external": true,
      "loc": "drivers/regulator/devres.c:51",
      "file": "drivers/regulator/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291502320,
      "name": "devm_regulator_get",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct regulator * devm_regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "devm_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276014046,
      "name": "devm_regulator_get",
      "external": true,
      "loc": "drivers/regulator/devres.c:51",
      "file": "drivers/regulator/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276014046,
      "name": "devm_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct regulator * devm_regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "devm_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585424688,
      "name": "devm_regulator_get",
      "external": true,
      "loc": "drivers/regulator/devres.c:51",
      "file": "drivers/regulator/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585424688,
      "name": "devm_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct regulator * devm_regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "devm_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585294736,
      "name": "devm_regulator_get",
      "external": true,
      "loc": "drivers/regulator/devres.c:51",
      "file": "drivers/regulator/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585294736,
      "name": "devm_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct regulator * devm_regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "devm_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585614064,
      "name": "devm_regulator_get",
      "external": true,
      "loc": "drivers/regulator/devres.c:51",
      "file": "drivers/regulator/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585614064,
      "name": "devm_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct regulator * devm_regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "devm_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585722192,
      "name": "devm_regulator_get",
      "external": true,
      "loc": "drivers/regulator/devres.c:51",
      "file": "drivers/regulator/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585722192,
      "name": "devm_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
