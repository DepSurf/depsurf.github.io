# Function: <code>of_clk_del_provider</code>

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
void of_clk_del_provider(struct device_node * np)
```

```json
{
  "name": "of_clk_del_provider",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497743976,
      "name": "of_clk_del_provider",
      "external": true,
      "loc": "drivers/clk/clk.c:4421",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_of_clk_release_provider",
        "drivers/clk/clk.c:of_clk_add_hw_provider",
        "drivers/clk/clk.c:of_clk_add_provider",
        "drivers/clk/clk-fixed-factor.c:of_fixed_factor_clk_remove",
        "drivers/clk/clk-fixed-rate.c:of_fixed_clk_remove",
        "drivers/clk/clk-fixed-mmio.c:of_fixed_mmio_clk_remove",
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_clk_remove",
        "drivers/clk/mediatek/clk-mt7622-aud.c:clk_mt7622_audiosys_init",
        "drivers/clk/mediatek/clk-mt8183-audio.c:clk_mt8183_audio_probe",
        "drivers/clk/mvebu/armada-37xx-xtal.c:armada_3700_xtal_clock_remove",
        "drivers/clk/mvebu/armada-37xx-tbg.c:armada_3700_tbg_clock_remove",
        "drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_remove",
        "drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_remove",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_probe",
        "drivers/clk/sunxi/clk-factors.c:sunxi_factors_unregister",
        "drivers/clk/sunxi/clk-sunxi.c:sunxi_divider_clk_setup",
        "drivers/clk/sunxi/clk-a10-ve.c:sun4i_ve_clk_setup",
        "drivers/clk/sunxi/clk-sun4i-display.c:sun4i_a10_display_init",
        "drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_a80_mmc_config_clk_probe",
        "drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_a80_mmc_config_clk_probe",
        "drivers/clk/sunxi-ng/ccu_common.c:sunxi_ccu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497743976,
      "name": "of_clk_del_provider",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void of_clk_del_provider(struct device_node * np)
```

```json
{
  "name": "of_clk_del_provider",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230567568,
      "name": "of_clk_del_provider",
      "external": true,
      "loc": "drivers/clk/clk.c:4421",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_of_clk_release_provider",
        "drivers/clk/clk.c:of_clk_add_hw_provider",
        "drivers/clk/clk.c:of_clk_add_provider",
        "drivers/clk/clk-fixed-factor.c:of_fixed_factor_clk_remove",
        "drivers/clk/clk-fixed-rate.c:of_fixed_clk_remove",
        "drivers/clk/clk-fixed-mmio.c:of_fixed_mmio_clk_remove",
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_clk_remove",
        "drivers/clk/mediatek/clk-mt7622-aud.c:clk_mt7622_audiosys_init",
        "drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_remove",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_probe",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_unregister",
        "drivers/clk/uniphier/clk-uniphier-core.c:uniphier_clk_remove",
        "drivers/net/ethernet/ti/cpts.c:cpts_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230567568,
      "name": "of_clk_del_provider",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void of_clk_del_provider(struct device_node * np)
```

```json
{
  "name": "of_clk_del_provider",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275889550,
      "name": "of_clk_del_provider",
      "external": true,
      "loc": "drivers/clk/clk.c:4421",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_of_clk_release_provider",
        "drivers/clk/clk.c:of_clk_add_hw_provider",
        "drivers/clk/clk.c:of_clk_add_provider",
        "drivers/clk/clk-fixed-factor.c:of_fixed_factor_clk_remove",
        "drivers/clk/clk-fixed-rate.c:of_fixed_clk_remove",
        "drivers/clk/clk-fixed-mmio.c:of_fixed_mmio_clk_remove",
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_clk_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275889550,
      "name": "of_clk_del_provider",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void of_clk_del_provider(struct device_node * np)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void of_clk_del_provider(struct device_node * np)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void of_clk_del_provider(struct device_node * np)
```
</details>
</li>
</ul>
