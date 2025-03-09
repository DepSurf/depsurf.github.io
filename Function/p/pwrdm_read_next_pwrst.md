# Function: <code>pwrdm_read_next_pwrst</code>

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
int pwrdm_read_next_pwrst(struct powerdomain * pwrdm)
```

```json
{
  "name": "pwrdm_read_next_pwrst",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224658204,
      "name": "pwrdm_read_next_pwrst",
      "external": true,
      "loc": "arch/arm/mach-omap2/powerdomain.c:561",
      "file": "arch/arm/mach-omap2/powerdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/powerdomain.c:omap_set_pwrdm_state",
        "arch/arm/mach-omap2/powerdomain.c:_pwrdm_state_switch"
      ],
      "caller_func": [
        "arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_enter_lowpower",
        "arch/arm/mach-omap2/pm34xx.c:omap3_pm_init",
        "arch/arm/mach-omap2/pm34xx.c:omap3_pm_suspend",
        "arch/arm/mach-omap2/pm34xx.c:omap_sram_idle",
        "arch/arm/mach-omap2/pm34xx.c:omap_sram_idle",
        "arch/arm/mach-omap2/pm34xx.c:omap_sram_idle",
        "arch/arm/mach-omap2/pm44xx.c:omap4_pm_suspend",
        "arch/arm/mach-omap2/cpuidle34xx.c:omap3_enter_idle_bm",
        "arch/arm/mach-omap2/omap-iommu.c:omap_iommu_set_pwrdm_constraint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224654672,
      "name": "pwrdm_read_next_pwrst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int pwrdm_read_next_pwrst(struct powerdomain * pwrdm)
```
</details>
</li>
</ul>
