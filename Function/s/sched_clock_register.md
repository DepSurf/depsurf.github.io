# Function: <code>sched_clock_register</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sched_clock_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_clock_register",
      "external": false,
      "loc": "include/linux/sched_clock.h:16",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
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
void sched_clock_register(u64 (*)() read, int bits, long unsigned int rate)
```

```json
{
  "name": "sched_clock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336510902640,
      "name": "sched_clock_register",
      "external": true,
      "loc": "kernel/time/sched_clock.c:168",
      "file": "kernel/time/sched_clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/sched_clock.c:generic_sched_clock_init",
        "drivers/clocksource/timer-rockchip.c:rk_timer_init",
        "drivers/clocksource/timer-mediatek.c:mtk_gpt_init",
        "drivers/clocksource/timer-owl.c:owl_timer_init",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_common_init",
        "drivers/clocksource/timer-sp804.c:__sp804_clocksource_and_sched_clock_init",
        "drivers/clocksource/timer-versatile.c:versatile_sched_clock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336510902640,
      "name": "sched_clock_register",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 496
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
void sched_clock_register(u64 (*)() read, int bits, long unsigned int rate)
```

```json
{
  "name": "sched_clock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243389520,
      "name": "sched_clock_register",
      "external": true,
      "loc": "kernel/time/sched_clock.c:168",
      "file": "kernel/time/sched_clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-omap2/timer.c:__omap_sync32k_timer_init",
        "arch/arm/plat-omap/counter_32k.c:omap_init_clocksource_32k",
        "kernel/time/sched_clock.c:generic_sched_clock_init",
        "drivers/clocksource/renesas-ostm.c:ostm_init",
        "drivers/clocksource/dw_apb_timer_of.c:dw_apb_timer_init",
        "drivers/clocksource/timer-rockchip.c:rk_timer_init",
        "drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_common_init",
        "drivers/clocksource/timer-orion.c:orion_timer_init",
        "drivers/clocksource/timer-meson6.c:meson6_timer_init",
        "drivers/clocksource/timer-tegra.c:tegra_init_timer",
        "drivers/clocksource/exynos_mct.c:mct_init_dt",
        "drivers/clocksource/timer-qcom.c:msm_dt_timer_init",
        "drivers/clocksource/timer-mediatek.c:mtk_gpt_init",
        "drivers/clocksource/timer-ti-32k.c:ti_32k_timer_init",
        "drivers/clocksource/timer-owl.c:owl_timer_init",
        "drivers/clocksource/timer-milbeaut.c:mlb_timer_init",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_common_init",
        "drivers/clocksource/arm_global_timer.c:global_timer_of_register",
        "drivers/clocksource/timer-sp804.c:__sp804_clocksource_and_sched_clock_init",
        "drivers/clocksource/timer-versatile.c:versatile_sched_clock_init",
        "drivers/clocksource/timer-imx-gpt.c:_mxc_timer_init",
        "drivers/clocksource/timer-imx-tpm.c:tpm_timer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243389520,
      "name": "sched_clock_register",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 700
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
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void sched_clock_register(u64 (*)() read, int bits, long unsigned int rate)
```

```json
{
  "name": "sched_clock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270640696,
      "name": "sched_clock_register",
      "external": true,
      "loc": "kernel/time/sched_clock.c:168",
      "file": "kernel/time/sched_clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/sched_clock.c:generic_sched_clock_init",
        "drivers/clocksource/timer-riscv.c:riscv_timer_init_dt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270640696,
      "name": "sched_clock_register",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 436
    }
  ]
}
```
</details>
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
void sched_clock_register(u64 (*)() read, int bits, long unsigned int rate)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void sched_clock_register(u64 (*)() read, int bits, long unsigned int rate)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void sched_clock_register(u64 (*)() read, int bits, long unsigned int rate)
```
</details>
</li>
</ul>
