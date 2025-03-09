# Function: <code>cpu_pm_exit</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int cpu_pm_exit()
```

```json
{
  "name": "cpu_pm_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492103216,
      "name": "cpu_pm_exit",
      "external": true,
      "loc": "kernel/cpu_pm.c:110",
      "file": "kernel/cpu_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu_pm.c:cpu_pm_resume"
      ],
      "caller_func": [
        "arch/arm64/kernel/cpuidle.c:acpi_processor_ffh_lpi_enter",
        "drivers/cpuidle/cpuidle-psci.c:psci_enter_idle_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492102936,
      "name": "cpu_pm_exit",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int cpu_pm_exit()
```

```json
{
  "name": "cpu_pm_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226003344,
      "name": "cpu_pm_exit",
      "external": true,
      "loc": "kernel/cpu_pm.c:110",
      "file": "kernel/cpu_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu_pm.c:cpu_pm_resume"
      ],
      "caller_func": [
        "arch/arm/common/mcpm_entry.c:mcpm_loopback",
        "arch/arm/common/bL_switcher.c:bL_switch_to",
        "arch/arm/mach-exynos/pm.c:exynos_cpu1_powerdown",
        "arch/arm/mach-exynos/pm.c:exynos_enter_aftr",
        "arch/arm/mach-highbank/pm.c:highbank_pm_enter",
        "arch/arm/mach-imx/cpuidle-imx6sx.c:imx6sx_enter_wait",
        "arch/arm/mach-omap2/cpuidle34xx.c:omap3_enter_idle_bm",
        "arch/arm/mach-omap2/cpuidle44xx.c:omap_enter_idle_coupled",
        "arch/arm/mach-omap2/cpuidle44xx.c:omap_enter_idle_coupled",
        "arch/arm/mach-omap2/cpuidle44xx.c:omap_enter_idle_coupled",
        "arch/arm/mach-tegra/cpuidle-tegra30.c:tegra30_idle_lp2",
        "arch/arm/mach-tegra/cpuidle-tegra30.c:tegra30_idle_lp2",
        "arch/arm/mach-tegra/cpuidle-tegra114.c:tegra114_idle_power_down",
        "drivers/cpuidle/cpuidle-mvebu-v7.c:mvebu_v7_enter_idle",
        "drivers/cpuidle/cpuidle-big_little.c:bl_enter_powerdown",
        "drivers/cpuidle/cpuidle-psci.c:psci_enter_idle_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226003056,
      "name": "cpu_pm_exit",
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
int cpu_pm_exit()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int cpu_pm_exit()
```
</details>
</li>
</ul>
