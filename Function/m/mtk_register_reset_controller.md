# Function: <code>mtk_register_reset_controller</code>

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
void mtk_register_reset_controller(struct device_node * np, unsigned int num_regs, int regofs)
```

```json
{
  "name": "mtk_register_reset_controller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497902384,
      "name": "mtk_register_reset_controller",
      "external": true,
      "loc": "drivers/clk/mediatek/reset.c:127",
      "file": "drivers/clk/mediatek/reset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/mediatek/clk-mt2712.c:clk_mt2712_peri_probe",
        "drivers/clk/mediatek/clk-mt2712.c:clk_mt2712_infra_probe",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_pericfg_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_infrasys_init",
        "drivers/clk/mediatek/clk-mt7622-eth.c:clk_mt7622_ethsys_init",
        "drivers/clk/mediatek/clk-mt7622-hif.c:clk_mt7622_pciesys_init",
        "drivers/clk/mediatek/clk-mt7622-hif.c:clk_mt7622_ssusbsys_init",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_pericfg_init",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_infrasys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497902384,
      "name": "mtk_register_reset_controller",
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void mtk_register_reset_controller(struct device_node * np, unsigned int num_regs, int regofs)
```

```json
{
  "name": "mtk_register_reset_controller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230663772,
      "name": "mtk_register_reset_controller",
      "external": true,
      "loc": "drivers/clk/mediatek/reset.c:127",
      "file": "drivers/clk/mediatek/reset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/mediatek/clk-mt7622.c:mtk_pericfg_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_infrasys_init",
        "drivers/clk/mediatek/clk-mt7622-eth.c:clk_mt7622_ethsys_init",
        "drivers/clk/mediatek/clk-mt7622-hif.c:clk_mt7622_pciesys_init",
        "drivers/clk/mediatek/clk-mt7622-hif.c:clk_mt7622_ssusbsys_init",
        "drivers/clk/mediatek/clk-mt7629-eth.c:clk_mt7629_ethsys_init",
        "drivers/clk/mediatek/clk-mt7629-hif.c:clk_mt7629_pciesys_init",
        "drivers/clk/mediatek/clk-mt7629-hif.c:clk_mt7629_ssusbsys_init",
        "drivers/clk/mediatek/clk-mt8135.c:mtk_pericfg_init",
        "drivers/clk/mediatek/clk-mt8135.c:mtk_infrasys_init",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_pericfg_init",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_infrasys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230663772,
      "name": "mtk_register_reset_controller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void mtk_register_reset_controller(struct device_node * np, unsigned int num_regs, int regofs)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void mtk_register_reset_controller(struct device_node * np, unsigned int num_regs, int regofs)
```
</details>
</li>
</ul>
