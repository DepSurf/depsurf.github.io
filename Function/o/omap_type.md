# Function: <code>omap_type</code>

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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
int omap_type()
```

```json
{
  "name": "omap_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224588236,
      "name": "omap_type",
      "external": true,
      "loc": "arch/arm/mach-omap2/id.c:50",
      "file": "arch/arm/mach-omap2/id.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/id.c:omap_get_type"
      ],
      "caller_func": [
        "arch/arm/mach-omap2/id.c:omap_get_type",
        "arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents",
        "arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents",
        "arch/arm/mach-omap2/timer.c:__omap_sync32k_timer_init",
        "arch/arm/mach-omap2/dma.c:omap2_system_dma_init_dev",
        "arch/arm/mach-omap2/dma.c:omap2_system_dma_init_dev",
        "arch/arm/mach-omap2/dma.c:omap2_system_dma_init_dev",
        "arch/arm/mach-omap2/sram.c:omap_sram_init",
        "arch/arm/mach-omap2/sram.c:omap_sram_init",
        "arch/arm/mach-omap2/sram.c:omap_sram_init",
        "arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_init",
        "arch/arm/mach-omap2/pm34xx.c:omap3_pm_init",
        "arch/arm/mach-omap2/pm34xx.c:omap3_pm_init",
        "arch/arm/mach-omap2/pm34xx.c:omap_sram_idle",
        "arch/arm/mach-omap2/pm34xx.c:omap_sram_idle",
        "arch/arm/mach-omap2/pm34xx.c:omap_sram_idle",
        "arch/arm/mach-omap2/pm34xx.c:omap_sram_idle",
        "arch/arm/mach-omap2/pm33xx-core.c:am33xx_suspend_init",
        "arch/arm/mach-omap2/clock.c:ti_clk_init_features",
        "arch/arm/mach-omap2/omap_hwmod_3xxx_data.c:omap3xxx_hwmod_init",
        "arch/arm/mach-omap2/omap_hwmod_3xxx_data.c:omap3xxx_hwmod_is_hs_ip_block_usable",
        "arch/arm/mach-omap2/omap_hwmod_7xx_data.c:dra7xx_hwmod_init",
        "arch/arm/mach-omap2/pdata-quirks.c:nokia_n900_legacy_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224587980,
      "name": "omap_type.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 3224588168,
      "name": "omap_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int omap_type()
```
</details>
</li>
</ul>
