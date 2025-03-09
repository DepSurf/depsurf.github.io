# Struct: <code>armada_thermal_data</code>

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
struct armada_thermal_data {
    void (*)(struct platform_device *, struct armada_thermal_priv *) init;
    s64 coef_b;
    s64 coef_m;
    u32 coef_div;
    bool inverted;
    bool signed_sample;
    unsigned int temp_shift;
    unsigned int temp_mask;
    unsigned int thresh_shift;
    unsigned int hyst_shift;
    unsigned int hyst_mask;
    u32 is_valid_bit;
    unsigned int syscon_control0_off;
    unsigned int syscon_control1_off;
    unsigned int syscon_status_off;
    unsigned int dfx_irq_cause_off;
    unsigned int dfx_irq_mask_off;
    unsigned int dfx_overheat_irq;
    unsigned int dfx_server_irq_mask_off;
    unsigned int dfx_server_irq_en;
    unsigned int cpu_nr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct armada_thermal_data {
    void (*)(struct platform_device *, struct armada_thermal_priv *) init;
    s64 coef_b;
    s64 coef_m;
    u32 coef_div;
    bool inverted;
    bool signed_sample;
    unsigned int temp_shift;
    unsigned int temp_mask;
    unsigned int thresh_shift;
    unsigned int hyst_shift;
    unsigned int hyst_mask;
    u32 is_valid_bit;
    unsigned int syscon_control0_off;
    unsigned int syscon_control1_off;
    unsigned int syscon_status_off;
    unsigned int dfx_irq_cause_off;
    unsigned int dfx_irq_mask_off;
    unsigned int dfx_overheat_irq;
    unsigned int dfx_server_irq_mask_off;
    unsigned int dfx_server_irq_en;
    unsigned int cpu_nr;
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
struct armada_thermal_data {
    void (*)(struct platform_device *, struct armada_thermal_priv *) init;
    s64 coef_b;
    s64 coef_m;
    u32 coef_div;
    bool inverted;
    bool signed_sample;
    unsigned int temp_shift;
    unsigned int temp_mask;
    unsigned int thresh_shift;
    unsigned int hyst_shift;
    unsigned int hyst_mask;
    u32 is_valid_bit;
    unsigned int syscon_control0_off;
    unsigned int syscon_control1_off;
    unsigned int syscon_status_off;
    unsigned int dfx_irq_cause_off;
    unsigned int dfx_irq_mask_off;
    unsigned int dfx_overheat_irq;
    unsigned int dfx_server_irq_mask_off;
    unsigned int dfx_server_irq_en;
    unsigned int cpu_nr;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct armada_thermal_data {
    void (*)(struct platform_device *, struct armada_thermal_priv *) init;
    s64 coef_b;
    s64 coef_m;
    u32 coef_div;
    bool inverted;
    bool signed_sample;
    unsigned int temp_shift;
    unsigned int temp_mask;
    unsigned int thresh_shift;
    unsigned int hyst_shift;
    unsigned int hyst_mask;
    u32 is_valid_bit;
    unsigned int syscon_control0_off;
    unsigned int syscon_control1_off;
    unsigned int syscon_status_off;
    unsigned int dfx_irq_cause_off;
    unsigned int dfx_irq_mask_off;
    unsigned int dfx_overheat_irq;
    unsigned int dfx_server_irq_mask_off;
    unsigned int dfx_server_irq_en;
    unsigned int cpu_nr;
}
```
</details>
</li>
</ul>
