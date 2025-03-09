# Function: <code>of_iomap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "of_iomap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_iomap",
      "external": false,
      "loc": "include/linux/of_address.h:127",
      "file": "drivers/mfd/syscon.c",
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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "of_iomap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_iomap",
      "external": false,
      "loc": "include/linux/of_address.h:138",
      "file": "drivers/mfd/syscon.c",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "of_iomap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_iomap",
      "external": false,
      "loc": "include/linux/of_address.h:138",
      "file": "drivers/mfd/syscon.c",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "of_iomap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_iomap",
      "external": false,
      "loc": "include/linux/of_address.h:138",
      "file": "drivers/mfd/syscon.c",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "of_iomap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_iomap",
      "external": false,
      "loc": "include/linux/of_address.h:171",
      "file": "drivers/mfd/syscon.c",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "of_iomap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_iomap",
      "external": false,
      "loc": "include/linux/of_address.h:171",
      "file": "drivers/mfd/syscon.c",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void * of_iomap(struct device_node * np, int index)
```

```json
{
  "name": "of_iomap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501640352,
      "name": "of_iomap",
      "external": true,
      "loc": "drivers/of/address.c:855",
      "file": "drivers/of/address.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-al-fic.c:al_fic_init_dt",
        "drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_l1_intc_of_init",
        "drivers/irqchip/irq-gic.c:gic_of_setup",
        "drivers/irqchip/irq-gic.c:gic_of_setup",
        "drivers/irqchip/irq-gic-v3.c:gic_of_init",
        "drivers/irqchip/irq-gic-v3.c:gic_of_init",
        "drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_of_init",
        "drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_of_init",
        "drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init",
        "drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_of_init",
        "drivers/irqchip/qcom-pdc.c:qcom_pdc_init",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe",
        "drivers/gpio/gpiolib-of.c:of_mm_gpiochip_add_data",
        "drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe",
        "drivers/clk/clk-fixed-mmio.c:fixed_mmio_clk_setup",
        "drivers/clk/clk-hsdk-pll.c:of_hsdk_pll_clk_setup",
        "drivers/clk/clk-hsdk-pll.c:of_hsdk_pll_clk_setup",
        "drivers/clk/clk-qoriq.c:clockgen_init",
        "drivers/clk/clk-qoriq.c:clockgen_init",
        "drivers/clk/clk-xgene.c:xgene_devclk_init",
        "drivers/clk/clk-xgene.c:xgene_pmdclk_init",
        "drivers/clk/clk-xgene.c:xgene_pllclk_init",
        "drivers/clk/bcm/clk-iproc-armpll.c:iproc_armpll_setup",
        "drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_clk_setup",
        "drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_clk_setup",
        "drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_clk_setup",
        "drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_clk_setup",
        "drivers/clk/bcm/clk-iproc-asiu.c:iproc_asiu_setup",
        "drivers/clk/bcm/clk-iproc-asiu.c:iproc_asiu_setup",
        "drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe",
        "drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe",
        "drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe",
        "drivers/clk/mediatek/clk-pll.c:mtk_clk_register_plls",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_apmixedsys_init",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_pericfg_init",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt8516.c:mtk_apmixedsys_init",
        "drivers/clk/mediatek/clk-mt8516.c:mtk_infracfg_init",
        "drivers/clk/mediatek/clk-mt8516.c:mtk_topckgen_init",
        "drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_common_init",
        "drivers/clk/renesas/clk-div6.c:cpg_div6_clock_init",
        "drivers/clk/rockchip/clk-px30.c:px30_pmu_clk_init",
        "drivers/clk/rockchip/clk-px30.c:px30_clk_init",
        "drivers/clk/rockchip/clk-rv1108.c:rv1108_clk_init",
        "drivers/clk/rockchip/clk-rk3036.c:rk3036_clk_init",
        "drivers/clk/rockchip/clk-rk3128.c:rk3128_common_clk_init",
        "drivers/clk/rockchip/clk-rk3188.c:rk3188_common_clk_init",
        "drivers/clk/rockchip/clk-rk3228.c:rk3228_clk_init",
        "drivers/clk/rockchip/clk-rk3288.c:rk3288_clk_init",
        "drivers/clk/rockchip/clk-rk3308.c:rk3308_clk_init",
        "drivers/clk/rockchip/clk-rk3328.c:rk3328_clk_init",
        "drivers/clk/rockchip/clk-rk3368.c:rk3368_clk_init",
        "drivers/clk/rockchip/clk-rk3399.c:rk3399_pmu_clk_init",
        "drivers/clk/rockchip/clk-rk3399.c:rk3399_clk_init",
        "drivers/clk/sunxi/clk-sunxi.c:sunxi_divs_clk_setup",
        "drivers/clk/sunxi/clk-sunxi.c:sunxi_divider_clk_setup",
        "drivers/clk/sunxi/clk-sunxi.c:sunxi_factors_clk_setup",
        "drivers/clk/sunxi/clk-a10-hosc.c:sun4i_osc_clk_setup",
        "drivers/clk/sunxi/clk-a20-gmac.c:sun7i_a20_gmac_clk_setup",
        "drivers/clk/sunxi/clk-mod0.c:sun5i_a13_mbus_setup",
        "drivers/clk/sunxi/clk-mod0.c:sun4i_a10_mod0_of_clk_init_driver",
        "drivers/clk/versatile/clk-sp810.c:clk_sp810_of_setup",
        "drivers/soc/bcm/brcmstb/common.c:brcmstb_soc_device_early_init",
        "drivers/soc/bcm/brcmstb/biuctrl.c:brcmstb_biuctrl_init",
        "drivers/soc/imx/soc-imx8.c:imx8mm_soc_revision",
        "drivers/soc/imx/soc-imx8.c:imx8mm_soc_revision",
        "drivers/soc/imx/soc-imx8.c:imx8mq_soc_revision",
        "drivers/soc/renesas/renesas-soc.c:renesas_soc_init",
        "drivers/soc/renesas/renesas-soc.c:renesas_soc_init",
        "drivers/soc/renesas/rcar-rst.c:rcar_rst_read_mode_pins",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_init",
        "drivers/mfd/vexpress-sysreg.c:vexpress_flags_set",
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_probe",
        "drivers/edac/altera_edac.c:altr_init_a10_ecc_block",
        "drivers/clocksource/timer-of.c:timer_of_init",
        "drivers/clocksource/timer-rockchip.c:rk_timer_probe",
        "drivers/clocksource/timer-sp804.c:integrator_cp_of_init",
        "drivers/clocksource/timer-sp804.c:sp804_of_init",
        "drivers/clocksource/timer-versatile.c:versatile_sched_clock_init",
        "drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501640352,
      "name": "of_iomap",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void * of_iomap(struct device_node * np, int index)
```

```json
{
  "name": "of_iomap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234161868,
      "name": "of_iomap",
      "external": true,
      "loc": "drivers/of/address.c:855",
      "file": "drivers/of/address.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/smp_twd.c:twd_local_timer_of_register",
        "arch/arm/mm/cache-feroceon-l2.c:feroceon_of_init",
        "arch/arm/mm/cache-uniphier.c:__uniphier_cache_init",
        "arch/arm/mm/cache-uniphier.c:__uniphier_cache_init",
        "arch/arm/mm/cache-uniphier.c:__uniphier_cache_init",
        "arch/arm/mach-actions/platsmp.c:s500_smp_prepare_cpus",
        "arch/arm/mach-actions/platsmp.c:s500_smp_prepare_cpus",
        "arch/arm/mach-actions/platsmp.c:s500_smp_prepare_cpus",
        "arch/arm/mach-alpine/alpine_cpu_pm.c:alpine_cpu_pm_init",
        "arch/arm/mach-aspeed/platsmp.c:aspeed_g6_smp_prepare_cpus",
        "arch/arm/mach-aspeed/platsmp.c:aspeed_g6_boot_secondary",
        "arch/arm/mach-berlin/platsmp.c:berlin_smp_prepare_cpus",
        "arch/arm/mach-berlin/platsmp.c:berlin_smp_prepare_cpus",
        "arch/arm/mach-exynos/exynos.c:exynos_init_irq",
        "arch/arm/mach-exynos/exynos.c:exynos_sysram_init",
        "arch/arm/mach-exynos/exynos.c:exynos_sysram_init",
        "arch/arm/mach-exynos/suspend.c:exynos_pmu_irq_init",
        "arch/arm/mach-exynos/platsmp.c:exynos_scu_enable",
        "arch/arm/mach-exynos/mcpm-exynos.c:exynos_mcpm_init",
        "arch/arm/mach-highbank/highbank.c:highbank_init",
        "arch/arm/mach-hisi/platmcpm.c:hip04_smp_init",
        "arch/arm/mach-hisi/platmcpm.c:hip04_smp_init",
        "arch/arm/mach-hisi/platsmp.c:hip01_boot_secondary",
        "arch/arm/mach-hisi/platsmp.c:hi3xxx_smp_prepare_cpus",
        "arch/arm/mach-hisi/hotplug.c:hip01_set_cpu",
        "arch/arm/mach-hisi/hotplug.c:hi3xxx_set_cpu",
        "arch/arm/mach-meson/platsmp.c:meson_smp_prepare_cpus",
        "arch/arm/mach-meson/platsmp.c:meson_smp_prepare_cpus",
        "arch/arm/mach-mvebu/system-controller.c:mvebu_system_controller_init",
        "arch/arm/mach-mvebu/mvebu-soc-id.c:mvebu_soc_id_init",
        "arch/arm/mach-mvebu/board-v7.c:mvebu_init_irq",
        "arch/arm/mach-mvebu/coherency.c:coherency_init",
        "arch/arm/mach-mvebu/coherency.c:coherency_init",
        "arch/arm/mach-mvebu/coherency.c:coherency_init",
        "arch/arm/mach-mvebu/coherency.c:coherency_init",
        "arch/arm/mach-mvebu/pm-board.c:mvebu_armada_pm_init",
        "arch/arm/mach-imx/cpu.c:imx_aips_allow_unprivileged_access",
        "arch/arm/mach-imx/system.c:imx_init_l2cache",
        "arch/arm/mach-imx/cpu-imx5.c:imx5_pmu_init",
        "arch/arm/mach-imx/cpu-imx5.c:imx5_read_srev_reg",
        "arch/arm/mach-imx/tzic.c:tzic_init_dt",
        "arch/arm/mach-imx/anatop.c:imx_init_revision_from_anatop",
        "arch/arm/mach-imx/anatop.c:imx_init_revision_from_anatop",
        "arch/arm/mach-imx/gpc.c:imx_gpc_check_dt",
        "arch/arm/mach-imx/gpc.c:imx_gpc_init",
        "arch/arm/mach-imx/mmdc.c:imx_mmdc_probe",
        "arch/arm/mach-imx/src.c:imx_src_init",
        "arch/arm/mach-imx/platsmp.c:ls1021a_smp_prepare_cpus",
        "arch/arm/mach-imx/pm-imx7ulp.c:imx7ulp_pm_init",
        "arch/arm/mach-imx/pm-imx6.c:imx6_pm_ccm_init",
        "arch/arm/mach-imx/mach-imx51.c:imx51_dt_init",
        "arch/arm/mach-npcm/platsmp.c:npcm7xx_smp_prepare_cpus",
        "arch/arm/mach-npcm/platsmp.c:npcm7xx_smp_boot_secondary",
        "arch/arm/mach-omap2/control.c:omap2_control_base_init",
        "arch/arm/mach-omap2/timer.c:omap_dm_timer_init_one",
        "arch/arm/mach-omap2/omap4-common.c:omap_gic_of_init",
        "arch/arm/mach-omap2/omap4-common.c:omap_gic_of_init",
        "arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_init",
        "arch/arm/mach-qcom/platsmp.c:kpssv2_release_secondary",
        "arch/arm/mach-qcom/platsmp.c:kpssv2_release_secondary",
        "arch/arm/mach-qcom/platsmp.c:kpssv1_release_secondary",
        "arch/arm/mach-qcom/platsmp.c:kpssv1_release_secondary",
        "arch/arm/mach-rockchip/pm.c:rk3288_suspend_init",
        "arch/arm/mach-rockchip/platsmp.c:rockchip_smp_prepare_cpus",
        "arch/arm/mach-rockchip/platsmp.c:rockchip_smp_prepare_cpus",
        "arch/arm/mach-rockchip/platsmp.c:rockchip_smp_prepare_cpus",
        "arch/arm/mach-tegra/irq.c:tegra_init_irq",
        "arch/arm/mach-vexpress/dcscb.c:dcscb_init",
        "arch/arm/mach-vexpress/tc2_pm.c:tc2_pm_init",
        "arch/arm/mach-vexpress/platsmp.c:vexpress_smp_dt_prepare_cpus",
        "drivers/irqchip/irq-al-fic.c:al_fic_init_dt",
        "drivers/irqchip/exynos-combiner.c:combiner_of_init",
        "drivers/irqchip/irq-hip04.c:hip04_of_init",
        "drivers/irqchip/irq-hip04.c:hip04_of_init",
        "drivers/irqchip/irq-tegra.c:tegra_ictlr_init",
        "drivers/irqchip/irq-omap-intc.c:intc_of_init",
        "drivers/irqchip/irq-gic.c:gic_of_setup",
        "drivers/irqchip/irq-gic.c:gic_of_setup",
        "drivers/irqchip/irq-gic-v3.c:gic_of_init",
        "drivers/irqchip/irq-gic-v3.c:gic_of_init",
        "drivers/irqchip/irq-crossbar.c:crossbar_of_init",
        "drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_of_init",
        "drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_of_init",
        "drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init",
        "drivers/irqchip/irq-aspeed-vic.c:avic_of_init",
        "drivers/irqchip/irq-aspeed-i2c-ic.c:aspeed_i2c_ic_of_init",
        "drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_of_init",
        "drivers/irqchip/qcom-pdc.c:qcom_pdc_init",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe",
        "drivers/gpio/gpiolib-of.c:of_mm_gpiochip_add_data",
        "drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe",
        "drivers/clk/clk-fixed-mmio.c:fixed_mmio_clk_setup",
        "drivers/clk/clk-aspeed.c:aspeed_cc_g5_of_clk_init_driver",
        "drivers/clk/clk-ast2600.c:aspeed_cc_g6_of_clk_init_driver",
        "drivers/clk/clk-highbank.c:hb_clk_init",
        "drivers/clk/clk-hsdk-pll.c:of_hsdk_pll_clk_setup",
        "drivers/clk/clk-hsdk-pll.c:of_hsdk_pll_clk_setup",
        "drivers/clk/clk-milbeaut.c:m10v_cc_of_clk_init_driver",
        "drivers/clk/clk-qoriq.c:clockgen_init",
        "drivers/clk/clk-qoriq.c:clockgen_init",
        "drivers/clk/berlin/bg2.c:berlin2_clock_setup",
        "drivers/clk/berlin/bg2q.c:berlin2q_clock_setup",
        "drivers/clk/berlin/bg2q.c:berlin2q_clock_setup",
        "drivers/clk/hisilicon/clk-hi3620.c:hi3620_mmc_clk_init",
        "drivers/clk/imx/clk-imx5.c:mx53_clocks_init",
        "drivers/clk/imx/clk-imx5.c:mx51_clocks_init",
        "drivers/clk/imx/clk-imx5.c:mx50_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6sl.c:imx6sl_clocks_init",
        "drivers/clk/imx/clk-imx6sl.c:imx6sl_clocks_init",
        "drivers/clk/imx/clk-imx6sll.c:imx6sll_clocks_init",
        "drivers/clk/imx/clk-imx6sll.c:imx6sll_clocks_init",
        "drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init",
        "drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init",
        "drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init",
        "drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init",
        "drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init",
        "drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init",
        "drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_smc1_init",
        "drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_pcc3_init",
        "drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_pcc2_init",
        "drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_scg1_init",
        "drivers/clk/imx/clk-vf610.c:vf610_clocks_init",
        "drivers/clk/imx/clk-vf610.c:vf610_clocks_init",
        "drivers/clk/mediatek/clk-pll.c:mtk_clk_register_plls",
        "drivers/clk/mediatek/clk-mt8135.c:mtk_pericfg_init",
        "drivers/clk/mediatek/clk-mt8135.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_apmixedsys_init",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_pericfg_init",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt8516.c:mtk_apmixedsys_init",
        "drivers/clk/mediatek/clk-mt8516.c:mtk_infracfg_init",
        "drivers/clk/mediatek/clk-mt8516.c:mtk_topckgen_init",
        "drivers/clk/meson/meson8b.c:meson8b_clkc_init_common",
        "drivers/clk/mvebu/common.c:kirkwood_fix_sscg_deviation",
        "drivers/clk/mvebu/common.c:mvebu_clk_gating_setup",
        "drivers/clk/mvebu/common.c:mvebu_coreclk_setup",
        "drivers/clk/mvebu/clk-cpu.c:of_cpu_clk_setup",
        "drivers/clk/mvebu/clk-cpu.c:of_cpu_clk_setup",
        "drivers/clk/mvebu/clk-corediv.c:mvebu_corediv_clk_init",
        "drivers/clk/mvebu/dove-divider.c:dove_divider_clk_init",
        "drivers/clk/renesas/clk-emev2.c:emev2_smu_init",
        "drivers/clk/renesas/clk-rz.c:rz_cpg_clocks_init",
        "drivers/clk/renesas/clk-r8a7740.c:r8a7740_cpg_clocks_init",
        "drivers/clk/renesas/clk-r8a7778.c:r8a7778_cpg_clocks_init",
        "drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe",
        "drivers/clk/renesas/clk-sh73a0.c:sh73a0_cpg_clocks_init",
        "drivers/clk/renesas/clk-rcar-gen2.c:rcar_gen2_cpg_clocks_init",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_common_init",
        "drivers/clk/renesas/clk-mstp.c:cpg_mstp_clocks_init",
        "drivers/clk/renesas/clk-mstp.c:cpg_mstp_clocks_init",
        "drivers/clk/renesas/clk-div6.c:cpg_div6_clock_init",
        "drivers/clk/rockchip/clk-px30.c:px30_pmu_clk_init",
        "drivers/clk/rockchip/clk-px30.c:px30_clk_init",
        "drivers/clk/rockchip/clk-rv1108.c:rv1108_clk_init",
        "drivers/clk/rockchip/clk-rk3036.c:rk3036_clk_init",
        "drivers/clk/rockchip/clk-rk3128.c:rk3128_common_clk_init",
        "drivers/clk/rockchip/clk-rk3188.c:rk3188_common_clk_init",
        "drivers/clk/rockchip/clk-rk3228.c:rk3228_clk_init",
        "drivers/clk/rockchip/clk-rk3288.c:rk3288_clk_init",
        "drivers/clk/rockchip/clk-rk3308.c:rk3308_clk_init",
        "drivers/clk/rockchip/clk-rk3328.c:rk3328_clk_init",
        "drivers/clk/rockchip/clk-rk3368.c:rk3368_clk_init",
        "drivers/clk/rockchip/clk-rk3399.c:rk3399_pmu_clk_init",
        "drivers/clk/rockchip/clk-rk3399.c:rk3399_clk_init",
        "drivers/clk/samsung/clk.c:samsung_cmu_register_one",
        "drivers/clk/samsung/clk-exynos5250.c:exynos5250_clk_of_clk_init_driver",
        "drivers/clk/samsung/clk-exynos5420.c:exynos5x_clk_init",
        "drivers/clk/samsung/clk-exynos-clkout.c:exynos_clkout_init",
        "drivers/clk/tegra/clk-tegra20.c:tegra20_clock_init",
        "drivers/clk/tegra/clk-tegra20.c:tegra20_clock_init",
        "drivers/clk/tegra/clk-tegra30.c:tegra30_clock_init",
        "drivers/clk/tegra/clk-tegra30.c:tegra30_clock_init",
        "drivers/clk/tegra/clk-tegra114.c:tegra114_clock_init",
        "drivers/clk/tegra/clk-tegra114.c:tegra114_clock_init",
        "drivers/clk/tegra/clk-tegra124.c:tegra124_132_clock_init_pre",
        "drivers/clk/tegra/clk-tegra124.c:tegra124_132_clock_init_pre",
        "drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup",
        "drivers/clk/ti/fapll.c:ti_fapll_setup",
        "drivers/clk/ti/clk-dra7-atl.c:of_dra7_atl_clk_probe",
        "drivers/clk/versatile/clk-versatile.c:cm_osc_setup",
        "drivers/clk/versatile/clk-sp810.c:clk_sp810_of_setup",
        "drivers/soc/dove/pmu.c:dove_init_pmu",
        "drivers/soc/dove/pmu.c:dove_init_pmu",
        "drivers/soc/imx/soc-imx8.c:imx8mm_soc_revision",
        "drivers/soc/imx/soc-imx8.c:imx8mm_soc_revision",
        "drivers/soc/imx/soc-imx8.c:imx8mq_soc_revision",
        "drivers/soc/renesas/renesas-soc.c:renesas_soc_init",
        "drivers/soc/renesas/renesas-soc.c:renesas_soc_init",
        "drivers/soc/renesas/rcar-rst.c:rcar_rst_read_mode_pins",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_init",
        "drivers/soc/renesas/rmobile-sysc.c:rmobile_init_pm_domains",
        "drivers/soc/samsung/pm_domains.c:exynos4_pm_init_power_domain",
        "drivers/soc/tegra/fuse/fuse-tegra.c:tegra_init_fuse",
        "drivers/mfd/vexpress-sysreg.c:vexpress_flags_set",
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_probe",
        "drivers/clocksource/timer-of.c:timer_of_init",
        "drivers/clocksource/renesas-ostm.c:ostm_init",
        "drivers/clocksource/dw_apb_timer_of.c:timer_get_base_and_rate",
        "drivers/clocksource/timer-rockchip.c:rk_timer_probe",
        "drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_common_init",
        "drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_common_init",
        "drivers/clocksource/timer-orion.c:orion_timer_init",
        "drivers/clocksource/exynos_mct.c:mct_init_dt",
        "drivers/clocksource/timer-qcom.c:msm_dt_timer_init",
        "drivers/clocksource/timer-ti-32k.c:ti_32k_timer_init",
        "drivers/clocksource/arm_global_timer.c:global_timer_of_register",
        "drivers/clocksource/timer-sp804.c:integrator_cp_of_init",
        "drivers/clocksource/timer-sp804.c:sp804_of_init",
        "drivers/clocksource/timer-versatile.c:versatile_sched_clock_init",
        "drivers/clocksource/timer-imx-gpt.c:mxc_timer_init_dt",
        "drivers/memory/samsung/exynos-srom.c:exynos_srom_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234161868,
      "name": "of_iomap",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * of_iomap(struct device_node * np, int index)
```

```json
{
  "name": "of_iomap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295076048,
      "name": "of_iomap",
      "external": true,
      "loc": "drivers/of/address.c:855",
      "file": "drivers/of/address.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/sysdev/fsl_lbc.c:fsl_lbc_ctrl_probe",
        "arch/powerpc/platforms/powernv/rng.c:__machine_initcall_powernv_rng_init",
        "drivers/irqchip/irq-al-fic.c:al_fic_init_dt",
        "drivers/gpio/gpiolib-of.c:of_mm_gpiochip_add_data",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_ppc_of_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295076048,
      "name": "of_iomap",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void * of_iomap(struct device_node * np, int index)
```

```json
{
  "name": "of_iomap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278099878,
      "name": "of_iomap",
      "external": true,
      "loc": "drivers/of/address.c:855",
      "file": "drivers/of/address.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-al-fic.c:al_fic_init_dt",
        "drivers/irqchip/irq-sifive-plic.c:plic_init",
        "drivers/gpio/gpiolib-of.c:of_mm_gpiochip_add_data",
        "drivers/clk/clk-fixed-mmio.c:fixed_mmio_clk_setup",
        "drivers/clk/clk-hsdk-pll.c:of_hsdk_pll_clk_setup",
        "drivers/clk/clk-hsdk-pll.c:of_hsdk_pll_clk_setup",
        "drivers/clocksource/timer-of.c:timer_of_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278099878,
      "name": "of_iomap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void * of_iomap(struct device_node * np, int index)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void * of_iomap(struct device_node * np, int index)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void * of_iomap(struct device_node * np, int index)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void * of_iomap(struct device_node * np, int index)
```
</details>
</li>
</ul>
