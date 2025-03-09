# Function: <code>rockchip_rk3399_pll_set_params</code>

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
int rockchip_rk3399_pll_set_params(struct rockchip_clk_pll * pll, const struct rockchip_pll_rate_table * rate)
```

```json
{
  "name": "rockchip_rk3399_pll_set_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497944544,
      "name": "rockchip_rk3399_pll_set_params",
      "external": false,
      "loc": "drivers/clk/rockchip/clk-pll.c:655",
      "file": "drivers/clk/rockchip/clk-pll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_init",
        "drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_set_rate",
        "drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_set_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497944544,
      "name": "rockchip_rk3399_pll_set_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
int rockchip_rk3399_pll_set_params(struct rockchip_clk_pll * pll, const struct rockchip_pll_rate_table * rate)
```

```json
{
  "name": "rockchip_rk3399_pll_set_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230688680,
      "name": "rockchip_rk3399_pll_set_params",
      "external": false,
      "loc": "drivers/clk/rockchip/clk-pll.c:655",
      "file": "drivers/clk/rockchip/clk-pll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_init",
        "drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_set_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230688680,
      "name": "rockchip_rk3399_pll_set_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
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
int rockchip_rk3399_pll_set_params(struct rockchip_clk_pll * pll, const struct rockchip_pll_rate_table * rate)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int rockchip_rk3399_pll_set_params(struct rockchip_clk_pll * pll, const struct rockchip_pll_rate_table * rate)
```
</details>
</li>
</ul>
