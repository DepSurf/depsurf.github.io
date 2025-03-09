# Function: <code>ti_clk_get_features</code>

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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
const struct ti_clk_features * ti_clk_get_features()
```

```json
{
  "name": "ti_clk_get_features",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230751908,
      "name": "ti_clk_get_features",
      "external": true,
      "loc": "drivers/clk/ti/clk.c:438",
      "file": "drivers/clk/ti/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/ti/clockdomain.c:omap2_clkops_disable_clkdm",
        "drivers/clk/ti/clockdomain.c:omap2_clkops_enable_clkdm",
        "drivers/clk/ti/clkt_dpll.c:omap2_dpll_round_rate",
        "drivers/clk/ti/clkt_dpll.c:omap2_dpll_round_rate",
        "drivers/clk/ti/clkt_dpll.c:omap2_dpll_round_rate",
        "drivers/clk/ti/clkt_dpll.c:omap2_dpll_round_rate",
        "drivers/clk/ti/clkt_dpll.c:omap2_dpll_round_rate",
        "drivers/clk/ti/clkt_dpll.c:omap2_dpll_round_rate",
        "drivers/clk/ti/clkt_dpll.c:omap2_get_dpll_rate",
        "drivers/clk/ti/clkt_dpll.c:omap2_init_dpll_parent",
        "drivers/clk/ti/clkt_dflt.c:omap2_dflt_clk_disable",
        "drivers/clk/ti/clkt_dflt.c:omap2_dflt_clk_enable",
        "drivers/clk/ti/clkt_dflt.c:omap2_clk_dflt_find_idlest",
        "drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup",
        "drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup",
        "drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup",
        "drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup",
        "drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup",
        "drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup",
        "drivers/clk/ti/clkctrl.c:_ti_clkctrl_clk_register",
        "drivers/clk/ti/clk-33xx.c:am33xx_dt_clk_init",
        "drivers/clk/ti/dpll3xxx.c:omap3_dpll4_set_rate_and_parent",
        "drivers/clk/ti/dpll3xxx.c:omap3_dpll4_set_rate",
        "drivers/clk/ti/dpll3xxx.c:omap3_noncore_dpll_set_rate",
        "drivers/clk/ti/dpll3xxx.c:omap3_noncore_dpll_program",
        "drivers/clk/ti/dpll3xxx.c:omap3_noncore_dpll_program",
        "drivers/clk/ti/clk-7xx.c:dra7xx_dt_clk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230751908,
      "name": "ti_clk_get_features",
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
const struct ti_clk_features * ti_clk_get_features()
```
</details>
</li>
</ul>
