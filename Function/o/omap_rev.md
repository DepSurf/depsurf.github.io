# Function: <code>omap_rev</code>

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
unsigned int omap_rev()
```

```json
{
  "name": "omap_rev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243318484,
      "name": "omap_rev",
      "external": true,
      "loc": "arch/arm/mach-omap2/id.c:44",
      "file": "arch/arm/mach-omap2/id.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/id.c:omap_soc_device_init",
        "arch/arm/mach-omap2/id.c:dra7xxx_check_revision",
        "arch/arm/mach-omap2/id.c:dra7xxx_check_revision",
        "arch/arm/mach-omap2/id.c:omap5xxx_check_revision",
        "arch/arm/mach-omap2/id.c:omap5xxx_check_revision",
        "arch/arm/mach-omap2/id.c:omap4xxx_check_revision",
        "arch/arm/mach-omap2/id.c:omap4xxx_check_revision",
        "arch/arm/mach-omap2/id.c:omap3xxx_check_features",
        "arch/arm/mach-omap2/id.c:omap3_cpuinfo",
        "arch/arm/mach-omap2/id.c:omap2xxx_check_revision",
        "arch/arm/mach-omap2/id.c:omap2xxx_check_revision",
        "arch/arm/mach-omap2/id.c:omap2xxx_check_revision",
        "arch/arm/mach-omap2/id.c:__omap_feed_randpool"
      ],
      "caller_func": [
        "arch/arm/mach-omap2/io.c:omap_sdrc_init",
        "arch/arm/mach-omap2/control.c:omap3630_ctrl_disable_rta",
        "arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents",
        "arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents",
        "arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents",
        "arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents",
        "arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents",
        "arch/arm/mach-omap2/control.c:omap_ctrl_write_dsp_boot_mode",
        "arch/arm/mach-omap2/control.c:omap_ctrl_write_dsp_boot_addr",
        "arch/arm/mach-omap2/control.c:omap_ctrl_write_dsp_boot_addr",
        "arch/arm/mach-omap2/fb.c:omap_init_vrfb",
        "arch/arm/mach-omap2/timer.c:realtime_counter_init",
        "arch/arm/mach-omap2/timer.c:__omap_sync32k_timer_init",
        "arch/arm/mach-omap2/timer.c:__omap_sync32k_timer_init",
        "arch/arm/mach-omap2/timer.c:__omap_sync32k_timer_init",
        "arch/arm/mach-omap2/pm.c:__omap2_common_pm_late_init",
        "arch/arm/mach-omap2/pm.c:omap_pm_wake",
        "arch/arm/mach-omap2/pm.c:omap_pm_begin",
        "arch/arm/mach-omap2/dma.c:__omap2_system_dma_init",
        "arch/arm/mach-omap2/dma.c:omap2_system_dma_init_dev",
        "arch/arm/mach-omap2/dma.c:omap2_system_dma_init_dev",
        "arch/arm/mach-omap2/dma.c:omap2_system_dma_init_dev",
        "arch/arm/mach-omap2/display.c:omap_dss_reset",
        "arch/arm/mach-omap2/i2c.c:omap_i2c_reset",
        "arch/arm/mach-omap2/i2c.c:omap_i2c_reset",
        "arch/arm/mach-omap2/omap_hwmod.c:__omap_hwmod_setup_all",
        "arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_init_module",
        "arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_init",
        "arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_init",
        "arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_init",
        "arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_init",
        "arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_init",
        "arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_init",
        "arch/arm/mach-omap2/omap_device.c:__omap_device_late_init",
        "arch/arm/mach-omap2/omap_device.c:__omap_device_init",
        "arch/arm/mach-omap2/sram.c:omap_sram_init",
        "arch/arm/mach-omap2/sram.c:omap_sram_init",
        "arch/arm/mach-omap2/sram.c:omap_sram_init",
        "arch/arm/mach-omap2/sram.c:omap_sram_init",
        "arch/arm/mach-omap2/sram.c:omap_sram_init",
        "arch/arm/mach-omap2/omap_twl.c:omap3_twl_init",
        "arch/arm/mach-omap2/omap_twl.c:omap4_twl_init",
        "arch/arm/mach-omap2/omap4-common.c:omap_gic_of_init",
        "arch/arm/mach-omap2/omap4-common.c:omap4_sar_ram_init",
        "arch/arm/mach-omap2/omap4-common.c:__omap4_sram_init",
        "arch/arm/mach-omap2/omap4-common.c:__omap4_sram_init",
        "arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_init",
        "arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_init",
        "arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_init",
        "arch/arm/mach-omap2/omap-wakeupgen.c:irq_sar_clear",
        "arch/arm/mach-omap2/omap-smp.c:omap4_smp_prepare_cpus",
        "arch/arm/mach-omap2/omap-smp.c:omap4_smp_prepare_cpus",
        "arch/arm/mach-omap2/omap-smp.c:omap4_smp_prepare_cpus",
        "arch/arm/mach-omap2/omap-smp.c:omap4_smp_prepare_cpus",
        "arch/arm/mach-omap2/omap-smp.c:omap4_smp_prepare_cpus",
        "arch/arm/mach-omap2/omap-smp.c:omap4_smp_prepare_cpus",
        "arch/arm/mach-omap2/omap-smp.c:omap4_smp_prepare_cpus",
        "arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_early_init",
        "arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_early_init",
        "arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_early_init",
        "arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_early_init",
        "arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_early_init",
        "arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_init",
        "arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_init",
        "arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_init",
        "arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_init",
        "arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_init",
        "arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_init",
        "arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_hotplug_cpu",
        "arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_enter_lowpower",
        "arch/arm/mach-omap2/pm34xx.c:omap3_pm_init",
        "arch/arm/mach-omap2/pm34xx.c:omap3_pm_init",
        "arch/arm/mach-omap2/pm34xx.c:omap3_pm_init",
        "arch/arm/mach-omap2/pm34xx.c:omap3_pm_init",
        "arch/arm/mach-omap2/pm34xx.c:omap_sram_idle",
        "arch/arm/mach-omap2/pm34xx.c:omap_sram_idle",
        "arch/arm/mach-omap2/pm34xx.c:omap_sram_idle",
        "arch/arm/mach-omap2/pm34xx.c:omap_sram_idle",
        "arch/arm/mach-omap2/pm34xx.c:omap_sram_idle",
        "arch/arm/mach-omap2/pm34xx.c:_prcm_int_handle_wakeup",
        "arch/arm/mach-omap2/pm44xx.c:omap4_pm_init",
        "arch/arm/mach-omap2/pm44xx.c:omap4_pm_init",
        "arch/arm/mach-omap2/pm44xx.c:omap4_pm_init",
        "arch/arm/mach-omap2/pm44xx.c:omap4_pm_init",
        "arch/arm/mach-omap2/pm44xx.c:omap4_pm_init",
        "arch/arm/mach-omap2/pm44xx.c:omap4_pm_init_early",
        "arch/arm/mach-omap2/pm44xx.c:omap4_pm_init_early",
        "arch/arm/mach-omap2/pm33xx-core.c:amx3_common_pm_init",
        "arch/arm/mach-omap2/pm33xx-core.c:amx3_get_sram_addrs",
        "arch/arm/mach-omap2/pm-debug.c:__pm_dbg_init",
        "arch/arm/mach-omap2/pm-debug.c:pwrdm_suspend_set",
        "arch/arm/mach-omap2/pm-debug.c:pwrdm_suspend_get",
        "arch/arm/mach-omap2/sr_device.c:sr_dev_init",
        "arch/arm/mach-omap2/sr_device.c:sr_dev_init",
        "arch/arm/mach-omap2/sr_device.c:sr_dev_init",
        "arch/arm/mach-omap2/sr_device.c:sr_set_nvalues",
        "arch/arm/mach-omap2/smartreflex-class3.c:__sr_class3_init",
        "arch/arm/mach-omap2/cpuidle34xx.c:omap3_idle_init",
        "arch/arm/mach-omap2/vc.c:omap_vc_init_channel",
        "arch/arm/mach-omap2/vc.c:omap_vc_init_channel",
        "arch/arm/mach-omap2/vc.c:omap_vc_init_channel",
        "arch/arm/mach-omap2/voltagedomains3xxx_data.c:omap3xxx_voltagedomains_init",
        "arch/arm/mach-omap2/voltagedomains3xxx_data.c:omap3xxx_voltagedomains_init",
        "arch/arm/mach-omap2/voltagedomains44xx_data.c:omap44xx_voltagedomains_init",
        "arch/arm/mach-omap2/voltagedomains44xx_data.c:omap44xx_voltagedomains_init",
        "arch/arm/mach-omap2/powerdomain.c:pwrdm_register_pwrdms",
        "arch/arm/mach-omap2/powerdomains3xxx_data.c:omap3xxx_powerdomains_init",
        "arch/arm/mach-omap2/powerdomains3xxx_data.c:omap3xxx_powerdomains_init",
        "arch/arm/mach-omap2/powerdomains3xxx_data.c:omap3xxx_powerdomains_init",
        "arch/arm/mach-omap2/powerdomains3xxx_data.c:omap3xxx_powerdomains_init",
        "arch/arm/mach-omap2/powerdomains7xx_data.c:dra7xx_powerdomains_init",
        "arch/arm/mach-omap2/powerdomains7xx_data.c:dra7xx_powerdomains_init",
        "arch/arm/mach-omap2/powerdomains7xx_data.c:dra7xx_powerdomains_init",
        "arch/arm/mach-omap2/clockdomain.c:clkdm_hwmod_disable",
        "arch/arm/mach-omap2/clockdomain.c:clkdm_hwmod_enable",
        "arch/arm/mach-omap2/clockdomains3xxx_data.c:omap3xxx_clockdomains_init",
        "arch/arm/mach-omap2/clockdomains3xxx_data.c:omap3xxx_clockdomains_init",
        "arch/arm/mach-omap2/clock.c:ti_clk_init_features",
        "arch/arm/mach-omap2/clock.c:ti_clk_init_features",
        "arch/arm/mach-omap2/clock.c:ti_clk_init_features",
        "arch/arm/mach-omap2/clock.c:ti_clk_init_features",
        "arch/arm/mach-omap2/clock.c:ti_clk_init_features",
        "arch/arm/mach-omap2/clock.c:ti_clk_init_features",
        "arch/arm/mach-omap2/clock.c:ti_clk_init_features",
        "arch/arm/mach-omap2/clock.c:ti_clk_init_features",
        "arch/arm/mach-omap2/clock.c:ti_clk_init_features",
        "arch/arm/mach-omap2/omap_hwmod_3xxx_data.c:omap3xxx_hwmod_init",
        "arch/arm/mach-omap2/omap_hwmod_7xx_data.c:dra7xx_hwmod_init",
        "arch/arm/mach-omap2/omap_hwmod_7xx_data.c:dra7xx_hwmod_init",
        "arch/arm/mach-omap2/omap_hwmod_7xx_data.c:dra7xx_hwmod_init",
        "arch/arm/mach-omap2/omap_hwmod_7xx_data.c:dra7xx_hwmod_init",
        "arch/arm/mach-omap2/omap_hwmod_7xx_data.c:dra7xx_hwmod_init",
        "arch/arm/mach-omap2/omap_hwmod_7xx_data.c:dra7xx_hwmod_init",
        "arch/arm/mach-omap2/omap_hwmod_7xx_data.c:dra7xx_hwmod_init",
        "arch/arm/mach-omap2/pdata-quirks.c:dra7x_evm_mmc_quirk",
        "arch/arm/mach-omap2/pdata-quirks.c:dra7x_evm_mmc_quirk",
        "arch/arm/mach-omap2/pdata-quirks.c:omap3_logicpd_torpedo_init",
        "arch/arm/mach-omap2/omap_phy_internal.c:__omap4430_phy_power_down",
        "arch/arm/mach-omap2/omap_phy_internal.c:__omap4430_phy_power_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224587944,
      "name": "omap_rev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
unsigned int omap_rev()
```
</details>
</li>
</ul>
