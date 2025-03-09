# Function: <code>timer_probe</code>

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
void timer_probe()
```

```json
{
  "name": "timer_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511291392,
      "name": "timer_probe",
      "external": true,
      "loc": "drivers/clocksource/timer-probe.c:16",
      "file": "drivers/clocksource/timer-probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/time.c:time_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511291392,
      "name": "timer_probe",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void timer_probe()
```

```json
{
  "name": "timer_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243943412,
      "name": "timer_probe",
      "external": true,
      "loc": "drivers/clocksource/timer-probe.c:16",
      "file": "drivers/clocksource/timer-probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/time.c:time_init",
        "arch/arm/mach-mediatek/mediatek.c:mediatek_timer_init",
        "arch/arm/mach-omap2/timer.c:omap5_realtime_timer_init",
        "arch/arm/mach-omap2/timer.c:omap4_local_timer_init",
        "arch/arm/mach-omap2/timer.c:omap3_gptimer_timer_init",
        "arch/arm/mach-omap2/timer.c:omap3_secure_sync32k_timer_init",
        "arch/arm/mach-omap2/timer.c:omap_init_time",
        "arch/arm/mach-rockchip/rockchip.c:rockchip_timer_init",
        "arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_timer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243943412,
      "name": "timer_probe",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void timer_probe()
```

```json
{
  "name": "timer_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270836872,
      "name": "timer_probe",
      "external": true,
      "loc": "drivers/clocksource/timer-probe.c:16",
      "file": "drivers/clocksource/timer-probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/time.c:time_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270836872,
      "name": "timer_probe",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void timer_probe()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void timer_probe()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void timer_probe()
```
</details>
</li>
</ul>
