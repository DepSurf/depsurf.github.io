# Struct: <code>omap3_scratchpad_sdrc_block</code>

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
struct omap3_scratchpad_sdrc_block {
    u16 sysconfig;
    u16 cs_cfg;
    u16 sharing;
    u16 err_type;
    u32 dll_a_ctrl;
    u32 dll_b_ctrl;
    u32 power;
    u32 cs_0;
    u32 mcfg_0;
    u16 mr_0;
    u16 emr_1_0;
    u16 emr_2_0;
    u16 emr_3_0;
    u32 actim_ctrla_0;
    u32 actim_ctrlb_0;
    u32 rfr_ctrl_0;
    u32 cs_1;
    u32 mcfg_1;
    u16 mr_1;
    u16 emr_1_1;
    u16 emr_2_1;
    u16 emr_3_1;
    u32 actim_ctrla_1;
    u32 actim_ctrlb_1;
    u32 rfr_ctrl_1;
    u16 dcdl_1_ctrl;
    u16 dcdl_2_ctrl;
    u32 flags;
    u32 block_size;
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
struct omap3_scratchpad_sdrc_block {
    u16 sysconfig;
    u16 cs_cfg;
    u16 sharing;
    u16 err_type;
    u32 dll_a_ctrl;
    u32 dll_b_ctrl;
    u32 power;
    u32 cs_0;
    u32 mcfg_0;
    u16 mr_0;
    u16 emr_1_0;
    u16 emr_2_0;
    u16 emr_3_0;
    u32 actim_ctrla_0;
    u32 actim_ctrlb_0;
    u32 rfr_ctrl_0;
    u32 cs_1;
    u32 mcfg_1;
    u16 mr_1;
    u16 emr_1_1;
    u16 emr_2_1;
    u16 emr_3_1;
    u32 actim_ctrla_1;
    u32 actim_ctrlb_1;
    u32 rfr_ctrl_1;
    u16 dcdl_1_ctrl;
    u16 dcdl_2_ctrl;
    u32 flags;
    u32 block_size;
}
```
</details>
</li>
</ul>
