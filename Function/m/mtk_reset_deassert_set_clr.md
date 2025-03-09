# Function: <code>mtk_reset_deassert_set_clr</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int mtk_reset_deassert_set_clr(struct reset_controller_dev * rcdev, long unsigned int id)
```

```json
{
  "name": "mtk_reset_deassert_set_clr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497902348,
      "name": "mtk_reset_deassert_set_clr",
      "external": false,
      "loc": "drivers/clk/mediatek/reset.c:31",
      "file": "drivers/clk/mediatek/reset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/mediatek/reset.c:mtk_reset_set_clr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497902152,
      "name": "mtk_reset_deassert_set_clr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
int mtk_reset_deassert_set_clr(struct reset_controller_dev * rcdev, long unsigned int id)
```

```json
{
  "name": "mtk_reset_deassert_set_clr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230663744,
      "name": "mtk_reset_deassert_set_clr",
      "external": false,
      "loc": "drivers/clk/mediatek/reset.c:31",
      "file": "drivers/clk/mediatek/reset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/mediatek/reset.c:mtk_reset_set_clr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230663580,
      "name": "mtk_reset_deassert_set_clr",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int mtk_reset_deassert_set_clr(struct reset_controller_dev * rcdev, long unsigned int id)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int mtk_reset_deassert_set_clr(struct reset_controller_dev * rcdev, long unsigned int id)
```
</details>
</li>
</ul>
