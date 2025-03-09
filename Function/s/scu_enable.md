# Function: <code>scu_enable</code>

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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void scu_enable(void * scu_base)
```

```json
{
  "name": "scu_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224454344,
      "name": "scu_enable",
      "external": true,
      "loc": "arch/arm/kernel/smp_scu.c:38",
      "file": "arch/arm/kernel/smp_scu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-actions/platsmp.c:s500_smp_prepare_cpus",
        "arch/arm/mach-berlin/platsmp.c:berlin_smp_prepare_cpus",
        "arch/arm/mach-exynos/platsmp.c:exynos_scu_enable",
        "arch/arm/mach-hisi/platsmp.c:hisi_enable_scu_a9",
        "arch/arm/mach-meson/platsmp.c:meson_smp_prepare_cpus",
        "arch/arm/mach-mvebu/board-v7.c:mvebu_init_irq",
        "arch/arm/mach-imx/platsmp.c:imx_smp_prepare_cpus",
        "arch/arm/mach-npcm/platsmp.c:npcm7xx_smp_prepare_cpus",
        "arch/arm/mach-omap2/omap-smp.c:omap4_smp_prepare_cpus",
        "arch/arm/mach-rockchip/platsmp.c:rockchip_smp_prepare_cpus",
        "arch/arm/mach-shmobile/platsmp-scu.c:shmobile_smp_scu_prepare_cpus",
        "arch/arm/mach-tegra/platsmp.c:tegra_smp_prepare_cpus",
        "arch/arm/mach-vexpress/platsmp.c:vexpress_smp_dt_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224454344,
      "name": "scu_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void scu_enable(void * scu_base)
```
</details>
</li>
</ul>
