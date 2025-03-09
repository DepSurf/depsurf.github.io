# Function: <code>tegra_lookup_dt_id</code>

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
struct clk * * tegra_lookup_dt_id(int clk_id, struct tegra_clk * tegra_clk)
```

```json
{
  "name": "tegra_lookup_dt_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243795260,
      "name": "tegra_lookup_dt_id",
      "external": true,
      "loc": "drivers/clk/tegra/clk.c:340",
      "file": "drivers/clk/tegra/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/tegra/clk-tegra-audio.c:tegra_audio_clk_init",
        "drivers/clk/tegra/clk-tegra-audio.c:tegra_audio_clk_init",
        "drivers/clk/tegra/clk-tegra-audio.c:tegra_audio_clk_init",
        "drivers/clk/tegra/clk-tegra-audio.c:tegra_audio_clk_init",
        "drivers/clk/tegra/clk-tegra-periph.c:tegra_periph_clk_init",
        "drivers/clk/tegra/clk-tegra-periph.c:tegra_periph_clk_init",
        "drivers/clk/tegra/clk-tegra-periph.c:tegra_periph_clk_init",
        "drivers/clk/tegra/clk-tegra-periph.c:tegra_periph_clk_init",
        "drivers/clk/tegra/clk-tegra-periph.c:tegra_periph_clk_init",
        "drivers/clk/tegra/clk-tegra-periph.c:tegra_periph_clk_init",
        "drivers/clk/tegra/clk-tegra-periph.c:tegra_periph_clk_init",
        "drivers/clk/tegra/clk-tegra-periph.c:tegra_periph_clk_init",
        "drivers/clk/tegra/clk-tegra-periph.c:tegra_periph_clk_init",
        "drivers/clk/tegra/clk-tegra-pmc.c:tegra_pmc_clk_init",
        "drivers/clk/tegra/clk-tegra-pmc.c:tegra_pmc_clk_init",
        "drivers/clk/tegra/clk-tegra-pmc.c:tegra_pmc_clk_init",
        "drivers/clk/tegra/clk-tegra-fixed.c:tegra_fixed_clk_init",
        "drivers/clk/tegra/clk-tegra-fixed.c:tegra_fixed_clk_init",
        "drivers/clk/tegra/clk-tegra-fixed.c:tegra_fixed_clk_init",
        "drivers/clk/tegra/clk-tegra-fixed.c:tegra_osc_clk_init",
        "drivers/clk/tegra/clk-tegra-fixed.c:tegra_osc_clk_init",
        "drivers/clk/tegra/clk-tegra-super-gen4.c:tegra_super_clk_init",
        "drivers/clk/tegra/clk-tegra-super-gen4.c:tegra_super_clk_init",
        "drivers/clk/tegra/clk-tegra-super-gen4.c:tegra_super_clk_init",
        "drivers/clk/tegra/clk-tegra-super-gen4.c:tegra_super_clk_init",
        "drivers/clk/tegra/clk-tegra-super-gen4.c:tegra_super_clk_init",
        "drivers/clk/tegra/clk-tegra-super-gen4.c:tegra_super_clk_init",
        "drivers/clk/tegra/clk-tegra-super-gen4.c:tegra_super_clk_init",
        "drivers/clk/tegra/clk-tegra-super-gen4.c:tegra_super_clk_init",
        "drivers/clk/tegra/clk-tegra-super-gen4.c:tegra_super_clk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243795260,
      "name": "tegra_lookup_dt_id",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 60
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
struct clk * * tegra_lookup_dt_id(int clk_id, struct tegra_clk * tegra_clk)
```
</details>
</li>
</ul>
