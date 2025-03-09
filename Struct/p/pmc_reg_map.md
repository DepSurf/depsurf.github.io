# Struct: <code>pmc_reg_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pmc_reg_map {
    const struct pmc_bit_map * d3_sts_0;
    const struct pmc_bit_map * d3_sts_1;
    const struct pmc_bit_map * func_dis;
    const struct pmc_bit_map * func_dis_2;
    const struct pmc_bit_map * pss;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct pmc_reg_map {
    const struct pmc_bit_map * d3_sts_0;
    const struct pmc_bit_map * d3_sts_1;
    const struct pmc_bit_map * func_dis;
    const struct pmc_bit_map * func_dis_2;
    const struct pmc_bit_map * pss;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct pmc_reg_map {
    const struct pmc_bit_map * d3_sts_0;
    const struct pmc_bit_map * d3_sts_1;
    const struct pmc_bit_map * func_dis;
    const struct pmc_bit_map * func_dis_2;
    const struct pmc_bit_map * pss;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pmc_reg_map {
    const struct pmc_bit_map * pfear_sts;
    const struct pmc_bit_map * mphy_sts;
    const struct pmc_bit_map * pll_sts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct pmc_reg_map {
    const struct pmc_bit_map * pfear_sts;
    const struct pmc_bit_map * mphy_sts;
    const struct pmc_bit_map * pll_sts;
    const u32 slp_s0_offset;
    const u32 ltr_ignore_offset;
    const u32 base_address;
    const int regmap_length;
    const u32 ppfear0_offset;
    const int ppfear_buckets;
    const u32 pm_cfg_offset;
    const int pm_read_disable_bit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct pmc_reg_map {
    const struct pmc_bit_map * pfear_sts;
    const struct pmc_bit_map * mphy_sts;
    const struct pmc_bit_map * pll_sts;
    const u32 slp_s0_offset;
    const u32 ltr_ignore_offset;
    const int regmap_length;
    const u32 ppfear0_offset;
    const int ppfear_buckets;
    const u32 pm_cfg_offset;
    const int pm_read_disable_bit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pmc_reg_map {
    const struct pmc_bit_map * pfear_sts;
    const struct pmc_bit_map * mphy_sts;
    const struct pmc_bit_map * pll_sts;
    const struct pmc_bit_map * * slps0_dbg_maps;
    const struct pmc_bit_map * ltr_show_sts;
    const u32 slp_s0_offset;
    const u32 ltr_ignore_offset;
    const int regmap_length;
    const u32 ppfear0_offset;
    const int ppfear_buckets;
    const u32 pm_cfg_offset;
    const int pm_read_disable_bit;
    const u32 slps0_dbg_offset;
    const u32 ltr_ignore_max;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pmc_reg_map {
    const struct pmc_bit_map * pfear_sts;
    const struct pmc_bit_map * mphy_sts;
    const struct pmc_bit_map * pll_sts;
    const struct pmc_bit_map * * slps0_dbg_maps;
    const struct pmc_bit_map * ltr_show_sts;
    const struct pmc_bit_map * msr_sts;
    const u32 slp_s0_offset;
    const u32 ltr_ignore_offset;
    const int regmap_length;
    const u32 ppfear0_offset;
    const int ppfear_buckets;
    const u32 pm_cfg_offset;
    const int pm_read_disable_bit;
    const u32 slps0_dbg_offset;
    const u32 ltr_ignore_max;
    const u32 pm_vric1_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pmc_reg_map {
    const struct pmc_bit_map * pfear_sts;
    const struct pmc_bit_map * mphy_sts;
    const struct pmc_bit_map * pll_sts;
    const struct pmc_bit_map * * slps0_dbg_maps;
    const struct pmc_bit_map * ltr_show_sts;
    const struct pmc_bit_map * msr_sts;
    const u32 slp_s0_offset;
    const u32 ltr_ignore_offset;
    const int regmap_length;
    const u32 ppfear0_offset;
    const int ppfear_buckets;
    const u32 pm_cfg_offset;
    const int pm_read_disable_bit;
    const u32 slps0_dbg_offset;
    const u32 ltr_ignore_max;
    const u32 pm_vric1_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pmc_reg_map {
    const struct pmc_bit_map * * pfear_sts;
    const struct pmc_bit_map * mphy_sts;
    const struct pmc_bit_map * pll_sts;
    const struct pmc_bit_map * * slps0_dbg_maps;
    const struct pmc_bit_map * ltr_show_sts;
    const struct pmc_bit_map * msr_sts;
    const struct pmc_bit_map * * lpm_sts;
    const u32 slp_s0_offset;
    const u32 ltr_ignore_offset;
    const int regmap_length;
    const u32 ppfear0_offset;
    const int ppfear_buckets;
    const u32 pm_cfg_offset;
    const int pm_read_disable_bit;
    const u32 slps0_dbg_offset;
    const u32 ltr_ignore_max;
    const u32 pm_vric1_offset;
    const char * * lpm_modes;
    const u32 lpm_en_offset;
    const u32 lpm_residency_offset;
    const u32 lpm_status_offset;
    const u32 lpm_live_status_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct pmc_reg_map {
    const struct pmc_bit_map * * pfear_sts;
    const struct pmc_bit_map * mphy_sts;
    const struct pmc_bit_map * pll_sts;
    const struct pmc_bit_map * * slps0_dbg_maps;
    const struct pmc_bit_map * ltr_show_sts;
    const struct pmc_bit_map * msr_sts;
    const struct pmc_bit_map * * lpm_sts;
    const u32 slp_s0_offset;
    const int slp_s0_res_counter_step;
    const u32 ltr_ignore_offset;
    const int regmap_length;
    const u32 ppfear0_offset;
    const int ppfear_buckets;
    const u32 pm_cfg_offset;
    const int pm_read_disable_bit;
    const u32 slps0_dbg_offset;
    const u32 ltr_ignore_max;
    const u32 pm_vric1_offset;
    const char * * lpm_modes;
    const u32 lpm_en_offset;
    const u32 lpm_residency_offset;
    const u32 lpm_status_offset;
    const u32 lpm_live_status_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct pmc_reg_map {
    const struct pmc_bit_map * * pfear_sts;
    const struct pmc_bit_map * mphy_sts;
    const struct pmc_bit_map * pll_sts;
    const struct pmc_bit_map * * slps0_dbg_maps;
    const struct pmc_bit_map * ltr_show_sts;
    const struct pmc_bit_map * msr_sts;
    const struct pmc_bit_map * * lpm_sts;
    const u32 slp_s0_offset;
    const int slp_s0_res_counter_step;
    const u32 ltr_ignore_offset;
    const int regmap_length;
    const u32 ppfear0_offset;
    const int ppfear_buckets;
    const u32 pm_cfg_offset;
    const int pm_read_disable_bit;
    const u32 slps0_dbg_offset;
    const u32 ltr_ignore_max;
    const u32 pm_vric1_offset;
    const int lpm_num_maps;
    const int lpm_res_counter_step_x2;
    const u32 lpm_sts_latch_en_offset;
    const u32 lpm_en_offset;
    const u32 lpm_priority_offset;
    const u32 lpm_residency_offset;
    const u32 lpm_status_offset;
    const u32 lpm_live_status_offset;
    const u32 etr3_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct pmc_reg_map {
    const struct pmc_bit_map * * pfear_sts;
    const struct pmc_bit_map * mphy_sts;
    const struct pmc_bit_map * pll_sts;
    const struct pmc_bit_map * * slps0_dbg_maps;
    const struct pmc_bit_map * ltr_show_sts;
    const struct pmc_bit_map * msr_sts;
    const struct pmc_bit_map * * lpm_sts;
    const u32 slp_s0_offset;
    const int slp_s0_res_counter_step;
    const u32 ltr_ignore_offset;
    const int regmap_length;
    const u32 ppfear0_offset;
    const int ppfear_buckets;
    const u32 pm_cfg_offset;
    const int pm_read_disable_bit;
    const u32 slps0_dbg_offset;
    const u32 ltr_ignore_max;
    const u32 pm_vric1_offset;
    const int lpm_num_maps;
    const int lpm_num_modes;
    const int lpm_res_counter_step_x2;
    const u32 lpm_sts_latch_en_offset;
    const u32 lpm_en_offset;
    const u32 lpm_priority_offset;
    const u32 lpm_residency_offset;
    const u32 lpm_status_offset;
    const u32 lpm_live_status_offset;
    const u32 etr3_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct pmc_reg_map {
    const struct pmc_bit_map * * pfear_sts;
    const struct pmc_bit_map * mphy_sts;
    const struct pmc_bit_map * pll_sts;
    const struct pmc_bit_map * * slps0_dbg_maps;
    const struct pmc_bit_map * ltr_show_sts;
    const struct pmc_bit_map * msr_sts;
    const struct pmc_bit_map * * lpm_sts;
    const u32 slp_s0_offset;
    const int slp_s0_res_counter_step;
    const u32 ltr_ignore_offset;
    const int regmap_length;
    const u32 ppfear0_offset;
    const int ppfear_buckets;
    const u32 pm_cfg_offset;
    const int pm_read_disable_bit;
    const u32 slps0_dbg_offset;
    const u32 ltr_ignore_max;
    const u32 pm_vric1_offset;
    const int lpm_num_maps;
    const int lpm_num_modes;
    const int lpm_res_counter_step_x2;
    const u32 lpm_sts_latch_en_offset;
    const u32 lpm_en_offset;
    const u32 lpm_priority_offset;
    const u32 lpm_residency_offset;
    const u32 lpm_status_offset;
    const u32 lpm_live_status_offset;
    const u32 etr3_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct pmc_reg_map {
    const struct pmc_bit_map * * pfear_sts;
    const struct pmc_bit_map * mphy_sts;
    const struct pmc_bit_map * pll_sts;
    const struct pmc_bit_map * * slps0_dbg_maps;
    const struct pmc_bit_map * ltr_show_sts;
    const struct pmc_bit_map * msr_sts;
    const struct pmc_bit_map * * lpm_sts;
    const u32 slp_s0_offset;
    const int slp_s0_res_counter_step;
    const u32 ltr_ignore_offset;
    const int regmap_length;
    const u32 ppfear0_offset;
    const int ppfear_buckets;
    const u32 pm_cfg_offset;
    const int pm_read_disable_bit;
    const u32 slps0_dbg_offset;
    const u32 ltr_ignore_max;
    const u32 pm_vric1_offset;
    const int lpm_num_maps;
    const int lpm_num_modes;
    const int lpm_res_counter_step_x2;
    const u32 lpm_sts_latch_en_offset;
    const u32 lpm_en_offset;
    const u32 lpm_priority_offset;
    const u32 lpm_residency_offset;
    const u32 lpm_status_offset;
    const u32 lpm_live_status_offset;
    const u32 etr3_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct pmc_reg_map {
    const struct pmc_bit_map * * pfear_sts;
    const struct pmc_bit_map * mphy_sts;
    const struct pmc_bit_map * pll_sts;
    const struct pmc_bit_map * * slps0_dbg_maps;
    const struct pmc_bit_map * ltr_show_sts;
    const struct pmc_bit_map * msr_sts;
    const struct pmc_bit_map * * lpm_sts;
    const u32 slp_s0_offset;
    const int slp_s0_res_counter_step;
    const u32 ltr_ignore_offset;
    const int regmap_length;
    const u32 ppfear0_offset;
    const int ppfear_buckets;
    const u32 pm_cfg_offset;
    const int pm_read_disable_bit;
    const u32 slps0_dbg_offset;
    const u32 ltr_ignore_max;
    const u32 pm_vric1_offset;
    const int lpm_num_maps;
    const int lpm_num_modes;
    const int lpm_res_counter_step_x2;
    const u32 lpm_sts_latch_en_offset;
    const u32 lpm_en_offset;
    const u32 lpm_priority_offset;
    const u32 lpm_residency_offset;
    const u32 lpm_status_offset;
    const u32 lpm_live_status_offset;
    const u32 etr3_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct pmc_reg_map {
    const struct pmc_bit_map * d3_sts_0;
    const struct pmc_bit_map * d3_sts_1;
    const struct pmc_bit_map * func_dis;
    const struct pmc_bit_map * func_dis_2;
    const struct pmc_bit_map * pss;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct pmc_reg_map {
    const struct pmc_bit_map * pfear_sts;
    const struct pmc_bit_map * mphy_sts;
    const struct pmc_bit_map * pll_sts;
    const struct pmc_bit_map * * slps0_dbg_maps;
    const struct pmc_bit_map * ltr_show_sts;
    const struct pmc_bit_map * msr_sts;
    const u32 slp_s0_offset;
    const u32 ltr_ignore_offset;
    const int regmap_length;
    const u32 ppfear0_offset;
    const int ppfear_buckets;
    const u32 pm_cfg_offset;
    const int pm_read_disable_bit;
    const u32 slps0_dbg_offset;
    const u32 ltr_ignore_max;
    const u32 pm_vric1_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct pmc_reg_map {
    const struct pmc_bit_map * pfear_sts;
    const struct pmc_bit_map * mphy_sts;
    const struct pmc_bit_map * pll_sts;
    const struct pmc_bit_map * * slps0_dbg_maps;
    const struct pmc_bit_map * ltr_show_sts;
    const struct pmc_bit_map * msr_sts;
    const u32 slp_s0_offset;
    const u32 ltr_ignore_offset;
    const int regmap_length;
    const u32 ppfear0_offset;
    const int ppfear_buckets;
    const u32 pm_cfg_offset;
    const int pm_read_disable_bit;
    const u32 slps0_dbg_offset;
    const u32 ltr_ignore_max;
    const u32 pm_vric1_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pmc_reg_map {
    const struct pmc_bit_map * pfear_sts;
    const struct pmc_bit_map * mphy_sts;
    const struct pmc_bit_map * pll_sts;
    const struct pmc_bit_map * * slps0_dbg_maps;
    const struct pmc_bit_map * ltr_show_sts;
    const struct pmc_bit_map * msr_sts;
    const u32 slp_s0_offset;
    const u32 ltr_ignore_offset;
    const int regmap_length;
    const u32 ppfear0_offset;
    const int ppfear_buckets;
    const u32 pm_cfg_offset;
    const int pm_read_disable_bit;
    const u32 slps0_dbg_offset;
    const u32 ltr_ignore_max;
    const u32 pm_vric1_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pmc_reg_map {
    const struct pmc_bit_map * pfear_sts;
    const struct pmc_bit_map * mphy_sts;
    const struct pmc_bit_map * pll_sts;
    const struct pmc_bit_map * * slps0_dbg_maps;
    const struct pmc_bit_map * ltr_show_sts;
    const struct pmc_bit_map * msr_sts;
    const u32 slp_s0_offset;
    const u32 ltr_ignore_offset;
    const int regmap_length;
    const u32 ppfear0_offset;
    const int ppfear_buckets;
    const u32 pm_cfg_offset;
    const int pm_read_disable_bit;
    const u32 slps0_dbg_offset;
    const u32 ltr_ignore_max;
    const u32 pm_vric1_offset;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct pmc_bit_map * pfear_sts</code>
</li>
<li>
<b>Field added. </b>
<code>const struct pmc_bit_map * mphy_sts</code>
</li>
<li>
<b>Field added. </b>
<code>const struct pmc_bit_map * pll_sts</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct pmc_bit_map * d3_sts_0</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct pmc_bit_map * d3_sts_1</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct pmc_bit_map * func_dis</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct pmc_bit_map * func_dis_2</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct pmc_bit_map * pss</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const u32 slp_s0_offset</code>
</li>
<li>
<b>Field added. </b>
<code>const u32 ltr_ignore_offset</code>
</li>
<li>
<b>Field added. </b>
<code>const u32 base_address</code>
</li>
<li>
<b>Field added. </b>
<code>const int regmap_length</code>
</li>
<li>
<b>Field added. </b>
<code>const u32 ppfear0_offset</code>
</li>
<li>
<b>Field added. </b>
<code>const int ppfear_buckets</code>
</li>
<li>
<b>Field added. </b>
<code>const u32 pm_cfg_offset</code>
</li>
<li>
<b>Field added. </b>
<code>const int pm_read_disable_bit</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>const u32 base_address</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct pmc_bit_map * * slps0_dbg_maps</code>
</li>
<li>
<b>Field added. </b>
<code>const struct pmc_bit_map * ltr_show_sts</code>
</li>
<li>
<b>Field added. </b>
<code>const u32 slps0_dbg_offset</code>
</li>
<li>
<b>Field added. </b>
<code>const u32 ltr_ignore_max</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct pmc_bit_map * msr_sts</code>
</li>
<li>
<b>Field added. </b>
<code>const u32 pm_vric1_offset</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct pmc_bit_map * * lpm_sts</code>
</li>
<li>
<b>Field added. </b>
<code>const char * * lpm_modes</code>
</li>
<li>
<b>Field added. </b>
<code>const u32 lpm_en_offset</code>
</li>
<li>
<b>Field added. </b>
<code>const u32 lpm_residency_offset</code>
</li>
<li>
<b>Field added. </b>
<code>const u32 lpm_status_offset</code>
</li>
<li>
<b>Field added. </b>
<code>const u32 lpm_live_status_offset</code>
</li>
<li>
<b>Field type changed. </b>
<code>const struct pmc_bit_map * pfear_sts</code> ➡️ <code>const struct pmc_bit_map * * pfear_sts</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const int slp_s0_res_counter_step</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const int lpm_num_maps</code>
</li>
<li>
<b>Field added. </b>
<code>const int lpm_res_counter_step_x2</code>
</li>
<li>
<b>Field added. </b>
<code>const u32 lpm_sts_latch_en_offset</code>
</li>
<li>
<b>Field added. </b>
<code>const u32 lpm_priority_offset</code>
</li>
<li>
<b>Field added. </b>
<code>const u32 etr3_offset</code>
</li>
<li>
<b>Field removed. </b>
<code>const char * * lpm_modes</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const int lpm_num_modes</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct pmc_bit_map * d3_sts_0</code>
</li>
<li>
<b>Field added. </b>
<code>const struct pmc_bit_map * d3_sts_1</code>
</li>
<li>
<b>Field added. </b>
<code>const struct pmc_bit_map * func_dis</code>
</li>
<li>
<b>Field added. </b>
<code>const struct pmc_bit_map * func_dis_2</code>
</li>
<li>
<b>Field added. </b>
<code>const struct pmc_bit_map * pss</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct pmc_bit_map * * pfear_sts</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct pmc_bit_map * mphy_sts</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct pmc_bit_map * pll_sts</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct pmc_bit_map * * slps0_dbg_maps</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct pmc_bit_map * ltr_show_sts</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct pmc_bit_map * msr_sts</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct pmc_bit_map * * lpm_sts</code>
</li>
<li>
<b>Field removed. </b>
<code>const u32 slp_s0_offset</code>
</li>
<li>
<b>Field removed. </b>
<code>const int slp_s0_res_counter_step</code>
</li>
<li>
<b>Field removed. </b>
<code>const u32 ltr_ignore_offset</code>
</li>
<li>
<b>Field removed. </b>
<code>const int regmap_length</code>
</li>
<li>
<b>Field removed. </b>
<code>const u32 ppfear0_offset</code>
</li>
<li>
<b>Field removed. </b>
<code>const int ppfear_buckets</code>
</li>
<li>
<b>Field removed. </b>
<code>const u32 pm_cfg_offset</code>
</li>
<li>
<b>Field removed. </b>
<code>const int pm_read_disable_bit</code>
</li>
<li>
<b>Field removed. </b>
<code>const u32 slps0_dbg_offset</code>
</li>
<li>
<b>Field removed. </b>
<code>const u32 ltr_ignore_max</code>
</li>
<li>
<b>Field removed. </b>
<code>const u32 pm_vric1_offset</code>
</li>
<li>
<b>Field removed. </b>
<code>const int lpm_num_maps</code>
</li>
<li>
<b>Field removed. </b>
<code>const int lpm_num_modes</code>
</li>
<li>
<b>Field removed. </b>
<code>const int lpm_res_counter_step_x2</code>
</li>
<li>
<b>Field removed. </b>
<code>const u32 lpm_sts_latch_en_offset</code>
</li>
<li>
<b>Field removed. </b>
<code>const u32 lpm_en_offset</code>
</li>
<li>
<b>Field removed. </b>
<code>const u32 lpm_priority_offset</code>
</li>
<li>
<b>Field removed. </b>
<code>const u32 lpm_residency_offset</code>
</li>
<li>
<b>Field removed. </b>
<code>const u32 lpm_status_offset</code>
</li>
<li>
<b>Field removed. </b>
<code>const u32 lpm_live_status_offset</code>
</li>
<li>
<b>Field removed. </b>
<code>const u32 etr3_offset</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct pmc_reg_map {
    const struct pmc_bit_map * pfear_sts;
    const struct pmc_bit_map * mphy_sts;
    const struct pmc_bit_map * pll_sts;
    const struct pmc_bit_map * * slps0_dbg_maps;
    const struct pmc_bit_map * ltr_show_sts;
    const struct pmc_bit_map * msr_sts;
    const u32 slp_s0_offset;
    const u32 ltr_ignore_offset;
    const int regmap_length;
    const u32 ppfear0_offset;
    const int ppfear_buckets;
    const u32 pm_cfg_offset;
    const int pm_read_disable_bit;
    const u32 slps0_dbg_offset;
    const u32 ltr_ignore_max;
    const u32 pm_vric1_offset;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct pmc_reg_map {
    const struct pmc_bit_map * pfear_sts;
    const struct pmc_bit_map * mphy_sts;
    const struct pmc_bit_map * pll_sts;
    const struct pmc_bit_map * * slps0_dbg_maps;
    const struct pmc_bit_map * ltr_show_sts;
    const struct pmc_bit_map * msr_sts;
    const u32 slp_s0_offset;
    const u32 ltr_ignore_offset;
    const int regmap_length;
    const u32 ppfear0_offset;
    const int ppfear_buckets;
    const u32 pm_cfg_offset;
    const int pm_read_disable_bit;
    const u32 slps0_dbg_offset;
    const u32 ltr_ignore_max;
    const u32 pm_vric1_offset;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct pmc_reg_map {
    const struct pmc_bit_map * pfear_sts;
    const struct pmc_bit_map * mphy_sts;
    const struct pmc_bit_map * pll_sts;
    const struct pmc_bit_map * * slps0_dbg_maps;
    const struct pmc_bit_map * ltr_show_sts;
    const struct pmc_bit_map * msr_sts;
    const u32 slp_s0_offset;
    const u32 ltr_ignore_offset;
    const int regmap_length;
    const u32 ppfear0_offset;
    const int ppfear_buckets;
    const u32 pm_cfg_offset;
    const int pm_read_disable_bit;
    const u32 slps0_dbg_offset;
    const u32 ltr_ignore_max;
    const u32 pm_vric1_offset;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct pmc_reg_map {
    const struct pmc_bit_map * pfear_sts;
    const struct pmc_bit_map * mphy_sts;
    const struct pmc_bit_map * pll_sts;
    const struct pmc_bit_map * * slps0_dbg_maps;
    const struct pmc_bit_map * ltr_show_sts;
    const struct pmc_bit_map * msr_sts;
    const u32 slp_s0_offset;
    const u32 ltr_ignore_offset;
    const int regmap_length;
    const u32 ppfear0_offset;
    const int ppfear_buckets;
    const u32 pm_cfg_offset;
    const int pm_read_disable_bit;
    const u32 slps0_dbg_offset;
    const u32 ltr_ignore_max;
    const u32 pm_vric1_offset;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
