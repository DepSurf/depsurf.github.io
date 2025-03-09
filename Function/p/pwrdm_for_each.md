# Function: <code>pwrdm_for_each</code>

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
int pwrdm_for_each(int (*)(struct powerdomain *, void *) fn, void * user)
```

```json
{
  "name": "pwrdm_for_each",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224659256,
      "name": "pwrdm_for_each",
      "external": true,
      "loc": "arch/arm/mach-omap2/powerdomain.c:437",
      "file": "arch/arm/mach-omap2/powerdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/powerdomain.c:pwrdms_lost_power",
        "arch/arm/mach-omap2/powerdomain.c:pwrdms_restore_context",
        "arch/arm/mach-omap2/powerdomain.c:pwrdms_save_context",
        "arch/arm/mach-omap2/powerdomain.c:pwrdm_post_transition",
        "arch/arm/mach-omap2/powerdomain.c:pwrdm_pre_transition"
      ],
      "caller_func": [
        "arch/arm/mach-omap2/pm34xx.c:omap3_pm_init",
        "arch/arm/mach-omap2/pm44xx.c:omap4_pm_init",
        "arch/arm/mach-omap2/pm-debug.c:__pm_dbg_init",
        "arch/arm/mach-omap2/pm-debug.c:pm_dbg_timers_show",
        "arch/arm/mach-omap2/pm-debug.c:pm_dbg_counters_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224653804,
      "name": "pwrdm_for_each",
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
int pwrdm_for_each(int (*)(struct powerdomain *, void *) fn, void * user)
```
</details>
</li>
</ul>
