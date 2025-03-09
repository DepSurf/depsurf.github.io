# Struct: <code>altr_sdram_prv_data</code>

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
struct altr_sdram_prv_data {
    int ecc_ctrl_offset;
    int ecc_ctl_en_mask;
    int ecc_cecnt_offset;
    int ecc_uecnt_offset;
    int ecc_stat_offset;
    int ecc_stat_ce_mask;
    int ecc_stat_ue_mask;
    int ecc_saddr_offset;
    int ecc_daddr_offset;
    int ecc_irq_en_offset;
    int ecc_irq_en_mask;
    int ecc_irq_clr_offset;
    int ecc_irq_clr_mask;
    int ecc_cnt_rst_offset;
    int ecc_cnt_rst_mask;
    struct edac_dev_sysfs_attribute * eccmgr_sysfs_attr;
    int ecc_enable_mask;
    int ce_set_mask;
    int ue_set_mask;
    int ce_ue_trgr_offset;
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
struct altr_sdram_prv_data {
    int ecc_ctrl_offset;
    int ecc_ctl_en_mask;
    int ecc_cecnt_offset;
    int ecc_uecnt_offset;
    int ecc_stat_offset;
    int ecc_stat_ce_mask;
    int ecc_stat_ue_mask;
    int ecc_saddr_offset;
    int ecc_daddr_offset;
    int ecc_irq_en_offset;
    int ecc_irq_en_mask;
    int ecc_irq_clr_offset;
    int ecc_irq_clr_mask;
    int ecc_cnt_rst_offset;
    int ecc_cnt_rst_mask;
    struct edac_dev_sysfs_attribute * eccmgr_sysfs_attr;
    int ecc_enable_mask;
    int ce_set_mask;
    int ue_set_mask;
    int ce_ue_trgr_offset;
}
```
</details>
</li>
</ul>
