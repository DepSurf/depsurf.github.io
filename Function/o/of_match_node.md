# Function: <code>of_match_node</code>

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
const struct of_device_id * of_match_node(const struct of_device_id * matches, const struct device_node * node)
```

```json
{
  "name": "of_match_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501596904,
      "name": "of_match_node",
      "external": true,
      "loc": "drivers/of/base.c:1136",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init",
        "drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_of_init",
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_probe",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_register",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_register",
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pinctrl_probe",
        "drivers/pci/controller/pci-host-generic.c:gen_pci_probe",
        "drivers/clk/clk-fixed-factor.c:_of_fixed_factor_clk_setup",
        "drivers/soc/bcm/brcmstb/common.c:soc_is_brcmstb",
        "drivers/soc/imx/soc-imx8.c:imx8_soc_init",
        "drivers/soc/renesas/renesas-soc.c:renesas_soc_init",
        "drivers/soc/sunxi/sunxi_sram.c:sunxi_sram_of_parse",
        "drivers/soc/sunxi/sunxi_sram.c:sunxi_sram_show",
        "drivers/tty/serial/owl-uart.c:owl_uart_probe",
        "drivers/mfd/sun6i-prcm.c:sun6i_prcm_probe",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/edac/altera_edac.c:altr_edac_a10_device_add",
        "drivers/edac/altera_edac.c:altr_init_a10_ecc_device_type",
        "drivers/edac/altera_edac.c:altr_edac_device_probe",
        "drivers/edac/altera_edac.c:altr_sdram_probe",
        "drivers/cpufreq/cpufreq-dt-platdev.c:cpufreq_dt_platdev_init",
        "drivers/cpufreq/cpufreq-dt-platdev.c:cpufreq_dt_platdev_init",
        "drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver",
        "drivers/of/base.c:of_alias_get_alias_list",
        "drivers/of/device.c:of_device_get_match_data",
        "drivers/of/platform.c:of_platform_bus_probe",
        "drivers/of/platform.c:of_platform_bus_probe",
        "drivers/of/platform.c:of_platform_bus_probe",
        "drivers/of/platform.c:of_platform_bus_create",
        "drivers/of/platform.c:of_platform_bus_create",
        "drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe",
        "drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501596904,
      "name": "of_match_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
const struct of_device_id * of_match_node(const struct of_device_id * matches, const struct device_node * node)
```

```json
{
  "name": "of_match_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234125912,
      "name": "of_match_node",
      "external": true,
      "loc": "drivers/of/base.c:1136",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/cache-l2x0.c:l2x0_of_init",
        "arch/arm/mm/cache-uniphier.c:__uniphier_cache_init",
        "drivers/irqchip/irq-tegra.c:tegra_ictlr_init",
        "drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init",
        "drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_of_init",
        "drivers/bus/arm-cci.c:cci_probe_ports",
        "drivers/bus/arm-cci.c:cci_probe_ports",
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe",
        "drivers/phy/ti/phy-gmii-sel.c:phy_gmii_sel_probe",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_get_soc_data",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_parse_dt",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_parse_dt",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_legacy_probe",
        "drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_eint_wkup_init",
        "drivers/pci/controller/pci-host-generic.c:gen_pci_probe",
        "drivers/clk/clk-fixed-factor.c:_of_fixed_factor_clk_setup",
        "drivers/dma/ti/edma.c:edma_probe",
        "drivers/dma/ti/dma-crossbar.c:ti_dma_xbar_probe",
        "drivers/dma/ti/dma-crossbar.c:ti_dma_xbar_probe",
        "drivers/dma/ti/dma-crossbar.c:ti_dra7_xbar_probe",
        "drivers/soc/imx/soc-imx8.c:imx8_soc_init",
        "drivers/soc/qcom/spm.c:spm_dev_probe",
        "drivers/soc/qcom/spm.c:qcom_cpuidle_init",
        "drivers/soc/renesas/renesas-soc.c:renesas_soc_init",
        "drivers/soc/tegra/common.c:soc_is_tegra",
        "drivers/tty/serial/owl-uart.c:owl_uart_probe",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_get_type",
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_probe",
        "drivers/watchdog/aspeed_wdt.c:aspeed_wdt_probe",
        "drivers/cpufreq/cpufreq-dt-platdev.c:cpufreq_dt_platdev_init",
        "drivers/cpufreq/cpufreq-dt-platdev.c:cpufreq_dt_platdev_init",
        "drivers/cpufreq/ti-cpufreq.c:ti_cpufreq_init",
        "drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver",
        "drivers/cpuidle/cpuidle-big_little.c:bl_idle_init",
        "drivers/of/base.c:of_alias_get_alias_list",
        "drivers/of/device.c:of_device_get_match_data",
        "drivers/of/platform.c:of_platform_bus_probe",
        "drivers/of/platform.c:of_platform_bus_probe",
        "drivers/of/platform.c:of_platform_bus_create",
        "drivers/of/platform.c:of_platform_bus_create",
        "drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe",
        "drivers/memory/omap-gpmc.c:gpmc_probe_generic_child",
        "drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234125912,
      "name": "of_match_node",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
const struct of_device_id * of_match_node(const struct of_device_id * matches, const struct device_node * node)
```

```json
{
  "name": "of_match_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295022208,
      "name": "of_match_node",
      "external": true,
      "loc": "drivers/of/base.c:1136",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/legacy_serial.c:find_legacy_serial_ports",
        "drivers/pci/controller/pci-host-generic.c:gen_pci_probe",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_get_type",
        "drivers/of/base.c:of_alias_get_alias_list",
        "drivers/of/device.c:of_device_get_match_data",
        "drivers/of/platform.c:of_platform_bus_probe",
        "drivers/of/platform.c:of_platform_bus_probe",
        "drivers/of/platform.c:of_platform_bus_probe",
        "drivers/of/platform.c:of_platform_bus_create",
        "drivers/of/platform.c:of_platform_bus_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295022208,
      "name": "of_match_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
const struct of_device_id * of_match_node(const struct of_device_id * matches, const struct device_node * node)
```

```json
{
  "name": "of_match_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278067754,
      "name": "of_match_node",
      "external": true,
      "loc": "drivers/of/base.c:1136",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/perf_event.c:init_hw_perf_events",
        "drivers/pci/controller/pci-host-generic.c:gen_pci_probe",
        "drivers/clk/clk-fixed-factor.c:_of_fixed_factor_clk_setup",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_get_type",
        "drivers/of/base.c:of_alias_get_alias_list",
        "drivers/of/device.c:of_device_get_match_data",
        "drivers/of/platform.c:of_platform_bus_probe",
        "drivers/of/platform.c:of_platform_bus_probe",
        "drivers/of/platform.c:of_platform_bus_create",
        "drivers/of/platform.c:of_platform_bus_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278067754,
      "name": "of_match_node",
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
const struct of_device_id * of_match_node(const struct of_device_id * matches, const struct device_node * node)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
const struct of_device_id * of_match_node(const struct of_device_id * matches, const struct device_node * node)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
const struct of_device_id * of_match_node(const struct of_device_id * matches, const struct device_node * node)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
const struct of_device_id * of_match_node(const struct of_device_id * matches, const struct device_node * node)
```
</details>
</li>
</ul>
