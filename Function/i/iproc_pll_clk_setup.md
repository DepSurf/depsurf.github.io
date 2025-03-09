# Function: <code>iproc_pll_clk_setup</code>

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
void iproc_pll_clk_setup(struct device_node * node, const struct iproc_pll_ctrl * pll_ctrl, const struct iproc_pll_vco_param * vco, unsigned int num_vco_entries, const struct iproc_clk_ctrl * clk_ctrl, unsigned int num_clks)
```

```json
{
  "name": "iproc_pll_clk_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497809000,
      "name": "iproc_pll_clk_setup",
      "external": true,
      "loc": "drivers/clk/bcm/clk-iproc-pll.c:725",
      "file": "drivers/clk/bcm/clk-iproc-pll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/bcm/clk-ns2.c:ns2_lcpll_ports_clk_init",
        "drivers/clk/bcm/clk-ns2.c:ns2_lcpll_ddr_clk_init",
        "drivers/clk/bcm/clk-ns2.c:ns2_genpll_sw_clk_init",
        "drivers/clk/bcm/clk-ns2.c:ns2_genpll_scr_clk_init",
        "drivers/clk/bcm/clk-sr.c:sr_lcpll_pcie_clk_init",
        "drivers/clk/bcm/clk-sr.c:sr_lcpll1_clk_init",
        "drivers/clk/bcm/clk-sr.c:sr_lcpll0_clk_init",
        "drivers/clk/bcm/clk-sr.c:sr_genpll5_clk_init",
        "drivers/clk/bcm/clk-sr.c:sr_genpll4_clk_init",
        "drivers/clk/bcm/clk-sr.c:sr_genpll3_clk_init",
        "drivers/clk/bcm/clk-sr.c:sr_genpll2_clk_init",
        "drivers/clk/bcm/clk-sr.c:sr_genpll0_clk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497809000,
      "name": "iproc_pll_clk_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 956
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
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
void iproc_pll_clk_setup(struct device_node * node, const struct iproc_pll_ctrl * pll_ctrl, const struct iproc_pll_vco_param * vco, unsigned int num_vco_entries, const struct iproc_clk_ctrl * clk_ctrl, unsigned int num_clks)
```
</details>
</li>
</ul>
