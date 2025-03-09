# Struct: <code>ti_iodelay_reg_data</code>

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
struct ti_iodelay_reg_data {
    u32 signature_mask;
    u32 signature_value;
    u32 lock_mask;
    u32 lock_val;
    u32 unlock_val;
    u32 binary_data_coarse_mask;
    u32 binary_data_fine_mask;
    u32 reg_refclk_offset;
    u32 refclk_period_mask;
    u32 reg_coarse_offset;
    u32 coarse_delay_count_mask;
    u32 coarse_ref_count_mask;
    u32 reg_fine_offset;
    u32 fine_delay_count_mask;
    u32 fine_ref_count_mask;
    u32 reg_global_lock_offset;
    u32 global_lock_mask;
    u32 global_unlock_val;
    u32 global_lock_val;
    u32 reg_start_offset;
    u32 reg_nr_per_pin;
    struct regmap_config * regmap_config;
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
struct ti_iodelay_reg_data {
    u32 signature_mask;
    u32 signature_value;
    u32 lock_mask;
    u32 lock_val;
    u32 unlock_val;
    u32 binary_data_coarse_mask;
    u32 binary_data_fine_mask;
    u32 reg_refclk_offset;
    u32 refclk_period_mask;
    u32 reg_coarse_offset;
    u32 coarse_delay_count_mask;
    u32 coarse_ref_count_mask;
    u32 reg_fine_offset;
    u32 fine_delay_count_mask;
    u32 fine_ref_count_mask;
    u32 reg_global_lock_offset;
    u32 global_lock_mask;
    u32 global_unlock_val;
    u32 global_lock_val;
    u32 reg_start_offset;
    u32 reg_nr_per_pin;
    struct regmap_config * regmap_config;
}
```
</details>
</li>
</ul>
