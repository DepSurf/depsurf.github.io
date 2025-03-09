# Struct: <code>samsung_cmu_info</code>

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
struct samsung_cmu_info {
    const struct samsung_pll_clock * pll_clks;
    unsigned int nr_pll_clks;
    const struct samsung_mux_clock * mux_clks;
    unsigned int nr_mux_clks;
    const struct samsung_div_clock * div_clks;
    unsigned int nr_div_clks;
    const struct samsung_gate_clock * gate_clks;
    unsigned int nr_gate_clks;
    const struct samsung_fixed_rate_clock * fixed_clks;
    unsigned int nr_fixed_clks;
    const struct samsung_fixed_factor_clock * fixed_factor_clks;
    unsigned int nr_fixed_factor_clks;
    unsigned int nr_clk_ids;
    const long unsigned int * clk_regs;
    unsigned int nr_clk_regs;
    const struct samsung_clk_reg_dump * suspend_regs;
    unsigned int nr_suspend_regs;
    const char * clk_name;
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
struct samsung_cmu_info {
    const struct samsung_pll_clock * pll_clks;
    unsigned int nr_pll_clks;
    const struct samsung_mux_clock * mux_clks;
    unsigned int nr_mux_clks;
    const struct samsung_div_clock * div_clks;
    unsigned int nr_div_clks;
    const struct samsung_gate_clock * gate_clks;
    unsigned int nr_gate_clks;
    const struct samsung_fixed_rate_clock * fixed_clks;
    unsigned int nr_fixed_clks;
    const struct samsung_fixed_factor_clock * fixed_factor_clks;
    unsigned int nr_fixed_factor_clks;
    unsigned int nr_clk_ids;
    const long unsigned int * clk_regs;
    unsigned int nr_clk_regs;
    const struct samsung_clk_reg_dump * suspend_regs;
    unsigned int nr_suspend_regs;
    const char * clk_name;
}
```
</details>
</li>
</ul>
