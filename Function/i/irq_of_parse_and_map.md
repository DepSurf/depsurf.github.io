# Function: <code>irq_of_parse_and_map</code>

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
unsigned int irq_of_parse_and_map(struct device_node * dev, int index)
```

```json
{
  "name": "irq_of_parse_and_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501645264,
      "name": "irq_of_parse_and_map",
      "external": true,
      "loc": "drivers/of/irq.c:36",
      "file": "drivers/of/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/xen/enlighten.c:xen_guest_init",
        "drivers/irqchip/irq-al-fic.c:al_fic_init_dt",
        "drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init",
        "drivers/irqchip/irq-sunxi-nmi.c:sunxi_sc_nmi_irq_init",
        "drivers/irqchip/irq-gic.c:gic_of_init",
        "drivers/irqchip/irq-gic.c:gic_of_init",
        "drivers/irqchip/irq-gic-v3.c:gic_of_setup_kvm_info",
        "drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_of_init",
        "drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_probe",
        "drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_probe",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe",
        "drivers/pinctrl/pinctrl-single.c:pcs_probe",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe",
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pinctrl_probe",
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pinctrl_probe",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pinctrl_probe",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_build_eint",
        "drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_host_init",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_host_init",
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/edac/altera_edac.c:altr_edac_a10_device_add",
        "drivers/clocksource/timer-of.c:timer_of_init",
        "drivers/clocksource/timer-rockchip.c:rk_timer_probe",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_mem_of_init",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_mem_of_init",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_of_init",
        "drivers/clocksource/timer-sp804.c:integrator_cp_of_init",
        "drivers/clocksource/timer-sp804.c:sp804_of_init",
        "drivers/of/platform.c:of_platform_bus_create",
        "drivers/mailbox/bcm2835-mailbox.c:bcm2835_mbox_probe",
        "drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_probe",
        "drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501645264,
      "name": "irq_of_parse_and_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
unsigned int irq_of_parse_and_map(struct device_node * dev, int index)
```

```json
{
  "name": "irq_of_parse_and_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234165928,
      "name": "irq_of_parse_and_map",
      "external": true,
      "loc": "drivers/of/irq.c:36",
      "file": "drivers/of/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/smp_twd.c:twd_local_timer_of_register",
        "arch/arm/mach-omap2/timer.c:omap_dm_timer_init_one",
        "arch/arm/mach-omap2/omap_device.c:omap_device_build",
        "arch/arm/mach-omap2/omap_device.c:omap_device_build",
        "arch/arm/mach-vexpress/tc2_pm.c:tc2_pm_init",
        "drivers/irqchip/irq-al-fic.c:al_fic_init_dt",
        "drivers/irqchip/exynos-combiner.c:combiner_init",
        "drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init",
        "drivers/irqchip/irq-orion.c:orion_bridge_irq_init",
        "drivers/irqchip/irq-gic.c:gic_of_init",
        "drivers/irqchip/irq-gic.c:gic_of_init",
        "drivers/irqchip/irq-gic-v3.c:gic_of_init",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init",
        "drivers/irqchip/irq-aspeed-i2c-ic.c:aspeed_i2c_ic_of_init",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_get_soc_data",
        "drivers/pinctrl/pinctrl-single.c:pcs_probe",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_gpio_of",
        "drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_eint_wkup_init",
        "drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_eint_wkup_init",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_build_eint",
        "drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_host_init",
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/dma/ti/edma.c:edma_probe",
        "drivers/dma/ti/edma.c:edma_probe",
        "drivers/soc/dove/pmu.c:dove_init_pmu",
        "drivers/tty/serial/omap-serial.c:serial_omap_probe",
        "drivers/tty/serial/omap-serial.c:serial_omap_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe",
        "drivers/clocksource/timer-of.c:timer_of_init",
        "drivers/clocksource/renesas-ostm.c:ostm_init",
        "drivers/clocksource/dw_apb_timer_of.c:dw_apb_timer_init",
        "drivers/clocksource/timer-rockchip.c:rk_timer_probe",
        "drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_common_init",
        "drivers/clocksource/timer-orion.c:orion_timer_init",
        "drivers/clocksource/timer-meson6.c:meson6_timer_init",
        "drivers/clocksource/timer-tegra.c:tegra_init_timer",
        "drivers/clocksource/exynos_mct.c:mct_init_dt",
        "drivers/clocksource/exynos_mct.c:mct_init_dt",
        "drivers/clocksource/timer-qcom.c:msm_dt_timer_init",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_mem_of_init",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_mem_of_init",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_of_init",
        "drivers/clocksource/arm_global_timer.c:global_timer_of_register",
        "drivers/clocksource/timer-sp804.c:integrator_cp_of_init",
        "drivers/clocksource/timer-sp804.c:sp804_of_init",
        "drivers/clocksource/timer-imx-gpt.c:mxc_timer_init_dt",
        "drivers/of/platform.c:of_platform_bus_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234165928,
      "name": "irq_of_parse_and_map",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
unsigned int irq_of_parse_and_map(struct device_node * dev, int index)
```

```json
{
  "name": "irq_of_parse_and_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295083520,
      "name": "irq_of_parse_and_map",
      "external": true,
      "loc": "drivers/of/irq.c:36",
      "file": "drivers/of/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/setup-common.c:check_legacy_ioport",
        "arch/powerpc/kernel/setup-common.c:check_legacy_ioport",
        "arch/powerpc/kernel/legacy_serial.c:serial_dev_init",
        "arch/powerpc/kernel/legacy_serial.c:serial_dev_init",
        "arch/powerpc/sysdev/mpic.c:mpic_init",
        "arch/powerpc/sysdev/fsl_lbc.c:fsl_lbc_ctrl_probe",
        "arch/powerpc/sysdev/fsl_lbc.c:fsl_lbc_ctrl_probe",
        "arch/powerpc/platforms/pseries/setup.c:pseries_init_irq",
        "arch/powerpc/platforms/pseries/vio.c:vio_register_device_node",
        "drivers/irqchip/irq-al-fic.c:al_fic_init_dt",
        "drivers/pinctrl/pinctrl-single.c:pcs_probe",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/tty/hvc/hvc_opal.c:hvc_opal_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_ppc_of_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295083520,
      "name": "irq_of_parse_and_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
unsigned int irq_of_parse_and_map(struct device_node * dev, int index)
```

```json
{
  "name": "irq_of_parse_and_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278104220,
      "name": "irq_of_parse_and_map",
      "external": true,
      "loc": "drivers/of/irq.c:36",
      "file": "drivers/of/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/mm/sifive_l2_cache.c:sifive_l2_init",
        "drivers/irqchip/irq-al-fic.c:al_fic_init_dt",
        "drivers/pinctrl/pinctrl-single.c:pcs_probe",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mmc/host/of_mmc_spi.c:mmc_spi_get_pdata",
        "drivers/clocksource/timer-of.c:timer_of_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278104220,
      "name": "irq_of_parse_and_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
unsigned int irq_of_parse_and_map(struct device_node * dev, int index)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
unsigned int irq_of_parse_and_map(struct device_node * dev, int index)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
unsigned int irq_of_parse_and_map(struct device_node * dev, int index)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
unsigned int irq_of_parse_and_map(struct device_node * dev, int index)
```
</details>
</li>
</ul>
