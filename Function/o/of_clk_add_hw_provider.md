# Function: <code>of_clk_add_hw_provider</code>

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
int of_clk_add_hw_provider(struct device_node * np, struct clk_hw * (*)(struct of_phandle_args *, void *) get, void * data)
```

```json
{
  "name": "of_clk_add_hw_provider",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497765128,
      "name": "of_clk_add_hw_provider",
      "external": true,
      "loc": "drivers/clk/clk.c:4322",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_of_clk_add_hw_provider",
        "drivers/clk/clk-fixed-factor.c:_of_fixed_factor_clk_setup",
        "drivers/clk/clk-fixed-mmio.c:fixed_mmio_clk_setup",
        "drivers/clk/clk-hsdk-pll.c:of_hsdk_pll_clk_setup",
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_clk_probe",
        "drivers/clk/bcm/clk-iproc-armpll.c:iproc_armpll_setup",
        "drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_clk_setup",
        "drivers/clk/bcm/clk-iproc-asiu.c:iproc_asiu_setup",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_clk_probe",
        "drivers/clk/bcm/clk-bcm2835-aux.c:bcm2835_aux_clk_probe",
        "drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe",
        "drivers/clk/imx/clk-imx8qxp-lpcg.c:imx8qxp_lpcg_clk_probe",
        "drivers/clk/mvebu/armada-37xx-xtal.c:armada_3700_xtal_clock_probe",
        "drivers/clk/mvebu/armada-37xx-tbg.c:armada_3700_tbg_clock_probe",
        "drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_probe",
        "drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_probe",
        "drivers/clk/mvebu/cp110-system-controller.c:cp110_syscon_common_probe",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe",
        "drivers/clk/sunxi-ng/ccu_common.c:sunxi_ccu_probe",
        "drivers/clk/sunxi-ng/ccu_common.c:sunxi_ccu_probe",
        "drivers/clk/zynqmp/clkc.c:zynqmp_clock_probe",
        "drivers/rtc/rtc-sun6i.c:sun6i_rtc_clk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497765128,
      "name": "of_clk_add_hw_provider",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int of_clk_add_hw_provider(struct device_node * np, struct clk_hw * (*)(struct of_phandle_args *, void *) get, void * data)
```

```json
{
  "name": "of_clk_add_hw_provider",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230582520,
      "name": "of_clk_add_hw_provider",
      "external": true,
      "loc": "drivers/clk/clk.c:4322",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_of_clk_add_hw_provider",
        "drivers/clk/clk-fixed-factor.c:_of_fixed_factor_clk_setup",
        "drivers/clk/clk-fixed-mmio.c:fixed_mmio_clk_setup",
        "drivers/clk/clk-aspeed.c:aspeed_cc_g5_of_clk_init_driver",
        "drivers/clk/clk-ast2600.c:aspeed_cc_g6_of_clk_init_driver",
        "drivers/clk/clk-highbank.c:hb_clk_init",
        "drivers/clk/clk-hsdk-pll.c:of_hsdk_pll_clk_setup",
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_clk_probe",
        "drivers/clk/clk-milbeaut.c:m10v_cc_of_clk_init_driver",
        "drivers/clk/clk-npcm7xx.c:npcm7xx_clk_init",
        "drivers/clk/berlin/bg2.c:berlin2_clock_setup",
        "drivers/clk/berlin/bg2q.c:berlin2q_clock_setup",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6sl.c:imx6sl_clocks_init",
        "drivers/clk/imx/clk-imx6sll.c:imx6sll_clocks_init",
        "drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init",
        "drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init",
        "drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init",
        "drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_smc1_init",
        "drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_pcc3_init",
        "drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_pcc2_init",
        "drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_scg1_init",
        "drivers/clk/meson/meson8b.c:meson8b_clkc_init_common",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe",
        "drivers/clk/samsung/clk.c:samsung_clk_of_add_provider",
        "drivers/clk/samsung/clk-exynos-clkout.c:exynos_clkout_init",
        "drivers/clk/tegra/clk-bpmp.c:tegra_bpmp_init_clocks",
        "drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup",
        "drivers/clk/ti/clkctrl.c:_clkctrl_add_provider",
        "drivers/clk/uniphier/clk-uniphier-core.c:uniphier_clk_probe",
        "drivers/net/ethernet/ti/cpts.c:cpts_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230582520,
      "name": "of_clk_add_hw_provider",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int of_clk_add_hw_provider(struct device_node * np, struct clk_hw * (*)(struct of_phandle_args *, void *) get, void * data)
```

```json
{
  "name": "of_clk_add_hw_provider",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275904436,
      "name": "of_clk_add_hw_provider",
      "external": true,
      "loc": "drivers/clk/clk.c:4322",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_of_clk_add_hw_provider",
        "drivers/clk/clk-fixed-factor.c:_of_fixed_factor_clk_setup",
        "drivers/clk/clk-fixed-mmio.c:fixed_mmio_clk_setup",
        "drivers/clk/clk-hsdk-pll.c:of_hsdk_pll_clk_setup",
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_clk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275904436,
      "name": "of_clk_add_hw_provider",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int of_clk_add_hw_provider(struct device_node * np, struct clk_hw * (*)(struct of_phandle_args *, void *) get, void * data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int of_clk_add_hw_provider(struct device_node * np, struct clk_hw * (*)(struct of_phandle_args *, void *) get, void * data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int of_clk_add_hw_provider(struct device_node * np, struct clk_hw * (*)(struct of_phandle_args *, void *) get, void * data)
```
</details>
</li>
</ul>
