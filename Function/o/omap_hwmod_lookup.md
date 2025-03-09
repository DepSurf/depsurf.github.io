# Function: <code>omap_hwmod_lookup</code>

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
struct omap_hwmod * omap_hwmod_lookup(const char * name)
```

```json
{
  "name": "omap_hwmod_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243328496,
      "name": "omap_hwmod_lookup",
      "external": true,
      "loc": "arch/arm/mach-omap2/omap_hwmod.c:3025",
      "file": "arch/arm/mach-omap2/omap_hwmod.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/omap_hwmod.c:__omap_hwmod_setup_all",
        "arch/arm/mach-omap2/omap_hwmod.c:__omap_hwmod_setup_all"
      ],
      "caller_func": [
        "arch/arm/mach-omap2/timer.c:__omap_sync32k_timer_init",
        "arch/arm/mach-omap2/timer.c:__omap_sync32k_timer_init",
        "arch/arm/mach-omap2/timer.c:omap_dm_timer_init_one",
        "arch/arm/mach-omap2/display.c:omap_dss_reset",
        "arch/arm/mach-omap2/omap_device.c:omap_device_get_by_hwmod_name",
        "arch/arm/mach-omap2/omap_device.c:omap_device_build_from_dt",
        "arch/arm/mach-omap2/pm33xx-core.c:am43xx_get_rtc_base_addr",
        "arch/arm/mach-omap2/hsmmc.c:omap_hsmmc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224606464,
      "name": "omap_hwmod_lookup",
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
struct omap_hwmod * omap_hwmod_lookup(const char * name)
```
</details>
</li>
</ul>
