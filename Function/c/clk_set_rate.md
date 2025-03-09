# Function: <code>clk_set_rate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int clk_set_rate(struct clk * clk, long unsigned int rate)
```

```json
{
  "name": "clk_set_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586086480,
      "name": "clk_set_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:1554",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/phy/phy-generic.c:usb_phy_gen_create_phy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586086480,
      "name": "clk_set_rate",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int clk_set_rate(struct clk * clk, long unsigned int rate)
```

```json
{
  "name": "clk_set_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586497520,
      "name": "clk_set_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:1620",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586497520,
      "name": "clk_set_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int clk_set_rate(struct clk * clk, long unsigned int rate)
```

```json
{
  "name": "clk_set_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584304208,
      "name": "clk_set_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:1620",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584304208,
      "name": "clk_set_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int clk_set_rate(struct clk * clk, long unsigned int rate)
```

```json
{
  "name": "clk_set_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584382608,
      "name": "clk_set_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:1622",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584382608,
      "name": "clk_set_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int clk_set_rate(struct clk * clk, long unsigned int rate)
```

```json
{
  "name": "clk_set_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584784896,
      "name": "clk_set_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:1733",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584784896,
      "name": "clk_set_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int clk_set_rate(struct clk * clk, long unsigned int rate)
```

```json
{
  "name": "clk_set_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585016000,
      "name": "clk_set_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:1943",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585016000,
      "name": "clk_set_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int clk_set_rate(struct clk * clk, long unsigned int rate)
```

```json
{
  "name": "clk_set_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585124176,
      "name": "clk_set_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:2056",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585124176,
      "name": "clk_set_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int clk_set_rate(struct clk * clk, long unsigned int rate)
```

```json
{
  "name": "clk_set_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585334208,
      "name": "clk_set_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:2192",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585334208,
      "name": "clk_set_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int clk_set_rate(struct clk * clk, long unsigned int rate)
```

```json
{
  "name": "clk_set_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585470320,
      "name": "clk_set_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:2200",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585470320,
      "name": "clk_set_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int clk_set_rate(struct clk * clk, long unsigned int rate)
```

```json
{
  "name": "clk_set_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586192992,
      "name": "clk_set_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:2221",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:_generic_set_opp_regulator",
        "drivers/opp/core.c:_generic_set_opp_regulator",
        "drivers/opp/core.c:_generic_set_opp_regulator"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586192992,
      "name": "clk_set_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
int clk_set_rate(struct clk * clk, long unsigned int rate)
```

```json
{
  "name": "clk_set_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586312608,
      "name": "clk_set_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:2230",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:_generic_set_opp_regulator",
        "drivers/opp/core.c:_generic_set_opp_regulator",
        "drivers/opp/core.c:_generic_set_opp_regulator"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586312608,
      "name": "clk_set_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
int clk_set_rate(struct clk * clk, long unsigned int rate)
```

```json
{
  "name": "clk_set_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586185696,
      "name": "clk_set_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:2243",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586185696,
      "name": "clk_set_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
int clk_set_rate(struct clk * clk, long unsigned int rate)
```

```json
{
  "name": "clk_set_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586687888,
      "name": "clk_set_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:2243",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586687888,
      "name": "clk_set_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
int clk_set_rate(struct clk * clk, long unsigned int rate)
```

```json
{
  "name": "clk_set_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587959488,
      "name": "clk_set_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:2257",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587959488,
      "name": "clk_set_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
int clk_set_rate(struct clk * clk, long unsigned int rate)
```

```json
{
  "name": "clk_set_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589321616,
      "name": "clk_set_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:2441",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_config_clks_simple",
        "drivers/opp/core.c:dev_pm_opp_config_clks_simple",
        "drivers/opp/core.c:_opp_config_clk_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589321616,
      "name": "clk_set_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
int clk_set_rate(struct clk * clk, long unsigned int rate)
```

```json
{
  "name": "clk_set_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589618432,
      "name": "clk_set_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:2486",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_config_clks_simple",
        "drivers/opp/core.c:dev_pm_opp_config_clks_simple",
        "drivers/opp/core.c:_opp_config_clk_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589618432,
      "name": "clk_set_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
int clk_set_rate(struct clk * clk, long unsigned int rate)
```

```json
{
  "name": "clk_set_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589928432,
      "name": "clk_set_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:2486",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_config_clks_simple",
        "drivers/opp/core.c:dev_pm_opp_config_clks_simple",
        "drivers/opp/core.c:_opp_config_clk_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589928432,
      "name": "clk_set_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
int clk_set_rate(struct clk * clk, long unsigned int rate)
```

```json
{
  "name": "clk_set_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497767144,
      "name": "clk_set_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:2200",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl",
        "drivers/video/fbdev/amba-clcd.c:clcdfb_set_par",
        "drivers/clk/rockchip/clk-rk3188.c:rk3188a_clk_init",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_set_termios",
        "drivers/tty/serial/msm_serial.c:msm_set_termios",
        "drivers/tty/serial/owl-uart.c:owl_uart_set_termios",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/mmc/host/mmci.c:mmci_probe",
        "drivers/mmc/host/mmci.c:mmci_set_ios",
        "drivers/firmware/qcom_scm.c:qcom_scm_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497767144,
      "name": "clk_set_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int clk_set_rate(struct clk * clk, long unsigned int rate)
```

```json
{
  "name": "clk_set_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230584608,
      "name": "clk_set_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:2200",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-mvebu/platsmp.c:armada_xp_sync_secondary_clk",
        "arch/arm/mach-omap2/io.c:omap_sdrc_init",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/video/fbdev/amba-clcd.c:clcdfb_set_par",
        "drivers/clk/imx/clk-imx5.c:mx53_clocks_init",
        "drivers/clk/imx/clk-imx5.c:mx53_clocks_init",
        "drivers/clk/imx/clk-imx5.c:mx53_clocks_init",
        "drivers/clk/imx/clk-imx5.c:mx51_clocks_init",
        "drivers/clk/imx/clk-imx5.c:mx51_clocks_init",
        "drivers/clk/imx/clk-imx5.c:mx50_clocks_init",
        "drivers/clk/imx/clk-imx5.c:mx50_clocks_init",
        "drivers/clk/imx/clk-imx5.c:mx50_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6sl.c:imx6sl_clocks_init",
        "drivers/clk/imx/clk-imx6sll.c:imx6sll_clocks_init",
        "drivers/clk/imx/clk-imx6sll.c:imx6sll_clocks_init",
        "drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init",
        "drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init",
        "drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init",
        "drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init",
        "drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init",
        "drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init",
        "drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init",
        "drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init",
        "drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init",
        "drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init",
        "drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init",
        "drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init",
        "drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init",
        "drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init",
        "drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init",
        "drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init",
        "drivers/clk/imx/clk-vf610.c:vf610_clocks_init",
        "drivers/clk/imx/clk-vf610.c:vf610_clocks_init",
        "drivers/clk/imx/clk-vf610.c:vf610_clocks_init",
        "drivers/clk/imx/clk-vf610.c:vf610_clocks_init",
        "drivers/clk/imx/clk-vf610.c:vf610_clocks_init",
        "drivers/clk/imx/clk-vf610.c:vf610_clocks_init",
        "drivers/clk/rockchip/clk-rk3188.c:rk3188a_clk_init",
        "drivers/clk/tegra/clk.c:tegra_init_from_table",
        "drivers/clk/tegra/clk-emc.c:emc_set_timing",
        "drivers/clk/ti/clk-3xxx.c:omap3_clk_lock_dpll5",
        "drivers/clk/ti/clk-3xxx.c:omap3_clk_lock_dpll5",
        "drivers/clk/ti/clk-44xx.c:omap4xxx_dt_clk_init",
        "drivers/clk/ti/clk-44xx.c:omap4xxx_dt_clk_init",
        "drivers/clk/ti/clk-7xx.c:dra7xx_dt_clk_init",
        "drivers/clk/ti/clk-7xx.c:dra7xx_dt_clk_init",
        "drivers/clk/ti/clk-7xx.c:dra7xx_dt_clk_init",
        "drivers/tty/serial/msm_serial.c:msm_set_termios",
        "drivers/tty/serial/owl-uart.c:owl_uart_set_termios",
        "drivers/tty/serial/rda-uart.c:rda_uart_set_termios",
        "drivers/usb/phy/phy-generic.c:usb_phy_gen_create_phy",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/ti-opp-supply.c:ti_opp_supply_set_opp",
        "drivers/opp/ti-opp-supply.c:ti_opp_supply_set_opp",
        "drivers/cpufreq/omap-cpufreq.c:omap_target",
        "drivers/cpufreq/omap-cpufreq.c:omap_target",
        "drivers/cpufreq/tegra20-cpufreq.c:tegra_target",
        "drivers/cpufreq/tegra124-cpufreq.c:tegra124_cpufreq_probe",
        "drivers/mmc/host/mmci.c:mmci_probe",
        "drivers/mmc/host/mmci.c:mmci_set_ios",
        "drivers/firmware/qcom_scm.c:qcom_scm_probe",
        "drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe",
        "drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe",
        "drivers/memory/tegra/tegra124-emc.c:emc_debug_rate_set",
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_set_bclk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230584608,
      "name": "clk_set_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
  "name": "clk_set_rate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_set_rate",
      "external": false,
      "loc": "include/linux/clk.h:842",
      "file": "drivers/pci/controller/pci-ftpci100.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "clk_set_rate",
      "external": false,
      "loc": "include/linux/clk.h:842",
      "file": "drivers/opp/core.c",
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
int clk_set_rate(struct clk * clk, long unsigned int rate)
```

```json
{
  "name": "clk_set_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275906156,
      "name": "clk_set_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:2200",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275906156,
      "name": "clk_set_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int clk_set_rate(struct clk * clk, long unsigned int rate)
```

```json
{
  "name": "clk_set_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585232848,
      "name": "clk_set_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:2200",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585232848,
      "name": "clk_set_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int clk_set_rate(struct clk * clk, long unsigned int rate)
```

```json
{
  "name": "clk_set_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585185024,
      "name": "clk_set_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:2200",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585185024,
      "name": "clk_set_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int clk_set_rate(struct clk * clk, long unsigned int rate)
```

```json
{
  "name": "clk_set_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585420720,
      "name": "clk_set_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:2200",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585420720,
      "name": "clk_set_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int clk_set_rate(struct clk * clk, long unsigned int rate)
```

```json
{
  "name": "clk_set_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585528640,
      "name": "clk_set_rate",
      "external": true,
      "loc": "drivers/clk/clk.c:2200",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585528640,
      "name": "clk_set_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int clk_set_rate(struct clk * clk, long unsigned int rate)
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
