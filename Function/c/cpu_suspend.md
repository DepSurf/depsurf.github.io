# Function: <code>cpu_suspend</code>

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
int cpu_suspend(long unsigned int arg, int (*)(long unsigned int) fn)
```

```json
{
  "name": "cpu_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490315104,
      "name": "cpu_suspend",
      "external": true,
      "loc": "arch/arm64/kernel/suspend.c:86",
      "file": "arch/arm64/kernel/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/psci/psci.c:psci_system_suspend_enter",
        "drivers/firmware/psci/psci.c:psci_cpu_suspend_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490315104,
      "name": "cpu_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
int cpu_suspend(long unsigned int arg, int (*)(long unsigned int) fn)
```

```json
{
  "name": "cpu_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224443696,
      "name": "cpu_suspend",
      "external": true,
      "loc": "arch/arm/kernel/suspend.c:20",
      "file": "arch/arm/kernel/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/hibernate.c:swsusp_arch_suspend",
        "arch/arm/common/mcpm_entry.c:mcpm_loopback",
        "arch/arm/common/bL_switcher.c:bL_switch_to",
        "arch/arm/mach-exynos/firmware.c:exynos_suspend",
        "arch/arm/mach-exynos/pm.c:exynos_cpu1_powerdown",
        "arch/arm/mach-exynos/pm.c:exynos_enter_aftr",
        "arch/arm/mach-exynos/suspend.c:exynos_suspend_enter",
        "arch/arm/mach-highbank/pm.c:highbank_pm_enter",
        "arch/arm/mach-mvebu/pmsu.c:armada_370_xp_cpu_suspend",
        "arch/arm/mach-imx/cpuidle-imx6sx.c:imx6sx_enter_wait",
        "arch/arm/mach-imx/pm-imx6.c:imx6q_pm_enter",
        "arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_enter_lowpower",
        "arch/arm/mach-omap2/pm34xx.c:omap_sram_idle",
        "arch/arm/mach-omap2/pm33xx-core.c:am33xx_suspend",
        "arch/arm/mach-rockchip/pm.c:rk3288_suspend_enter",
        "arch/arm/mach-shmobile/platsmp-apmu.c:shmobile_smp_apmu_enter_suspend",
        "arch/arm/mach-tegra/pm.c:tegra_suspend_enter",
        "arch/arm/mach-tegra/pm.c:tegra_suspend_enter",
        "arch/arm/mach-tegra/pm.c:tegra_suspend_enter",
        "arch/arm/mach-tegra/pm.c:tegra_idle_lp2_last",
        "arch/arm/mach-tegra/cpuidle-tegra30.c:tegra30_idle_lp2",
        "arch/arm/mach-tegra/cpuidle-tegra114.c:tegra114_idle_power_down",
        "drivers/soc/qcom/spm.c:qcom_cpu_spc",
        "drivers/cpuidle/cpuidle-big_little.c:bl_enter_powerdown",
        "drivers/firmware/psci/psci.c:psci_system_suspend_enter",
        "drivers/firmware/psci/psci.c:psci_cpu_suspend_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224443696,
      "name": "cpu_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int cpu_suspend(long unsigned int arg, int (*)(long unsigned int) fn)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int cpu_suspend(long unsigned int arg, int (*)(long unsigned int) fn)
```
</details>
</li>
</ul>
