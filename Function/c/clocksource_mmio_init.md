# Function: <code>clocksource_mmio_init</code>

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
int clocksource_mmio_init(void * base, const char * name, long unsigned int hz, int rating, unsigned int bits, u64 (*)(struct clocksource *) read)
```

```json
{
  "name": "clocksource_mmio_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511291860,
      "name": "clocksource_mmio_init",
      "external": true,
      "loc": "drivers/clocksource/mmio.c:49",
      "file": "drivers/clocksource/mmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/timer-rockchip.c:rk_timer_init",
        "drivers/clocksource/timer-mediatek.c:mtk_gpt_init",
        "drivers/clocksource/timer-owl.c:owl_timer_init",
        "drivers/clocksource/timer-sp804.c:__sp804_clocksource_and_sched_clock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511291860,
      "name": "clocksource_mmio_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int clocksource_mmio_init(void * base, const char * name, long unsigned int hz, int rating, unsigned int bits, u64 (*)(struct clocksource *) read)
```

```json
{
  "name": "clocksource_mmio_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243944688,
      "name": "clocksource_mmio_init",
      "external": true,
      "loc": "drivers/clocksource/mmio.c:49",
      "file": "drivers/clocksource/mmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/plat-omap/counter_32k.c:omap_init_clocksource_32k",
        "drivers/clocksource/renesas-ostm.c:ostm_init",
        "drivers/clocksource/timer-rockchip.c:rk_timer_init",
        "drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_common_init",
        "drivers/clocksource/timer-orion.c:orion_timer_init",
        "drivers/clocksource/timer-meson6.c:meson6_timer_init",
        "drivers/clocksource/timer-tegra.c:tegra_init_timer",
        "drivers/clocksource/timer-mediatek.c:mtk_gpt_init",
        "drivers/clocksource/timer-owl.c:owl_timer_init",
        "drivers/clocksource/timer-milbeaut.c:mlb_timer_init",
        "drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_init",
        "drivers/clocksource/timer-sp804.c:__sp804_clocksource_and_sched_clock_init",
        "drivers/clocksource/timer-imx-gpt.c:_mxc_timer_init",
        "drivers/clocksource/timer-imx-tpm.c:tpm_timer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243944688,
      "name": "clocksource_mmio_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int clocksource_mmio_init(void * base, const char * name, long unsigned int hz, int rating, unsigned int bits, u64 (*)(struct clocksource *) read)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int clocksource_mmio_init(void * base, const char * name, long unsigned int hz, int rating, unsigned int bits, u64 (*)(struct clocksource *) read)
```
</details>
</li>
</ul>
