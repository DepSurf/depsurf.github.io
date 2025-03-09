# Function: <code>omap_set_pwrdm_state</code>

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
int omap_set_pwrdm_state(struct powerdomain * pwrdm, u8 pwrst)
```

```json
{
  "name": "omap_set_pwrdm_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224658004,
      "name": "omap_set_pwrdm_state",
      "external": true,
      "loc": "arch/arm/mach-omap2/powerdomain.c:1108",
      "file": "arch/arm/mach-omap2/powerdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-omap2/pm34xx.c:pwrdms_setup",
        "arch/arm/mach-omap2/pm34xx.c:omap3_pm_off_mode_enable",
        "arch/arm/mach-omap2/pm34xx.c:omap3_pm_suspend",
        "arch/arm/mach-omap2/pm34xx.c:omap3_pm_suspend",
        "arch/arm/mach-omap2/pm44xx.c:pwrdms_setup",
        "arch/arm/mach-omap2/pm44xx.c:omap4_pm_suspend",
        "arch/arm/mach-omap2/pm44xx.c:omap4_pm_suspend",
        "arch/arm/mach-omap2/pm33xx-core.c:am33xx_suspend",
        "arch/arm/mach-omap2/pm33xx-core.c:am33xx_suspend_init",
        "arch/arm/mach-omap2/cpuidle44xx.c:omap_enter_idle_coupled",
        "arch/arm/mach-omap2/cpuidle44xx.c:omap_enter_idle_coupled",
        "arch/arm/mach-omap2/cpuidle44xx.c:omap_enter_idle_coupled",
        "arch/arm/mach-omap2/cpuidle44xx.c:omap_enter_idle_coupled",
        "arch/arm/mach-omap2/cpuidle44xx.c:omap_enter_idle_coupled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224658004,
      "name": "omap_set_pwrdm_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
int omap_set_pwrdm_state(struct powerdomain * pwrdm, u8 pwrst)
```
</details>
</li>
</ul>
