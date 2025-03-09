# Struct: <code>spu_priv2</code>

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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct spu_priv2 {
    u8[4352] pad_0x0000_0x1100;
    u8[8] pad_0x1100_0x1108;
    u64 slb_index_W;
    u64 slb_esid_RW;
    u64 slb_vsid_RW;
    u64 slb_invalidate_entry_W;
    u64 slb_invalidate_all_W;
    u8[3792] pad_0x1130_0x2000;
    struct mfc_cq_sr[16] spuq;
    struct mfc_cq_sr[8] puq;
    u8[3328] pad_0x2300_0x3000;
    u64 mfc_control_RW;
    u8[4088] pad_0x3008_0x4000;
    u64 puint_mb_R;
    u8[56] pad_0x4008_0x4040;
    u64 spu_privcntl_RW;
    u8[16] pad_0x4048_0x4058;
    u64 spu_lslr_RW;
    u64 spu_chnlcntptr_RW;
    u64 spu_chnlcnt_RW;
    u64 spu_chnldata_RW;
    u64 spu_cfg_RW;
    u8[3968] pad_0x4080_0x5000;
    u64 spu_pm_trace_tag_status_RW;
    u64 spu_tag_status_query_RW;
    u64 spu_cmd_buf1_RW;
    u64 spu_cmd_buf2_RW;
    u64 spu_atomic_status_RW;
}
```
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct spu_priv2 {
    u8[4352] pad_0x0000_0x1100;
    u8[8] pad_0x1100_0x1108;
    u64 slb_index_W;
    u64 slb_esid_RW;
    u64 slb_vsid_RW;
    u64 slb_invalidate_entry_W;
    u64 slb_invalidate_all_W;
    u8[3792] pad_0x1130_0x2000;
    struct mfc_cq_sr[16] spuq;
    struct mfc_cq_sr[8] puq;
    u8[3328] pad_0x2300_0x3000;
    u64 mfc_control_RW;
    u8[4088] pad_0x3008_0x4000;
    u64 puint_mb_R;
    u8[56] pad_0x4008_0x4040;
    u64 spu_privcntl_RW;
    u8[16] pad_0x4048_0x4058;
    u64 spu_lslr_RW;
    u64 spu_chnlcntptr_RW;
    u64 spu_chnlcnt_RW;
    u64 spu_chnldata_RW;
    u64 spu_cfg_RW;
    u8[3968] pad_0x4080_0x5000;
    u64 spu_pm_trace_tag_status_RW;
    u64 spu_tag_status_query_RW;
    u64 spu_cmd_buf1_RW;
    u64 spu_cmd_buf2_RW;
    u64 spu_atomic_status_RW;
}
```
</details>
</li>
</ul>
