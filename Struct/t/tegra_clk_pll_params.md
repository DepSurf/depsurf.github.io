# Struct: <code>tegra_clk_pll_params</code>

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
struct tegra_clk_pll_params {
    long unsigned int input_min;
    long unsigned int input_max;
    long unsigned int cf_min;
    long unsigned int cf_max;
    long unsigned int vco_min;
    long unsigned int vco_max;
    u32 base_reg;
    u32 misc_reg;
    u32 lock_reg;
    u32 lock_mask;
    u32 lock_enable_bit_idx;
    u32 iddq_reg;
    u32 iddq_bit_idx;
    u32 reset_reg;
    u32 reset_bit_idx;
    u32 sdm_din_reg;
    u32 sdm_din_mask;
    u32 sdm_ctrl_reg;
    u32 sdm_ctrl_en_mask;
    u32 ssc_ctrl_reg;
    u32 ssc_ctrl_en_mask;
    u32 aux_reg;
    u32 dyn_ramp_reg;
    u32[6] ext_misc_reg;
    u32 pmc_divnm_reg;
    u32 pmc_divp_reg;
    u32 flags;
    int stepa_shift;
    int stepb_shift;
    int lock_delay;
    int max_p;
    bool defaults_set;
    const struct pdiv_map * pdiv_tohw;
    struct div_nmp * div_nmp;
    struct tegra_clk_pll_freq_table * freq_table;
    long unsigned int fixed_rate;
    u16 mdiv_default;
    u32 (*)(u32, u32 *) round_p_to_pdiv;
    void (*)(struct tegra_clk_pll_freq_table *) set_gain;
    int (*)(struct clk_hw *, struct tegra_clk_pll_freq_table *, long unsigned int, long unsigned int) calc_rate;
    long unsigned int (*)(struct tegra_clk_pll_params *, long unsigned int) adjust_vco;
    void (*)(struct tegra_clk_pll *) set_defaults;
    int (*)(struct tegra_clk_pll *, struct tegra_clk_pll_freq_table *) dyn_ramp;
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
struct tegra_clk_pll_params {
    long unsigned int input_min;
    long unsigned int input_max;
    long unsigned int cf_min;
    long unsigned int cf_max;
    long unsigned int vco_min;
    long unsigned int vco_max;
    u32 base_reg;
    u32 misc_reg;
    u32 lock_reg;
    u32 lock_mask;
    u32 lock_enable_bit_idx;
    u32 iddq_reg;
    u32 iddq_bit_idx;
    u32 reset_reg;
    u32 reset_bit_idx;
    u32 sdm_din_reg;
    u32 sdm_din_mask;
    u32 sdm_ctrl_reg;
    u32 sdm_ctrl_en_mask;
    u32 ssc_ctrl_reg;
    u32 ssc_ctrl_en_mask;
    u32 aux_reg;
    u32 dyn_ramp_reg;
    u32[6] ext_misc_reg;
    u32 pmc_divnm_reg;
    u32 pmc_divp_reg;
    u32 flags;
    int stepa_shift;
    int stepb_shift;
    int lock_delay;
    int max_p;
    bool defaults_set;
    const struct pdiv_map * pdiv_tohw;
    struct div_nmp * div_nmp;
    struct tegra_clk_pll_freq_table * freq_table;
    long unsigned int fixed_rate;
    u16 mdiv_default;
    u32 (*)(u32, u32 *) round_p_to_pdiv;
    void (*)(struct tegra_clk_pll_freq_table *) set_gain;
    int (*)(struct clk_hw *, struct tegra_clk_pll_freq_table *, long unsigned int, long unsigned int) calc_rate;
    long unsigned int (*)(struct tegra_clk_pll_params *, long unsigned int) adjust_vco;
    void (*)(struct tegra_clk_pll *) set_defaults;
    int (*)(struct tegra_clk_pll *, struct tegra_clk_pll_freq_table *) dyn_ramp;
}
```
</details>
</li>
</ul>
