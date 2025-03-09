# Function: <code>mtk_rmw</code>

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
void mtk_rmw(struct mtk_pinctrl * pctl, u8 i, u32 reg, u32 mask, u32 set)
```

```json
{
  "name": "mtk_rmw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496688424,
      "name": "mtk_rmw",
      "external": true,
      "loc": "drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:55",
      "file": "drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_set_value",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_set_value",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_set_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496688424,
      "name": "mtk_rmw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void mtk_rmw(struct mtk_pinctrl * pctl, u8 i, u32 reg, u32 mask, u32 set)
```

```json
{
  "name": "mtk_rmw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229989496,
      "name": "mtk_rmw",
      "external": true,
      "loc": "drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:55",
      "file": "drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_set_value",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_set_value",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_set_value"
      ],
      "caller_func": [
        "drivers/pinctrl/mediatek/pinctrl-mt7623.c:mt7623_pinctrl_probe",
        "drivers/pinctrl/mediatek/pinctrl-mt7623.c:mt7623_pinctrl_probe",
        "drivers/pinctrl/mediatek/pinctrl-mt7623.c:mt7623_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229989312,
      "name": "mtk_rmw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void mtk_rmw(struct mtk_pinctrl * pctl, u8 i, u32 reg, u32 mask, u32 set)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void mtk_rmw(struct mtk_pinctrl * pctl, u8 i, u32 reg, u32 mask, u32 set)
```
</details>
</li>
</ul>
