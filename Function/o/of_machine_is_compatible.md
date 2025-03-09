# Function: <code>of_machine_is_compatible</code>

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
int of_machine_is_compatible(const char * compat)
```

```json
{
  "name": "of_machine_is_compatible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501604208,
      "name": "of_machine_is_compatible",
      "external": true,
      "loc": "drivers/of/base.c:593",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/edac/altera_edac.c:altr_edac_a10_probe",
        "drivers/edac/altera_edac.c:altr_init_a10_ecc_device_type",
        "drivers/edac/altera_edac.c:altr_init_a10_ecc_device_type",
        "drivers/edac/altera_edac.c:altr_init_a10_ecc_block",
        "drivers/edac/altera_edac.c:altr_sdram_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501604208,
      "name": "of_machine_is_compatible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int of_machine_is_compatible(const char * compat)
```

```json
{
  "name": "of_machine_is_compatible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234128916,
      "name": "of_machine_is_compatible",
      "external": true,
      "loc": "drivers/of/base.c:593",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-exynos/exynos.c:exynos_dt_machine_init",
        "arch/arm/mach-exynos/exynos.c:exynos_dt_machine_init",
        "arch/arm/mach-exynos/exynos.c:exynos_dt_machine_init",
        "arch/arm/mach-exynos/exynos.c:exynos_dt_machine_init",
        "arch/arm/mach-exynos/exynos.c:exynos_dt_machine_init",
        "arch/arm/mach-exynos/exynos.c:exynos_dt_machine_init",
        "arch/arm/mach-exynos/exynos.c:exynos_dt_machine_init",
        "arch/arm/mach-exynos/exynos.c:exynos_dt_machine_init",
        "arch/arm/mach-exynos/exynos.c:exynos_set_delayed_reset_assertion",
        "arch/arm/mach-mvebu/system-controller.c:mvebu_system_controller_set_cpu_boot_addr",
        "arch/arm/mach-mvebu/system-controller.c:mvebu_system_controller_get_soc_id",
        "arch/arm/mach-mvebu/board-v7.c:mvebu_dt_init",
        "arch/arm/mach-mvebu/pmsu.c:mvebu_v7_cpu_pm_init",
        "arch/arm/mach-mvebu/pmsu.c:mvebu_v7_cpu_pm_init",
        "arch/arm/mach-mvebu/pmsu.c:mvebu_v7_cpu_pm_init",
        "arch/arm/mach-mvebu/pmsu.c:mvebu_v7_cpu_pm_init",
        "arch/arm/mach-mvebu/pm.c:mvebu_pm_init",
        "arch/arm/mach-mvebu/pm.c:mvebu_pm_init",
        "arch/arm/mach-mvebu/pm.c:mvebu_pm_init",
        "arch/arm/mach-mvebu/pm.c:mvebu_pm_init",
        "arch/arm/mach-mvebu/pm-board.c:mvebu_armada_pm_init",
        "arch/arm/mach-mvebu/platsmp-a9.c:mvebu_cortex_a9_boot_secondary",
        "arch/arm/mach-mediatek/mediatek.c:mediatek_timer_init",
        "arch/arm/mach-mediatek/mediatek.c:mediatek_timer_init",
        "arch/arm/mach-mediatek/mediatek.c:mediatek_timer_init",
        "arch/arm/mach-mediatek/mediatek.c:mediatek_timer_init",
        "arch/arm/mach-milbeaut/platsmp.c:m10v_pm_init",
        "arch/arm/mach-omap2/omap_hwmod_7xx_data.c:dra7xx_hwmod_init",
        "arch/arm/mach-omap2/pdata-quirks.c:pdata_quirks_init",
        "arch/arm/mach-omap2/pdata-quirks.c:pdata_quirks_init",
        "arch/arm/mach-omap2/pdata-quirks.c:pdata_quirks_init",
        "arch/arm/mach-omap2/pdata-quirks.c:pdata_quirks_check",
        "arch/arm/mach-rockchip/rockchip.c:rockchip_timer_init",
        "arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_timer_init",
        "arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_timer_init",
        "arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_timer_init",
        "arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_timer_init",
        "arch/arm/mach-shmobile/regulator-quirk-rcar-gen2.c:rcar_gen2_regulator_quirk",
        "arch/arm/mach-shmobile/regulator-quirk-rcar-gen2.c:rcar_gen2_regulator_quirk",
        "arch/arm/mach-shmobile/regulator-quirk-rcar-gen2.c:rcar_gen2_regulator_quirk",
        "arch/arm/mach-shmobile/regulator-quirk-rcar-gen2.c:rcar_gen2_regulator_quirk",
        "arch/arm/mach-shmobile/regulator-quirk-rcar-gen2.c:rcar_gen2_regulator_quirk",
        "arch/arm/mach-tegra/tegra.c:tegra_dt_init_late",
        "arch/arm/mach-tegra/tegra.c:tegra_dt_init_late",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:of_assigned_ldb_sels",
        "drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init",
        "drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init",
        "drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init",
        "drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init",
        "drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init",
        "drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init",
        "drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init",
        "drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init",
        "drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init",
        "drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init",
        "drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init",
        "drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init",
        "drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init",
        "drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init",
        "drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init",
        "drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init",
        "drivers/clk/mvebu/mv98dx3236.c:mv98dx3236_get_clk_ratio",
        "drivers/clk/mvebu/mv98dx3236.c:mv98dx3236_get_clk_ratio",
        "drivers/clk/mvebu/mv98dx3236.c:mv98dx3236_get_clk_ratio",
        "drivers/clk/mvebu/mv98dx3236.c:mv98dx3236_get_clk_ratio",
        "drivers/clk/mvebu/mv98dx3236.c:mv98dx3236_get_cpu_freq",
        "drivers/clk/mvebu/mv98dx3236.c:mv98dx3236_get_cpu_freq",
        "drivers/clk/ti/dpll.c:of_ti_omap3_dpll_setup",
        "drivers/clk/ti/dpll.c:of_ti_omap3_dpll_setup",
        "drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup",
        "drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup",
        "drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup",
        "drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup",
        "drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup",
        "drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup",
        "drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup",
        "drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup",
        "drivers/soc/tegra/fuse/tegra-apbmisc.c:tegra_init_apbmisc",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/edac/armada_xp_edac.c:axp_mc_probe",
        "drivers/edac/armada_xp_edac.c:axp_mc_probe",
        "drivers/cpufreq/mvebu-cpufreq.c:armada_xp_pmsu_cpufreq_init",
        "drivers/cpufreq/tegra124-cpufreq.c:tegra_cpufreq_init",
        "drivers/cpufreq/tegra124-cpufreq.c:tegra_cpufreq_init",
        "drivers/cpuidle/cpuidle-exynos.c:exynos_cpuidle_probe",
        "drivers/cpuidle/cpuidle-exynos.c:exynos_cpuidle_probe",
        "drivers/clocksource/timer-tegra.c:tegra20_init_timer",
        "drivers/clocksource/timer-tegra.c:tegra20_init_timer",
        "drivers/clocksource/timer-ti-32k.c:ti_32k_timer_init",
        "drivers/clocksource/timer-imx-gpt.c:imx31_timer_init_dt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234128916,
      "name": "of_machine_is_compatible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int of_machine_is_compatible(const char * compat)
```

```json
{
  "name": "of_machine_is_compatible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295027824,
      "name": "of_machine_is_compatible",
      "external": true,
      "loc": "drivers/of/base.c:593",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/pci_64.c:__se_sys_pciconfig_iobase",
        "arch/powerpc/platforms/powernv/setup.c:pnv_probe",
        "arch/powerpc/platforms/pseries/setup.c:pSeries_probe",
        "arch/powerpc/platforms/pseries/setup.c:pSeries_probe",
        "drivers/of/address.c:__of_translate_address",
        "drivers/of/address.c:__of_translate_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295027824,
      "name": "of_machine_is_compatible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int of_machine_is_compatible(const char * compat)
```

```json
{
  "name": "of_machine_is_compatible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278070662,
      "name": "of_machine_is_compatible",
      "external": true,
      "loc": "drivers/of/base.c:593",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278070662,
      "name": "of_machine_is_compatible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int of_machine_is_compatible(const char * compat)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int of_machine_is_compatible(const char * compat)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int of_machine_is_compatible(const char * compat)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int of_machine_is_compatible(const char * compat)
```
</details>
</li>
</ul>
