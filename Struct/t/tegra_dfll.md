# Struct: <code>tegra_dfll</code>

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
struct tegra_dfll {
    struct device * dev;
    struct tegra_dfll_soc_data * soc;
    void * base;
    void * i2c_base;
    void * i2c_controller_base;
    void * lut_base;
    struct regulator * vdd_reg;
    struct clk * soc_clk;
    struct clk * ref_clk;
    struct clk * i2c_clk;
    struct clk * dfll_clk;
    struct reset_control * dvco_rst;
    long unsigned int ref_rate;
    long unsigned int i2c_clk_rate;
    long unsigned int dvco_rate_min;
    enum dfll_ctrl_mode mode;
    enum dfll_tune_range tune_range;
    struct dentry * debugfs_dir;
    struct clk_hw dfll_clk_hw;
    const char * output_clock_name;
    struct dfll_rate_req last_req;
    long unsigned int last_unrounded_rate;
    u32 droop_ctrl;
    u32 sample_rate;
    u32 force_mode;
    u32 cf;
    u32 ci;
    u32 cg;
    bool cg_scale;
    u32 i2c_fs_rate;
    u32 i2c_reg;
    u32 i2c_slave_addr;
    unsigned int[33] lut;
    long unsigned int[33] lut_uv;
    int lut_size;
    u8 lut_bottom;
    u8 lut_min;
    u8 lut_max;
    u8 lut_safe;
    enum tegra_dfll_pmu_if pmu_if;
    long unsigned int pwm_rate;
    struct pinctrl * pwm_pin;
    struct pinctrl_state * pwm_enable_state;
    struct pinctrl_state * pwm_disable_state;
    u32 reg_init_uV;
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
struct tegra_dfll {
    struct device * dev;
    struct tegra_dfll_soc_data * soc;
    void * base;
    void * i2c_base;
    void * i2c_controller_base;
    void * lut_base;
    struct regulator * vdd_reg;
    struct clk * soc_clk;
    struct clk * ref_clk;
    struct clk * i2c_clk;
    struct clk * dfll_clk;
    struct reset_control * dvco_rst;
    long unsigned int ref_rate;
    long unsigned int i2c_clk_rate;
    long unsigned int dvco_rate_min;
    enum dfll_ctrl_mode mode;
    enum dfll_tune_range tune_range;
    struct dentry * debugfs_dir;
    struct clk_hw dfll_clk_hw;
    const char * output_clock_name;
    struct dfll_rate_req last_req;
    long unsigned int last_unrounded_rate;
    u32 droop_ctrl;
    u32 sample_rate;
    u32 force_mode;
    u32 cf;
    u32 ci;
    u32 cg;
    bool cg_scale;
    u32 i2c_fs_rate;
    u32 i2c_reg;
    u32 i2c_slave_addr;
    unsigned int[33] lut;
    long unsigned int[33] lut_uv;
    int lut_size;
    u8 lut_bottom;
    u8 lut_min;
    u8 lut_max;
    u8 lut_safe;
    enum tegra_dfll_pmu_if pmu_if;
    long unsigned int pwm_rate;
    struct pinctrl * pwm_pin;
    struct pinctrl_state * pwm_enable_state;
    struct pinctrl_state * pwm_disable_state;
    u32 reg_init_uV;
}
```
</details>
</li>
</ul>
