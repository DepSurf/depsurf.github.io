# Struct: <code>dwc2_qtd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dwc2_qtd {
    enum dwc2_control_phase control_phase;
    u8 in_process;
    u8 data_toggle;
    u8 complete_split;
    u8 isoc_split_pos;
    u16 isoc_frame_index;
    u16 isoc_split_offset;
    u32 ssplit_out_xfer_count;
    u8 error_count;
    u8 n_desc;
    u16 isoc_frame_index_last;
    struct dwc2_hcd_urb * urb;
    struct dwc2_qh * qh;
    struct list_head qtd_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct dwc2_qtd {
    enum dwc2_control_phase control_phase;
    u8 in_process;
    u8 data_toggle;
    u8 complete_split;
    u8 isoc_split_pos;
    u16 isoc_frame_index;
    u16 isoc_split_offset;
    u16 isoc_td_last;
    u16 isoc_td_first;
    u32 ssplit_out_xfer_count;
    u8 error_count;
    u8 n_desc;
    u16 isoc_frame_index_last;
    struct dwc2_hcd_urb * urb;
    struct dwc2_qh * qh;
    struct list_head qtd_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct dwc2_qtd {
    enum dwc2_control_phase control_phase;
    u8 in_process;
    u8 data_toggle;
    u8 complete_split;
    u8 isoc_split_pos;
    u16 isoc_frame_index;
    u16 isoc_split_offset;
    u16 isoc_td_last;
    u16 isoc_td_first;
    u32 ssplit_out_xfer_count;
    u8 error_count;
    u8 n_desc;
    u16 isoc_frame_index_last;
    struct dwc2_hcd_urb * urb;
    struct dwc2_qh * qh;
    struct list_head qtd_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dwc2_qtd {
    enum dwc2_control_phase control_phase;
    u8 in_process;
    u8 data_toggle;
    u8 complete_split;
    u8 isoc_split_pos;
    u16 isoc_frame_index;
    u16 isoc_split_offset;
    u16 isoc_td_last;
    u16 isoc_td_first;
    u32 ssplit_out_xfer_count;
    u8 error_count;
    u8 n_desc;
    u16 isoc_frame_index_last;
    struct dwc2_hcd_urb * urb;
    struct dwc2_qh * qh;
    struct list_head qtd_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dwc2_qtd {
    enum dwc2_control_phase control_phase;
    u8 in_process;
    u8 data_toggle;
    u8 complete_split;
    u8 isoc_split_pos;
    u16 isoc_frame_index;
    u16 isoc_split_offset;
    u16 isoc_td_last;
    u16 isoc_td_first;
    u32 ssplit_out_xfer_count;
    u8 error_count;
    u8 n_desc;
    u16 isoc_frame_index_last;
    struct dwc2_hcd_urb * urb;
    struct dwc2_qh * qh;
    struct list_head qtd_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dwc2_qtd {
    enum dwc2_control_phase control_phase;
    u8 in_process;
    u8 data_toggle;
    u8 complete_split;
    u8 isoc_split_pos;
    u16 isoc_frame_index;
    u16 isoc_split_offset;
    u16 isoc_td_last;
    u16 isoc_td_first;
    u32 ssplit_out_xfer_count;
    u8 error_count;
    u8 n_desc;
    u16 isoc_frame_index_last;
    u16 num_naks;
    struct dwc2_hcd_urb * urb;
    struct dwc2_qh * qh;
    struct list_head qtd_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dwc2_qtd {
    enum dwc2_control_phase control_phase;
    u8 in_process;
    u8 data_toggle;
    u8 complete_split;
    u8 isoc_split_pos;
    u16 isoc_frame_index;
    u16 isoc_split_offset;
    u16 isoc_td_last;
    u16 isoc_td_first;
    u32 ssplit_out_xfer_count;
    u8 error_count;
    u8 n_desc;
    u16 isoc_frame_index_last;
    u16 num_naks;
    struct dwc2_hcd_urb * urb;
    struct dwc2_qh * qh;
    struct list_head qtd_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dwc2_qtd {
    enum dwc2_control_phase control_phase;
    u8 in_process;
    u8 data_toggle;
    u8 complete_split;
    u8 isoc_split_pos;
    u16 isoc_frame_index;
    u16 isoc_split_offset;
    u16 isoc_td_last;
    u16 isoc_td_first;
    u32 ssplit_out_xfer_count;
    u8 error_count;
    u8 n_desc;
    u16 isoc_frame_index_last;
    u16 num_naks;
    struct dwc2_hcd_urb * urb;
    struct dwc2_qh * qh;
    struct list_head qtd_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dwc2_qtd {
    enum dwc2_control_phase control_phase;
    u8 in_process;
    u8 data_toggle;
    u8 complete_split;
    u8 isoc_split_pos;
    u16 isoc_frame_index;
    u16 isoc_split_offset;
    u16 isoc_td_last;
    u16 isoc_td_first;
    u32 ssplit_out_xfer_count;
    u8 error_count;
    u8 n_desc;
    u16 isoc_frame_index_last;
    u16 num_naks;
    struct dwc2_hcd_urb * urb;
    struct dwc2_qh * qh;
    struct list_head qtd_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dwc2_qtd {
    enum dwc2_control_phase control_phase;
    u8 in_process;
    u8 data_toggle;
    u8 complete_split;
    u8 isoc_split_pos;
    u16 isoc_frame_index;
    u16 isoc_split_offset;
    u16 isoc_td_last;
    u16 isoc_td_first;
    u32 ssplit_out_xfer_count;
    u8 error_count;
    u8 n_desc;
    u16 isoc_frame_index_last;
    u16 num_naks;
    struct dwc2_hcd_urb * urb;
    struct dwc2_qh * qh;
    struct list_head qtd_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dwc2_qtd {
    enum dwc2_control_phase control_phase;
    u8 in_process;
    u8 data_toggle;
    u8 complete_split;
    u8 isoc_split_pos;
    u16 isoc_frame_index;
    u16 isoc_split_offset;
    u16 isoc_td_last;
    u16 isoc_td_first;
    u32 ssplit_out_xfer_count;
    u8 error_count;
    u8 n_desc;
    u16 isoc_frame_index_last;
    u16 num_naks;
    struct dwc2_hcd_urb * urb;
    struct dwc2_qh * qh;
    struct list_head qtd_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dwc2_qtd {
    enum dwc2_control_phase control_phase;
    u8 in_process;
    u8 data_toggle;
    u8 complete_split;
    u8 isoc_split_pos;
    u16 isoc_frame_index;
    u16 isoc_split_offset;
    u16 isoc_td_last;
    u16 isoc_td_first;
    u32 ssplit_out_xfer_count;
    u8 error_count;
    u8 n_desc;
    u16 isoc_frame_index_last;
    u16 num_naks;
    struct dwc2_hcd_urb * urb;
    struct dwc2_qh * qh;
    struct list_head qtd_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dwc2_qtd {
    enum dwc2_control_phase control_phase;
    u8 in_process;
    u8 data_toggle;
    u8 complete_split;
    u8 isoc_split_pos;
    u16 isoc_frame_index;
    u16 isoc_split_offset;
    u16 isoc_td_last;
    u16 isoc_td_first;
    u32 ssplit_out_xfer_count;
    u8 error_count;
    u8 n_desc;
    u16 isoc_frame_index_last;
    u16 num_naks;
    struct dwc2_hcd_urb * urb;
    struct dwc2_qh * qh;
    struct list_head qtd_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dwc2_qtd {
    enum dwc2_control_phase control_phase;
    u8 in_process;
    u8 data_toggle;
    u8 complete_split;
    u8 isoc_split_pos;
    u16 isoc_frame_index;
    u16 isoc_split_offset;
    u16 isoc_td_last;
    u16 isoc_td_first;
    u32 ssplit_out_xfer_count;
    u8 error_count;
    u8 n_desc;
    u16 isoc_frame_index_last;
    u16 num_naks;
    struct dwc2_hcd_urb * urb;
    struct dwc2_qh * qh;
    struct list_head qtd_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dwc2_qtd {
    enum dwc2_control_phase control_phase;
    u8 in_process;
    u8 data_toggle;
    u8 complete_split;
    u8 isoc_split_pos;
    u16 isoc_frame_index;
    u16 isoc_split_offset;
    u16 isoc_td_last;
    u16 isoc_td_first;
    u32 ssplit_out_xfer_count;
    u8 error_count;
    u8 n_desc;
    u16 isoc_frame_index_last;
    u16 num_naks;
    struct dwc2_hcd_urb * urb;
    struct dwc2_qh * qh;
    struct list_head qtd_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dwc2_qtd {
    enum dwc2_control_phase control_phase;
    u8 in_process;
    u8 data_toggle;
    u8 complete_split;
    u8 isoc_split_pos;
    u16 isoc_frame_index;
    u16 isoc_split_offset;
    u16 isoc_td_last;
    u16 isoc_td_first;
    u32 ssplit_out_xfer_count;
    u8 error_count;
    u8 n_desc;
    u16 isoc_frame_index_last;
    u16 num_naks;
    struct dwc2_hcd_urb * urb;
    struct dwc2_qh * qh;
    struct list_head qtd_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dwc2_qtd {
    enum dwc2_control_phase control_phase;
    u8 in_process;
    u8 data_toggle;
    u8 complete_split;
    u8 isoc_split_pos;
    u16 isoc_frame_index;
    u16 isoc_split_offset;
    u16 isoc_td_last;
    u16 isoc_td_first;
    u32 ssplit_out_xfer_count;
    u8 error_count;
    u8 n_desc;
    u16 isoc_frame_index_last;
    u16 num_naks;
    struct dwc2_hcd_urb * urb;
    struct dwc2_qh * qh;
    struct list_head qtd_list_entry;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct dwc2_qtd {
    enum dwc2_control_phase control_phase;
    u8 in_process;
    u8 data_toggle;
    u8 complete_split;
    u8 isoc_split_pos;
    u16 isoc_frame_index;
    u16 isoc_split_offset;
    u16 isoc_td_last;
    u16 isoc_td_first;
    u32 ssplit_out_xfer_count;
    u8 error_count;
    u8 n_desc;
    u16 isoc_frame_index_last;
    u16 num_naks;
    struct dwc2_hcd_urb * urb;
    struct dwc2_qh * qh;
    struct list_head qtd_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dwc2_qtd {
    enum dwc2_control_phase control_phase;
    u8 in_process;
    u8 data_toggle;
    u8 complete_split;
    u8 isoc_split_pos;
    u16 isoc_frame_index;
    u16 isoc_split_offset;
    u16 isoc_td_last;
    u16 isoc_td_first;
    u32 ssplit_out_xfer_count;
    u8 error_count;
    u8 n_desc;
    u16 isoc_frame_index_last;
    u16 num_naks;
    struct dwc2_hcd_urb * urb;
    struct dwc2_qh * qh;
    struct list_head qtd_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dwc2_qtd {
    enum dwc2_control_phase control_phase;
    u8 in_process;
    u8 data_toggle;
    u8 complete_split;
    u8 isoc_split_pos;
    u16 isoc_frame_index;
    u16 isoc_split_offset;
    u16 isoc_td_last;
    u16 isoc_td_first;
    u32 ssplit_out_xfer_count;
    u8 error_count;
    u8 n_desc;
    u16 isoc_frame_index_last;
    u16 num_naks;
    struct dwc2_hcd_urb * urb;
    struct dwc2_qh * qh;
    struct list_head qtd_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dwc2_qtd {
    enum dwc2_control_phase control_phase;
    u8 in_process;
    u8 data_toggle;
    u8 complete_split;
    u8 isoc_split_pos;
    u16 isoc_frame_index;
    u16 isoc_split_offset;
    u16 isoc_td_last;
    u16 isoc_td_first;
    u32 ssplit_out_xfer_count;
    u8 error_count;
    u8 n_desc;
    u16 isoc_frame_index_last;
    u16 num_naks;
    struct dwc2_hcd_urb * urb;
    struct dwc2_qh * qh;
    struct list_head qtd_list_entry;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct dwc2_qtd {
    enum dwc2_control_phase control_phase;
    u8 in_process;
    u8 data_toggle;
    u8 complete_split;
    u8 isoc_split_pos;
    u16 isoc_frame_index;
    u16 isoc_split_offset;
    u16 isoc_td_last;
    u16 isoc_td_first;
    u32 ssplit_out_xfer_count;
    u8 error_count;
    u8 n_desc;
    u16 isoc_frame_index_last;
    u16 num_naks;
    struct dwc2_hcd_urb * urb;
    struct dwc2_qh * qh;
    struct list_head qtd_list_entry;
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dwc2_qtd {
    enum dwc2_control_phase control_phase;
    u8 in_process;
    u8 data_toggle;
    u8 complete_split;
    u8 isoc_split_pos;
    u16 isoc_frame_index;
    u16 isoc_split_offset;
    u16 isoc_td_last;
    u16 isoc_td_first;
    u32 ssplit_out_xfer_count;
    u8 error_count;
    u8 n_desc;
    u16 isoc_frame_index_last;
    u16 num_naks;
    struct dwc2_hcd_urb * urb;
    struct dwc2_qh * qh;
    struct list_head qtd_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dwc2_qtd {
    enum dwc2_control_phase control_phase;
    u8 in_process;
    u8 data_toggle;
    u8 complete_split;
    u8 isoc_split_pos;
    u16 isoc_frame_index;
    u16 isoc_split_offset;
    u16 isoc_td_last;
    u16 isoc_td_first;
    u32 ssplit_out_xfer_count;
    u8 error_count;
    u8 n_desc;
    u16 isoc_frame_index_last;
    u16 num_naks;
    struct dwc2_hcd_urb * urb;
    struct dwc2_qh * qh;
    struct list_head qtd_list_entry;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u16 isoc_td_last</code>
</li>
<li>
<b>Field added. </b>
<code>u16 isoc_td_first</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u16 num_naks</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct dwc2_qtd {
    enum dwc2_control_phase control_phase;
    u8 in_process;
    u8 data_toggle;
    u8 complete_split;
    u8 isoc_split_pos;
    u16 isoc_frame_index;
    u16 isoc_split_offset;
    u16 isoc_td_last;
    u16 isoc_td_first;
    u32 ssplit_out_xfer_count;
    u8 error_count;
    u8 n_desc;
    u16 isoc_frame_index_last;
    u16 num_naks;
    struct dwc2_hcd_urb * urb;
    struct dwc2_qh * qh;
    struct list_head qtd_list_entry;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
