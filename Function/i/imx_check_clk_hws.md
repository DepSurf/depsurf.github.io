# Function: <code>imx_check_clk_hws</code>

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
void imx_check_clk_hws(struct clk_hw * * clks, unsigned int count)
```

```json
{
  "name": "imx_check_clk_hws",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497831352,
      "name": "imx_check_clk_hws",
      "external": true,
      "loc": "drivers/clk/imx/clk.c:45",
      "file": "drivers/clk/imx/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497831352,
      "name": "imx_check_clk_hws",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void imx_check_clk_hws(struct clk_hw * * clks, unsigned int count)
```

```json
{
  "name": "imx_check_clk_hws",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230635924,
      "name": "imx_check_clk_hws",
      "external": true,
      "loc": "drivers/clk/imx/clk.c:45",
      "file": "drivers/clk/imx/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6sl.c:imx6sl_clocks_init",
        "drivers/clk/imx/clk-imx6sll.c:imx6sll_clocks_init",
        "drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init",
        "drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init",
        "drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init",
        "drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_smc1_init",
        "drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_pcc3_init",
        "drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_pcc2_init",
        "drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_scg1_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230635924,
      "name": "imx_check_clk_hws",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void imx_check_clk_hws(struct clk_hw * * clks, unsigned int count)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void imx_check_clk_hws(struct clk_hw * * clks, unsigned int count)
```
</details>
</li>
</ul>
