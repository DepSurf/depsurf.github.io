# Function: <code>pmu_raw_writel</code>

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
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
void pmu_raw_writel(u32 val, u32 offset)
```

```json
{
  "name": "pmu_raw_writel",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224554532,
      "name": "pmu_raw_writel",
      "external": false,
      "loc": "arch/arm/mach-exynos/common.h:155",
      "file": "arch/arm/mach-exynos/exynos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-exynos/exynos.c:exynos_set_delayed_reset_assertion"
      ],
      "caller_func": []
    },
    {
      "addr": 3224556548,
      "name": "pmu_raw_writel",
      "external": false,
      "loc": "arch/arm/mach-exynos/common.h:155",
      "file": "arch/arm/mach-exynos/pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-exynos/pm.c:exynos_enter_aftr",
        "arch/arm/mach-exynos/pm.c:exynos_enter_aftr",
        "arch/arm/mach-exynos/pm.c:exynos_enter_aftr"
      ],
      "caller_func": []
    },
    {
      "addr": 3224558424,
      "name": "pmu_raw_writel",
      "external": false,
      "loc": "arch/arm/mach-exynos/common.h:155",
      "file": "arch/arm/mach-exynos/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-exynos/suspend.c:exynos5420_pm_resume",
        "arch/arm/mach-exynos/suspend.c:exynos5420_pm_resume",
        "arch/arm/mach-exynos/suspend.c:exynos5420_pm_resume",
        "arch/arm/mach-exynos/suspend.c:exynos5420_pm_resume",
        "arch/arm/mach-exynos/suspend.c:exynos5420_pm_resume",
        "arch/arm/mach-exynos/suspend.c:exynos5420_pm_resume",
        "arch/arm/mach-exynos/suspend.c:exynos5420_pm_resume",
        "arch/arm/mach-exynos/suspend.c:exynos3250_pm_resume",
        "arch/arm/mach-exynos/suspend.c:exynos3250_pm_resume",
        "arch/arm/mach-exynos/suspend.c:exynos_pm_resume",
        "arch/arm/mach-exynos/suspend.c:exynos_pm_suspend",
        "arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare",
        "arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare",
        "arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare",
        "arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare",
        "arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare",
        "arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare",
        "arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare",
        "arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare",
        "arch/arm/mach-exynos/suspend.c:exynos3250_pm_prepare",
        "arch/arm/mach-exynos/suspend.c:exynos3250_pm_prepare",
        "arch/arm/mach-exynos/suspend.c:exynos3250_pm_prepare",
        "arch/arm/mach-exynos/suspend.c:exynos3250_pm_prepare",
        "arch/arm/mach-exynos/suspend.c:exynos_pm_prepare",
        "arch/arm/mach-exynos/suspend.c:exynos_pm_prepare",
        "arch/arm/mach-exynos/suspend.c:exynos_pm_prepare",
        "arch/arm/mach-exynos/suspend.c:exynos_pm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3224561420,
      "name": "pmu_raw_writel",
      "external": false,
      "loc": "arch/arm/mach-exynos/common.h:155",
      "file": "arch/arm/mach-exynos/platsmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-exynos/platsmp.c:exynos_boot_secondary",
        "arch/arm/mach-exynos/platsmp.c:exynos_cluster_power_up",
        "arch/arm/mach-exynos/platsmp.c:exynos_cluster_power_down",
        "arch/arm/mach-exynos/platsmp.c:exynos_cpu_power_down"
      ],
      "caller_func": []
    },
    {
      "addr": 3243297500,
      "name": "pmu_raw_writel",
      "external": false,
      "loc": "arch/arm/mach-exynos/common.h:155",
      "file": "arch/arm/mach-exynos/mcpm-exynos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-exynos/mcpm-exynos.c:exynos_mcpm_init",
        "arch/arm/mach-exynos/mcpm-exynos.c:exynos_mcpm_init",
        "arch/arm/mach-exynos/mcpm-exynos.c:exynos_cpu_powerup"
      ],
      "caller_func": []
    },
    {
      "addr": 3230899876,
      "name": "pmu_raw_writel",
      "external": true,
      "loc": "drivers/soc/samsung/exynos-pmu.c:28",
      "file": "drivers/soc/samsung/exynos-pmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/soc/samsung/exynos-pmu.c:exynos_sys_powerdown_conf"
      ],
      "caller_func": [
        "drivers/soc/samsung/exynos3250-pmu.c:exynos3250_pmu_init",
        "drivers/soc/samsung/exynos3250-pmu.c:exynos3250_pmu_init",
        "drivers/soc/samsung/exynos3250-pmu.c:exynos3250_pmu_init",
        "drivers/soc/samsung/exynos3250-pmu.c:exynos3250_pmu_init",
        "drivers/soc/samsung/exynos5250-pmu.c:exynos5_powerdown_conf",
        "drivers/soc/samsung/exynos5250-pmu.c:exynos5_powerdown_conf",
        "drivers/soc/samsung/exynos5250-pmu.c:exynos5_powerdown_conf",
        "drivers/soc/samsung/exynos5250-pmu.c:exynos5250_pmu_init",
        "drivers/soc/samsung/exynos5250-pmu.c:exynos5250_pmu_init",
        "drivers/soc/samsung/exynos5420-pmu.c:exynos5420_pmu_init",
        "drivers/soc/samsung/exynos5420-pmu.c:exynos5420_pmu_init",
        "drivers/soc/samsung/exynos5420-pmu.c:exynos5420_pmu_init",
        "drivers/soc/samsung/exynos5420-pmu.c:exynos5420_pmu_init",
        "drivers/soc/samsung/exynos5420-pmu.c:exynos5420_pmu_init",
        "drivers/soc/samsung/exynos5420-pmu.c:exynos5420_pmu_init",
        "drivers/soc/samsung/exynos5420-pmu.c:exynos5420_pmu_init",
        "drivers/soc/samsung/exynos5420-pmu.c:exynos5420_pmu_init",
        "drivers/soc/samsung/exynos5420-pmu.c:exynos5420_pmu_init",
        "drivers/soc/samsung/exynos5420-pmu.c:exynos5420_pmu_init",
        "drivers/soc/samsung/exynos5420-pmu.c:exynos5420_pmu_init",
        "drivers/soc/samsung/exynos5420-pmu.c:exynos5420_pmu_init",
        "drivers/soc/samsung/exynos5420-pmu.c:exynos5420_powerdown_conf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230899680,
      "name": "pmu_raw_writel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void pmu_raw_writel(u32 val, u32 offset)
```
</details>
</li>
</ul>
