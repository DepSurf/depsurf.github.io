# Struct: <code>nand_onfi_vendor_micron</code>

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
struct nand_onfi_vendor_micron {
    u8 two_plane_read;
    u8 read_cache;
    u8 read_unique_id;
    u8 dq_imped;
    u8 dq_imped_num_settings;
    u8 dq_imped_feat_addr;
    u8 rb_pulldown_strength;
    u8 rb_pulldown_strength_feat_addr;
    u8 rb_pulldown_strength_num_settings;
    u8 otp_mode;
    u8 otp_page_start;
    u8 otp_data_prot_addr;
    u8 otp_num_pages;
    u8 otp_feat_addr;
    u8 read_retry_options;
    u8[72] reserved;
    u8 param_revision;
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
struct nand_onfi_vendor_micron {
    u8 two_plane_read;
    u8 read_cache;
    u8 read_unique_id;
    u8 dq_imped;
    u8 dq_imped_num_settings;
    u8 dq_imped_feat_addr;
    u8 rb_pulldown_strength;
    u8 rb_pulldown_strength_feat_addr;
    u8 rb_pulldown_strength_num_settings;
    u8 otp_mode;
    u8 otp_page_start;
    u8 otp_data_prot_addr;
    u8 otp_num_pages;
    u8 otp_feat_addr;
    u8 read_retry_options;
    u8[72] reserved;
    u8 param_revision;
}
```
</details>
</li>
</ul>
