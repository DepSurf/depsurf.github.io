# Function: <code>mtk_clk_register_fixed_clks</code>

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
void mtk_clk_register_fixed_clks(const struct mtk_fixed_clk * clks, int num, struct clk_onecell_data * clk_data)
```

```json
{
  "name": "mtk_clk_register_fixed_clks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497895248,
      "name": "mtk_clk_register_fixed_clks",
      "external": true,
      "loc": "drivers/clk/mediatek/clk-mtk.c:45",
      "file": "drivers/clk/mediatek/clk-mtk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/mediatek/clk-mt6779.c:clk_mt6779_top_probe",
        "drivers/clk/mediatek/clk-mt2712.c:clk_mt2712_top_probe",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt8183.c:clk_mt8183_top_probe",
        "drivers/clk/mediatek/clk-mt8516.c:mtk_topckgen_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497895248,
      "name": "mtk_clk_register_fixed_clks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void mtk_clk_register_fixed_clks(const struct mtk_fixed_clk * clks, int num, struct clk_onecell_data * clk_data)
```

```json
{
  "name": "mtk_clk_register_fixed_clks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230657032,
      "name": "mtk_clk_register_fixed_clks",
      "external": true,
      "loc": "drivers/clk/mediatek/clk-mtk.c:45",
      "file": "drivers/clk/mediatek/clk-mtk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt7629.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt8516.c:mtk_topckgen_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230657032,
      "name": "mtk_clk_register_fixed_clks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void mtk_clk_register_fixed_clks(const struct mtk_fixed_clk * clks, int num, struct clk_onecell_data * clk_data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void mtk_clk_register_fixed_clks(const struct mtk_fixed_clk * clks, int num, struct clk_onecell_data * clk_data)
```
</details>
</li>
</ul>
