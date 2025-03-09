# Struct: <code>ti_sci_msg_rm_udmap_flow_cfg</code>

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
struct ti_sci_msg_rm_udmap_flow_cfg {
    u32 valid_params;
    u16 nav_id;
    u16 flow_index;
    u8 rx_einfo_present;
    u8 rx_psinfo_present;
    u8 rx_error_handling;
    u8 rx_desc_type;
    u16 rx_sop_offset;
    u16 rx_dest_qnum;
    u8 rx_src_tag_hi;
    u8 rx_src_tag_lo;
    u8 rx_dest_tag_hi;
    u8 rx_dest_tag_lo;
    u8 rx_src_tag_hi_sel;
    u8 rx_src_tag_lo_sel;
    u8 rx_dest_tag_hi_sel;
    u8 rx_dest_tag_lo_sel;
    u16 rx_fdq0_sz0_qnum;
    u16 rx_fdq1_qnum;
    u16 rx_fdq2_qnum;
    u16 rx_fdq3_qnum;
    u8 rx_ps_location;
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
struct ti_sci_msg_rm_udmap_flow_cfg {
    u32 valid_params;
    u16 nav_id;
    u16 flow_index;
    u8 rx_einfo_present;
    u8 rx_psinfo_present;
    u8 rx_error_handling;
    u8 rx_desc_type;
    u16 rx_sop_offset;
    u16 rx_dest_qnum;
    u8 rx_src_tag_hi;
    u8 rx_src_tag_lo;
    u8 rx_dest_tag_hi;
    u8 rx_dest_tag_lo;
    u8 rx_src_tag_hi_sel;
    u8 rx_src_tag_lo_sel;
    u8 rx_dest_tag_hi_sel;
    u8 rx_dest_tag_lo_sel;
    u16 rx_fdq0_sz0_qnum;
    u16 rx_fdq1_qnum;
    u16 rx_fdq2_qnum;
    u16 rx_fdq3_qnum;
    u8 rx_ps_location;
}
```
</details>
</li>
</ul>
