# Function: <code>clk_pll_recalc_rate</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
long unsigned int clk_pll_recalc_rate(struct clk_hw * hw, long unsigned int parent_rate)
```

```json
{
  "name": "clk_pll_recalc_rate",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497838576,
      "name": "clk_pll_recalc_rate",
      "external": false,
      "loc": "drivers/clk/imx/clk-frac-pll.c:95",
      "file": "drivers/clk/imx/clk-frac-pll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497957008,
      "name": "clk_pll_recalc_rate",
      "external": false,
      "loc": "drivers/clk/socfpga/clk-pll-s10.c:30",
      "file": "drivers/clk/socfpga/clk-pll-s10.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497838576,
      "name": "clk_pll_recalc_rate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446603336497957008,
      "name": "clk_pll_recalc_rate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
long unsigned int clk_pll_recalc_rate(struct clk_hw * hwclk, long unsigned int parent_rate)
```

```json
{
  "name": "clk_pll_recalc_rate",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230614564,
      "name": "clk_pll_recalc_rate",
      "external": false,
      "loc": "drivers/clk/clk-highbank.c:93",
      "file": "drivers/clk/clk-highbank.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230641432,
      "name": "clk_pll_recalc_rate",
      "external": false,
      "loc": "drivers/clk/imx/clk-frac-pll.c:95",
      "file": "drivers/clk/imx/clk-frac-pll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230732192,
      "name": "clk_pll_recalc_rate",
      "external": false,
      "loc": "drivers/clk/tegra/clk-pll.c:840",
      "file": "drivers/clk/tegra/clk-pll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230614564,
      "name": "clk_pll_recalc_rate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 3230641432,
      "name": "clk_pll_recalc_rate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 3230732192,
      "name": "clk_pll_recalc_rate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
long unsigned int clk_pll_recalc_rate(struct clk_hw * hw, long unsigned int parent_rate)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
long unsigned int clk_pll_recalc_rate(struct clk_hw * hwclk, long unsigned int parent_rate)
```
</details>
</li>
</ul>
