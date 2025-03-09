# Function: <code>zynqmp_pm_get_eemi_ops</code>

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
const struct zynqmp_eemi_ops * zynqmp_pm_get_eemi_ops()
```

```json
{
  "name": "zynqmp_pm_get_eemi_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501573080,
      "name": "zynqmp_pm_get_eemi_ops",
      "external": true,
      "loc": "drivers/firmware/xilinx/zynqmp.c:697",
      "file": "drivers/firmware/xilinx/zynqmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/zynqmp/pll.c:zynqmp_pll_disable",
        "drivers/clk/zynqmp/pll.c:zynqmp_pll_enable",
        "drivers/clk/zynqmp/pll.c:zynqmp_pll_is_enabled",
        "drivers/clk/zynqmp/pll.c:zynqmp_pll_set_rate",
        "drivers/clk/zynqmp/pll.c:zynqmp_pll_set_rate",
        "drivers/clk/zynqmp/pll.c:zynqmp_pll_recalc_rate",
        "drivers/clk/zynqmp/pll.c:zynqmp_pll_recalc_rate",
        "drivers/clk/zynqmp/clk-gate-zynqmp.c:zynqmp_clk_gate_is_enabled",
        "drivers/clk/zynqmp/clk-gate-zynqmp.c:zynqmp_clk_gate_disable",
        "drivers/clk/zynqmp/clk-gate-zynqmp.c:zynqmp_clk_gate_enable",
        "drivers/clk/zynqmp/divider.c:zynqmp_clk_divider_set_rate",
        "drivers/clk/zynqmp/divider.c:zynqmp_clk_divider_round_rate",
        "drivers/clk/zynqmp/divider.c:zynqmp_clk_divider_recalc_rate",
        "drivers/clk/zynqmp/clk-mux-zynqmp.c:zynqmp_clk_mux_set_parent",
        "drivers/clk/zynqmp/clk-mux-zynqmp.c:zynqmp_clk_mux_get_parent",
        "drivers/clk/zynqmp/clkc.c:zynqmp_clock_probe",
        "drivers/soc/xilinx/zynqmp_power.c:zynqmp_pm_probe",
        "drivers/soc/xilinx/zynqmp_pm_domains.c:zynqmp_gpd_probe",
        "drivers/reset/reset-zynqmp.c:zynqmp_reset_probe",
        "drivers/nvmem/zynqmp_nvmem.c:zynqmp_nvmem_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501573080,
      "name": "zynqmp_pm_get_eemi_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
const struct zynqmp_eemi_ops * zynqmp_pm_get_eemi_ops()
```
</details>
</li>
</ul>
