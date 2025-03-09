# Struct: <code>spu_priv1</code>

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
struct spu_priv1 {
    u64 mfc_sr1_RW;
    u64 mfc_lpid_RW;
    u64 spu_idr_RW;
    u64 mfc_vr_RO;
    u64 spu_vr_RO;
    u8[216] pad_0x28_0x100;
    u64[3] int_mask_RW;
    u8[40] pad_0x118_0x140;
    u64[3] int_stat_RW;
    u8[40] pad_0x158_0x180;
    u64 int_route_RW;
    u8[120] pad_0x188_0x200;
    u64 mfc_atomic_flush_RW;
    u8[120] pad_0x208_0x280;
    u64 resource_allocation_groupID_RW;
    u64 resource_allocation_enable_RW;
    u8[312] pad_0x290_0x3c8;
    u64 smf_sbi_signal_sel;
    u64 smf_ato_signal_sel;
    u8[40] pad_0x3d8_0x400;
    u64 mfc_sdr_RW;
    u8[248] pad_0x408_0x500;
    u64 tlb_index_hint_RO;
    u64 tlb_index_W;
    u64 tlb_vpn_RW;
    u64 tlb_rpn_RW;
    u8[32] pad_0x520_0x540;
    u64 tlb_invalidate_entry_W;
    u64 tlb_invalidate_all_W;
    u8[48] pad_0x550_0x580;
    u64 smm_hid;
    u8[120] pad_0x588_0x600;
    u64 mfc_accr_RW;
    u8[8] pad_0x608_0x610;
    u64 mfc_dsisr_RW;
    u8[8] pad_0x618_0x620;
    u64 mfc_dar_RW;
    u8[216] pad_0x628_0x700;
    u64 rmt_index_RW;
    u8[8] pad_0x708_0x710;
    u64 rmt_data1_RW;
    u8[232] pad_0x718_0x800;
    u64 mfc_dsir_R;
    u64 mfc_lsacr_RW;
    u64 mfc_lscrr_R;
    u8[8] pad_0x818_0x820;
    u64 mfc_tclass_id_RW;
    u8[216] pad_0x828_0x900;
    u64 mfc_rm_boundary;
    u8[48] pad_0x908_0x938;
    u64 smf_dma_signal_sel;
    u8[248] pad_0x940_0xa38;
    u64 smm_signal_sel;
    u8[448] pad_0xa40_0xc00;
    u64 mfc_cer_R;
    u8[1016] pad_0xc08_0x1000;
    u64 spu_ecc_cntl_RW;
    u64 spu_ecc_stat_RW;
    u64 spu_ecc_addr_RW;
    u64 spu_err_mask_RW;
    u8[8] pad_0x1020_0x1028;
    u64 spu_trig0_sel;
    u64 spu_trig1_sel;
    u64 spu_trig2_sel;
    u64 spu_trig3_sel;
    u64 spu_trace_sel;
    u64 spu_event0_sel;
    u64 spu_event1_sel;
    u64 spu_event2_sel;
    u64 spu_event3_sel;
    u64 spu_trace_cntl;
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
struct spu_priv1 {
    u64 mfc_sr1_RW;
    u64 mfc_lpid_RW;
    u64 spu_idr_RW;
    u64 mfc_vr_RO;
    u64 spu_vr_RO;
    u8[216] pad_0x28_0x100;
    u64[3] int_mask_RW;
    u8[40] pad_0x118_0x140;
    u64[3] int_stat_RW;
    u8[40] pad_0x158_0x180;
    u64 int_route_RW;
    u8[120] pad_0x188_0x200;
    u64 mfc_atomic_flush_RW;
    u8[120] pad_0x208_0x280;
    u64 resource_allocation_groupID_RW;
    u64 resource_allocation_enable_RW;
    u8[312] pad_0x290_0x3c8;
    u64 smf_sbi_signal_sel;
    u64 smf_ato_signal_sel;
    u8[40] pad_0x3d8_0x400;
    u64 mfc_sdr_RW;
    u8[248] pad_0x408_0x500;
    u64 tlb_index_hint_RO;
    u64 tlb_index_W;
    u64 tlb_vpn_RW;
    u64 tlb_rpn_RW;
    u8[32] pad_0x520_0x540;
    u64 tlb_invalidate_entry_W;
    u64 tlb_invalidate_all_W;
    u8[48] pad_0x550_0x580;
    u64 smm_hid;
    u8[120] pad_0x588_0x600;
    u64 mfc_accr_RW;
    u8[8] pad_0x608_0x610;
    u64 mfc_dsisr_RW;
    u8[8] pad_0x618_0x620;
    u64 mfc_dar_RW;
    u8[216] pad_0x628_0x700;
    u64 rmt_index_RW;
    u8[8] pad_0x708_0x710;
    u64 rmt_data1_RW;
    u8[232] pad_0x718_0x800;
    u64 mfc_dsir_R;
    u64 mfc_lsacr_RW;
    u64 mfc_lscrr_R;
    u8[8] pad_0x818_0x820;
    u64 mfc_tclass_id_RW;
    u8[216] pad_0x828_0x900;
    u64 mfc_rm_boundary;
    u8[48] pad_0x908_0x938;
    u64 smf_dma_signal_sel;
    u8[248] pad_0x940_0xa38;
    u64 smm_signal_sel;
    u8[448] pad_0xa40_0xc00;
    u64 mfc_cer_R;
    u8[1016] pad_0xc08_0x1000;
    u64 spu_ecc_cntl_RW;
    u64 spu_ecc_stat_RW;
    u64 spu_ecc_addr_RW;
    u64 spu_err_mask_RW;
    u8[8] pad_0x1020_0x1028;
    u64 spu_trig0_sel;
    u64 spu_trig1_sel;
    u64 spu_trig2_sel;
    u64 spu_trig3_sel;
    u64 spu_trace_sel;
    u64 spu_event0_sel;
    u64 spu_event1_sel;
    u64 spu_event2_sel;
    u64 spu_event3_sel;
    u64 spu_trace_cntl;
}
```
</details>
</li>
</ul>
