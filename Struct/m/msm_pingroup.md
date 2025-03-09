# Struct: <code>msm_pingroup</code>

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
struct msm_pingroup {
    const char * name;
    const unsigned int * pins;
    unsigned int npins;
    unsigned int * funcs;
    unsigned int nfuncs;
    u32 ctl_reg;
    u32 io_reg;
    u32 intr_cfg_reg;
    u32 intr_status_reg;
    u32 intr_target_reg;
    unsigned int tile;
    unsigned int mux_bit;
    unsigned int pull_bit;
    unsigned int drv_bit;
    unsigned int oe_bit;
    unsigned int in_bit;
    unsigned int out_bit;
    unsigned int intr_enable_bit;
    unsigned int intr_status_bit;
    unsigned int intr_ack_high;
    unsigned int intr_target_bit;
    unsigned int intr_target_kpss_val;
    unsigned int intr_raw_status_bit;
    unsigned int intr_polarity_bit;
    unsigned int intr_detection_bit;
    unsigned int intr_detection_width;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct msm_pingroup {
    const char * name;
    const unsigned int * pins;
    unsigned int npins;
    unsigned int * funcs;
    unsigned int nfuncs;
    u32 ctl_reg;
    u32 io_reg;
    u32 intr_cfg_reg;
    u32 intr_status_reg;
    u32 intr_target_reg;
    unsigned int tile;
    unsigned int mux_bit;
    unsigned int pull_bit;
    unsigned int drv_bit;
    unsigned int oe_bit;
    unsigned int in_bit;
    unsigned int out_bit;
    unsigned int intr_enable_bit;
    unsigned int intr_status_bit;
    unsigned int intr_ack_high;
    unsigned int intr_target_bit;
    unsigned int intr_target_kpss_val;
    unsigned int intr_raw_status_bit;
    unsigned int intr_polarity_bit;
    unsigned int intr_detection_bit;
    unsigned int intr_detection_width;
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
struct msm_pingroup {
    const char * name;
    const unsigned int * pins;
    unsigned int npins;
    unsigned int * funcs;
    unsigned int nfuncs;
    u32 ctl_reg;
    u32 io_reg;
    u32 intr_cfg_reg;
    u32 intr_status_reg;
    u32 intr_target_reg;
    unsigned int tile;
    unsigned int mux_bit;
    unsigned int pull_bit;
    unsigned int drv_bit;
    unsigned int oe_bit;
    unsigned int in_bit;
    unsigned int out_bit;
    unsigned int intr_enable_bit;
    unsigned int intr_status_bit;
    unsigned int intr_ack_high;
    unsigned int intr_target_bit;
    unsigned int intr_target_kpss_val;
    unsigned int intr_raw_status_bit;
    unsigned int intr_polarity_bit;
    unsigned int intr_detection_bit;
    unsigned int intr_detection_width;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct msm_pingroup {
    const char * name;
    const unsigned int * pins;
    unsigned int npins;
    unsigned int * funcs;
    unsigned int nfuncs;
    u32 ctl_reg;
    u32 io_reg;
    u32 intr_cfg_reg;
    u32 intr_status_reg;
    u32 intr_target_reg;
    unsigned int tile;
    unsigned int mux_bit;
    unsigned int pull_bit;
    unsigned int drv_bit;
    unsigned int oe_bit;
    unsigned int in_bit;
    unsigned int out_bit;
    unsigned int intr_enable_bit;
    unsigned int intr_status_bit;
    unsigned int intr_ack_high;
    unsigned int intr_target_bit;
    unsigned int intr_target_kpss_val;
    unsigned int intr_raw_status_bit;
    unsigned int intr_polarity_bit;
    unsigned int intr_detection_bit;
    unsigned int intr_detection_width;
}
```
</details>
</li>
</ul>
