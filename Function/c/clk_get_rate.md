# Function: <code>clk_get_rate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int clk_get_rate(struct clk * clk)
```

```json
{
  "name": "clk_get_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586077456,
      "name": "clk_get_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:1056",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586077456,
      "name": "clk_get_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
long unsigned int clk_get_rate(struct clk * clk)
```

```json
{
  "name": "clk_get_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586490816,
      "name": "clk_get_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:1105",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:clock",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586490816,
      "name": "clk_get_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
long unsigned int clk_get_rate(struct clk * clk)
```

```json
{
  "name": "clk_get_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584297536,
      "name": "clk_get_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:1105",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:clock",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584297536,
      "name": "clk_get_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
long unsigned int clk_get_rate(struct clk * clk)
```

```json
{
  "name": "clk_get_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584377088,
      "name": "clk_get_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:1107",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_get_clk_rate_khz",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get",
        "lib/vsprintf.c:clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584377088,
      "name": "clk_get_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
long unsigned int clk_get_rate(struct clk * clk)
```

```json
{
  "name": "clk_get_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584784448,
      "name": "clk_get_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:1184",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_get_clk_rate_khz",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get",
        "lib/vsprintf.c:clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584784448,
      "name": "clk_get_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
long unsigned int clk_get_rate(struct clk * clk)
```

```json
{
  "name": "clk_get_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585010736,
      "name": "clk_get_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:1393",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_get_clk_rate_khz",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585010736,
      "name": "clk_get_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
long unsigned int clk_get_rate(struct clk * clk)
```

```json
{
  "name": "clk_get_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585117536,
      "name": "clk_get_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:1499",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_get_clk_rate_khz",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585117536,
      "name": "clk_get_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
long unsigned int clk_get_rate(struct clk * clk)
```

```json
{
  "name": "clk_get_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585323472,
      "name": "clk_get_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:1617",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_get_clk_rate_khz",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585323472,
      "name": "clk_get_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
long unsigned int clk_get_rate(struct clk * clk)
```

```json
{
  "name": "clk_get_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585461840,
      "name": "clk_get_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:1625",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_get_clk_rate_khz",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585461840,
      "name": "clk_get_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int clk_get_rate(struct clk * clk)
```

```json
{
  "name": "clk_get_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586178768,
      "name": "clk_get_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:1622",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/twl-core.c:clocks_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586178768,
      "name": "clk_get_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int clk_get_rate(struct clk * clk)
```

```json
{
  "name": "clk_get_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586298064,
      "name": "clk_get_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:1631",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/twl-core.c:clocks_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586298064,
      "name": "clk_get_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int clk_get_rate(struct clk * clk)
```

```json
{
  "name": "clk_get_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586171312,
      "name": "clk_get_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:1652",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/opp/core.c:_set_opp",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586171312,
      "name": "clk_get_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int clk_get_rate(struct clk * clk)
```

```json
{
  "name": "clk_get_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586677760,
      "name": "clk_get_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:1652",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/opp/core.c:_set_opp",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586677760,
      "name": "clk_get_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int clk_get_rate(struct clk * clk)
```

```json
{
  "name": "clk_get_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587948480,
      "name": "clk_get_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:1666",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/opp/core.c:_set_opp",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587948480,
      "name": "clk_get_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int clk_get_rate(struct clk * clk)
```

```json
{
  "name": "clk_get_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589305376,
      "name": "clk_get_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:1846",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/opp/core.c:_set_opp",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589305376,
      "name": "clk_get_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int clk_get_rate(struct clk * clk)
```

```json
{
  "name": "clk_get_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589602000,
      "name": "clk_get_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:1891",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/opp/core.c:_set_opp",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589602000,
      "name": "clk_get_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int clk_get_rate(struct clk * clk)
```

```json
{
  "name": "clk_get_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589911776,
      "name": "clk_get_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:1891",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/opp/core.c:_set_opp",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589911776,
      "name": "clk_get_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
long unsigned int clk_get_rate(struct clk * clk)
```

```json
{
  "name": "clk_get_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497751424,
      "name": "clk_get_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:1625",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_get_debounce_div",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_host_init",
        "drivers/video/fbdev/mx3fb.c:sdc_init_panel",
        "drivers/clk/clk-qoriq.c:clockgen_init",
        "drivers/clk/clk-qoriq.c:clockgen_init",
        "drivers/clk/imx/clk-cpu.c:clk_cpu_recalc_rate",
        "drivers/clk/renesas/rcar-gen3-cpg.c:rcar_gen3_cpg_clk_register",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_register_core_clk",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_clk_src_twocell_get",
        "drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_notifier_cb",
        "drivers/clk/rockchip/clk-rk3188.c:rk3188a_clk_init",
        "drivers/clk/sunxi/clk-mod0.c:mmc_set_phase",
        "drivers/clk/sunxi/clk-mod0.c:mmc_set_phase",
        "drivers/clk/sunxi/clk-mod0.c:mmc_get_phase",
        "drivers/clk/sunxi/clk-mod0.c:mmc_get_phase",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_probe",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe",
        "drivers/tty/serial/amba-pl011.c:pl011_console_setup",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_console_setup",
        "drivers/tty/serial/meson_uart.c:meson_uart_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/msm_serial.c:msm_serial_probe",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe",
        "drivers/tty/serial/owl-uart.c:owl_uart_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/ata/ahci_imx.c:imx_ahci_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_init",
        "drivers/net/ethernet/freescale/fman/fman.c:read_dts_node",
        "drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_get_clk_rate_khz",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe",
        "drivers/watchdog/rtd119x_wdt.c:rtd119x_wdt_probe",
        "drivers/watchdog/rtd119x_wdt.c:rtd119x_wdt_set_timeout",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get",
        "drivers/mmc/host/mmci.c:mmci_probe",
        "drivers/mmc/host/mmci.c:mmci_probe",
        "drivers/mmc/host/mmci.c:mmci_set_ios",
        "drivers/clocksource/timer-of.c:timer_of_init",
        "drivers/clocksource/sh_cmt.c:sh_cmt_setup",
        "drivers/clocksource/sh_cmt.c:sh_cmt_setup",
        "drivers/clocksource/sh_tmu.c:sh_tmu_setup",
        "drivers/clocksource/timer-rockchip.c:rk_timer_probe",
        "drivers/clocksource/timer-owl.c:owl_timer_init",
        "drivers/clocksource/timer-sp804.c:sp804_get_clock_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497751424,
      "name": "clk_get_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
long unsigned int clk_get_rate(struct clk * clk)
```

```json
{
  "name": "clk_get_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230576664,
      "name": "clk_get_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:1625",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/smp_twd.c:twd_local_timer_of_register",
        "arch/arm/mach-mvebu/platsmp.c:armada_xp_sync_secondary_clk",
        "arch/arm/mach-omap2/io.c:omap_sdrc_init",
        "arch/arm/mach-omap2/timer.c:realtime_counter_init",
        "arch/arm/mach-omap2/timer.c:omap_dm_timer_init_one",
        "arch/arm/mach-omap2/voltage.c:omap_voltage_late_init",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_host_init",
        "drivers/video/fbdev/mx3fb.c:__set_par",
        "drivers/clk/clk-qoriq.c:clockgen_init",
        "drivers/clk/clk-qoriq.c:clockgen_init",
        "drivers/clk/imx/clk-cpu.c:clk_cpu_recalc_rate",
        "drivers/clk/imx/clk-vf610.c:vf610_clocks_init",
        "drivers/clk/imx/clk-vf610.c:vf610_clocks_init",
        "drivers/clk/imx/clk-vf610.c:vf610_clocks_init",
        "drivers/clk/imx/clk-vf610.c:vf610_clocks_init",
        "drivers/clk/imx/clk-vf610.c:vf610_clocks_init",
        "drivers/clk/imx/clk-vf610.c:vf610_clocks_init",
        "drivers/clk/renesas/r7s9210-cpg-mssr.c:rza2_cpg_clk_register",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_register_mod_clk",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_register_core_clk",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_clk_src_twocell_get",
        "drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_notifier_cb",
        "drivers/clk/rockchip/clk-rk3188.c:rk3188a_clk_init",
        "drivers/clk/samsung/clk.c:_get_rate",
        "drivers/clk/samsung/clk-exynos5410.c:exynos5410_clk_init",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_register",
        "drivers/clk/tegra/clk-dfll.c:dfll_init",
        "drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllss",
        "drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllc",
        "drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllm",
        "drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllxc",
        "drivers/clk/tegra/clk-emc.c:emc_set_rate",
        "drivers/clk/tegra/clk-emc.c:emc_set_timing",
        "drivers/clk/tegra/clk-emc.c:emc_set_timing",
        "drivers/clk/ti/clk-3xxx.c:omap3xxx_dt_clk_init",
        "drivers/clk/ti/clk-3xxx.c:omap3xxx_dt_clk_init",
        "drivers/clk/ti/clk-3xxx.c:omap3xxx_dt_clk_init",
        "drivers/clk/ti/clk-3xxx.c:omap3xxx_dt_clk_init",
        "drivers/soc/imx/gpc.c:imx_gpc_probe",
        "drivers/soc/tegra/pmc.c:tegra_pmc_enter_suspend_mode",
        "drivers/regulator/ti-abb-regulator.c:ti_abb_probe",
        "drivers/regulator/ti-abb-regulator.c:ti_abb_probe",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_setup",
        "drivers/tty/serial/amba-pl011.c:pl011_console_setup",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_console_setup",
        "drivers/tty/serial/meson_uart.c:meson_uart_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/msm_serial.c:msm_serial_probe",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe",
        "drivers/tty/serial/owl-uart.c:owl_uart_probe",
        "drivers/tty/serial/rda-uart.c:rda_uart_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/ata/ahci_imx.c:imx_ahci_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_init",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_probe",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_get_clk_rate_khz",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_init",
        "drivers/power/avs/smartreflex.c:sr_set_clk_length",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get",
        "drivers/cpufreq/mvebu-cpufreq.c:armada_xp_pmsu_cpufreq_init",
        "drivers/cpufreq/mvebu-cpufreq.c:armada_xp_pmsu_cpufreq_init",
        "drivers/cpufreq/mvebu-cpufreq.c:armada_xp_pmsu_cpufreq_init",
        "drivers/cpufreq/tegra20-cpufreq.c:tegra_target",
        "drivers/cpufreq/tegra20-cpufreq.c:tegra_get_intermediate",
        "drivers/cpufreq/tegra124-cpufreq.c:tegra124_cpufreq_probe",
        "drivers/mmc/host/mmci.c:mmci_probe",
        "drivers/mmc/host/mmci.c:mmci_probe",
        "drivers/mmc/host/mmci.c:mmci_set_ios",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_request",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_clock",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_clock",
        "drivers/mmc/host/sdhci-pltfm.c:sdhci_pltfm_clk_get_max_clock",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe",
        "drivers/clocksource/timer-of.c:timer_of_init",
        "drivers/clocksource/sh_cmt.c:sh_cmt_setup",
        "drivers/clocksource/sh_cmt.c:sh_cmt_setup",
        "drivers/clocksource/sh_mtu2.c:sh_mtu2_clock_event_set_periodic",
        "drivers/clocksource/renesas-ostm.c:ostm_init",
        "drivers/clocksource/sh_tmu.c:sh_tmu_setup",
        "drivers/clocksource/em_sti.c:em_sti_probe",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_stop",
        "drivers/clocksource/dw_apb_timer_of.c:timer_get_base_and_rate",
        "drivers/clocksource/timer-rockchip.c:rk_timer_probe",
        "drivers/clocksource/timer-armada-370-xp.c:armada_370_timer_init",
        "drivers/clocksource/timer-armada-370-xp.c:armada_375_timer_init",
        "drivers/clocksource/timer-armada-370-xp.c:armada_375_timer_init",
        "drivers/clocksource/timer-armada-370-xp.c:armada_xp_timer_init",
        "drivers/clocksource/timer-orion.c:orion_timer_init",
        "drivers/clocksource/timer-orion.c:orion_timer_init",
        "drivers/clocksource/exynos_mct.c:mct_init_dt",
        "drivers/clocksource/timer-owl.c:owl_timer_init",
        "drivers/clocksource/arm_global_timer.c:global_timer_of_register",
        "drivers/clocksource/timer-sp804.c:sp804_get_clock_rate",
        "drivers/clocksource/timer-imx-gpt.c:_mxc_timer_init",
        "drivers/clocksource/timer-imx-gpt.c:_mxc_timer_init",
        "drivers/clocksource/timer-imx-gpt.c:imx6dl_gpt_setup_tctl",
        "drivers/clocksource/timer-imx-gpt.c:imx31_gpt_setup_tctl",
        "drivers/devfreq/exynos-bus.c:exynos_bus_probe",
        "drivers/memory/omap-gpmc.c:gpmc_probe",
        "drivers/memory/omap-gpmc.c:gpmc_calc_timings",
        "drivers/memory/omap-gpmc.c:gpmc_calc_timings",
        "drivers/memory/omap-gpmc.c:gpmc_calc_timings",
        "drivers/memory/omap-gpmc.c:gpmc_calc_timings",
        "drivers/memory/omap-gpmc.c:gpmc_calc_timings",
        "drivers/memory/omap-gpmc.c:gpmc_calc_timings",
        "drivers/memory/omap-gpmc.c:gpmc_calc_timings",
        "drivers/memory/omap-gpmc.c:gpmc_calc_timings",
        "drivers/memory/omap-gpmc.c:gpmc_calc_timings",
        "drivers/memory/omap-gpmc.c:gpmc_calc_timings",
        "drivers/memory/omap-gpmc.c:gpmc_calc_timings",
        "drivers/memory/omap-gpmc.c:gpmc_calc_timings",
        "drivers/memory/omap-gpmc.c:gpmc_calc_timings",
        "drivers/memory/omap-gpmc.c:gpmc_round_ps_to_sync_clk",
        "drivers/memory/omap-gpmc.c:gpmc_round_ps_to_sync_clk",
        "drivers/memory/omap-gpmc.c:gpmc_cs_set_timings",
        "drivers/memory/omap-gpmc.c:gpmc_calc_divider",
        "drivers/memory/omap-gpmc.c:set_gpmc_timing_reg",
        "drivers/memory/omap-gpmc.c:gpmc_round_ps_to_ticks",
        "drivers/memory/omap-gpmc.c:gpmc_round_ps_to_ticks",
        "drivers/memory/omap-gpmc.c:gpmc_ticks_to_ns",
        "drivers/memory/mvebu-devbus.c:mvebu_devbus_probe",
        "drivers/memory/tegra/mc.c:tegra_mc_probe",
        "drivers/memory/tegra/tegra124-emc.c:emc_debug_rate_get",
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_set_bclk",
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_set_bclk",
        "sound/soc/fsl/imx-sgtl5000.c:imx_sgtl5000_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230576664,
      "name": "clk_get_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "clk_get_rate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_get_rate",
      "external": false,
      "loc": "include/linux/clk.h:837",
      "file": "drivers/gpio/gpio-ftgpio010.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "clk_get_rate",
      "external": false,
      "loc": "include/linux/clk.h:837",
      "file": "drivers/pci/controller/pci-ftpci100.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "clk_get_rate",
      "external": false,
      "loc": "include/linux/clk.h:837",
      "file": "drivers/tty/serial/8250/8250_of.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "clk_get_rate",
      "external": false,
      "loc": "include/linux/clk.h:837",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "clk_get_rate",
      "external": false,
      "loc": "include/linux/clk.h:837",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "clk_get_rate",
      "external": false,
      "loc": "include/linux/clk.h:837",
      "file": "drivers/mfd/twl-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "clk_get_rate",
      "external": false,
      "loc": "include/linux/clk.h:837",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "clk_get_rate",
      "external": false,
      "loc": "include/linux/clk.h:837",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "clk_get_rate",
      "external": false,
      "loc": "include/linux/clk.h:837",
      "file": "drivers/cpufreq/cpufreq.c",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
long unsigned int clk_get_rate(struct clk * clk)
```

```json
{
  "name": "clk_get_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275896766,
      "name": "clk_get_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:1625",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config",
        "drivers/pwm/pwm-sifive.c:pwm_sifive_apply",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sifive.c:sifive_serial_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/spi/spi-sifive.c:sifive_spi_transfer_one",
        "drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_get_clk_rate_khz",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/clocksource/timer-of.c:timer_of_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275896766,
      "name": "clk_get_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
long unsigned int clk_get_rate(struct clk * clk)
```

```json
{
  "name": "clk_get_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585224368,
      "name": "clk_get_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:1625",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585224368,
      "name": "clk_get_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
long unsigned int clk_get_rate(struct clk * clk)
```

```json
{
  "name": "clk_get_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585176544,
      "name": "clk_get_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:1625",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585176544,
      "name": "clk_get_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
long unsigned int clk_get_rate(struct clk * clk)
```

```json
{
  "name": "clk_get_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585412240,
      "name": "clk_get_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:1625",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_get_clk_rate_khz",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585412240,
      "name": "clk_get_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
long unsigned int clk_get_rate(struct clk * clk)
```

```json
{
  "name": "clk_get_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585519824,
      "name": "clk_get_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:1625",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_get_clk_rate_khz",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585519824,
      "name": "clk_get_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int clk_get_rate(struct clk * clk)
```
</details>
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
