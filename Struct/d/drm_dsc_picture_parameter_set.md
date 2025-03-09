# Struct: <code>drm_dsc_picture_parameter_set</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct drm_dsc_picture_parameter_set {
    u8 dsc_version;
    u8 pps_identifier;
    u8 pps_reserved;
    u8 pps_3;
    u8 pps_4;
    u8 bits_per_pixel_low;
    __be16 pic_height;
    __be16 pic_width;
    __be16 slice_height;
    __be16 slice_width;
    __be16 chunk_size;
    u8 initial_xmit_delay_high;
    u8 initial_xmit_delay_low;
    __be16 initial_dec_delay;
    u8 pps20_reserved;
    u8 initial_scale_value;
    __be16 scale_increment_interval;
    u8 scale_decrement_interval_high;
    u8 scale_decrement_interval_low;
    u8 pps26_reserved;
    u8 first_line_bpg_offset;
    __be16 nfl_bpg_offset;
    __be16 slice_bpg_offset;
    __be16 initial_offset;
    __be16 final_offset;
    u8 flatness_min_qp;
    u8 flatness_max_qp;
    __be16 rc_model_size;
    u8 rc_edge_factor;
    u8 rc_quant_incr_limit0;
    u8 rc_quant_incr_limit1;
    u8 rc_tgt_offset;
    u8[14] rc_buf_thresh;
    __be16[15] rc_range_parameters;
    u8 native_422_420;
    u8 second_line_bpg_offset;
    __be16 nsl_bpg_offset;
    __be16 second_line_offset_adj;
    u32 pps_long_94_reserved;
    u32 pps_long_98_reserved;
    u32 pps_long_102_reserved;
    u32 pps_long_106_reserved;
    u32 pps_long_110_reserved;
    u32 pps_long_114_reserved;
    u32 pps_long_118_reserved;
    u32 pps_long_122_reserved;
    __be16 pps_short_126_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct drm_dsc_picture_parameter_set {
    u8 dsc_version;
    u8 pps_identifier;
    u8 pps_reserved;
    u8 pps_3;
    u8 pps_4;
    u8 bits_per_pixel_low;
    __be16 pic_height;
    __be16 pic_width;
    __be16 slice_height;
    __be16 slice_width;
    __be16 chunk_size;
    u8 initial_xmit_delay_high;
    u8 initial_xmit_delay_low;
    __be16 initial_dec_delay;
    u8 pps20_reserved;
    u8 initial_scale_value;
    __be16 scale_increment_interval;
    u8 scale_decrement_interval_high;
    u8 scale_decrement_interval_low;
    u8 pps26_reserved;
    u8 first_line_bpg_offset;
    __be16 nfl_bpg_offset;
    __be16 slice_bpg_offset;
    __be16 initial_offset;
    __be16 final_offset;
    u8 flatness_min_qp;
    u8 flatness_max_qp;
    __be16 rc_model_size;
    u8 rc_edge_factor;
    u8 rc_quant_incr_limit0;
    u8 rc_quant_incr_limit1;
    u8 rc_tgt_offset;
    u8[14] rc_buf_thresh;
    __be16[15] rc_range_parameters;
    u8 native_422_420;
    u8 second_line_bpg_offset;
    __be16 nsl_bpg_offset;
    __be16 second_line_offset_adj;
    u32 pps_long_94_reserved;
    u32 pps_long_98_reserved;
    u32 pps_long_102_reserved;
    u32 pps_long_106_reserved;
    u32 pps_long_110_reserved;
    u32 pps_long_114_reserved;
    u32 pps_long_118_reserved;
    u32 pps_long_122_reserved;
    __be16 pps_short_126_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct drm_dsc_picture_parameter_set {
    u8 dsc_version;
    u8 pps_identifier;
    u8 pps_reserved;
    u8 pps_3;
    u8 pps_4;
    u8 bits_per_pixel_low;
    __be16 pic_height;
    __be16 pic_width;
    __be16 slice_height;
    __be16 slice_width;
    __be16 chunk_size;
    u8 initial_xmit_delay_high;
    u8 initial_xmit_delay_low;
    __be16 initial_dec_delay;
    u8 pps20_reserved;
    u8 initial_scale_value;
    __be16 scale_increment_interval;
    u8 scale_decrement_interval_high;
    u8 scale_decrement_interval_low;
    u8 pps26_reserved;
    u8 first_line_bpg_offset;
    __be16 nfl_bpg_offset;
    __be16 slice_bpg_offset;
    __be16 initial_offset;
    __be16 final_offset;
    u8 flatness_min_qp;
    u8 flatness_max_qp;
    __be16 rc_model_size;
    u8 rc_edge_factor;
    u8 rc_quant_incr_limit0;
    u8 rc_quant_incr_limit1;
    u8 rc_tgt_offset;
    u8[14] rc_buf_thresh;
    __be16[15] rc_range_parameters;
    u8 native_422_420;
    u8 second_line_bpg_offset;
    __be16 nsl_bpg_offset;
    __be16 second_line_offset_adj;
    u32 pps_long_94_reserved;
    u32 pps_long_98_reserved;
    u32 pps_long_102_reserved;
    u32 pps_long_106_reserved;
    u32 pps_long_110_reserved;
    u32 pps_long_114_reserved;
    u32 pps_long_118_reserved;
    u32 pps_long_122_reserved;
    __be16 pps_short_126_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct drm_dsc_picture_parameter_set {
    u8 dsc_version;
    u8 pps_identifier;
    u8 pps_reserved;
    u8 pps_3;
    u8 pps_4;
    u8 bits_per_pixel_low;
    __be16 pic_height;
    __be16 pic_width;
    __be16 slice_height;
    __be16 slice_width;
    __be16 chunk_size;
    u8 initial_xmit_delay_high;
    u8 initial_xmit_delay_low;
    __be16 initial_dec_delay;
    u8 pps20_reserved;
    u8 initial_scale_value;
    __be16 scale_increment_interval;
    u8 scale_decrement_interval_high;
    u8 scale_decrement_interval_low;
    u8 pps26_reserved;
    u8 first_line_bpg_offset;
    __be16 nfl_bpg_offset;
    __be16 slice_bpg_offset;
    __be16 initial_offset;
    __be16 final_offset;
    u8 flatness_min_qp;
    u8 flatness_max_qp;
    __be16 rc_model_size;
    u8 rc_edge_factor;
    u8 rc_quant_incr_limit0;
    u8 rc_quant_incr_limit1;
    u8 rc_tgt_offset;
    u8[14] rc_buf_thresh;
    __be16[15] rc_range_parameters;
    u8 native_422_420;
    u8 second_line_bpg_offset;
    __be16 nsl_bpg_offset;
    __be16 second_line_offset_adj;
    u32 pps_long_94_reserved;
    u32 pps_long_98_reserved;
    u32 pps_long_102_reserved;
    u32 pps_long_106_reserved;
    u32 pps_long_110_reserved;
    u32 pps_long_114_reserved;
    u32 pps_long_118_reserved;
    u32 pps_long_122_reserved;
    __be16 pps_short_126_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct drm_dsc_picture_parameter_set {
    u8 dsc_version;
    u8 pps_identifier;
    u8 pps_reserved;
    u8 pps_3;
    u8 pps_4;
    u8 bits_per_pixel_low;
    __be16 pic_height;
    __be16 pic_width;
    __be16 slice_height;
    __be16 slice_width;
    __be16 chunk_size;
    u8 initial_xmit_delay_high;
    u8 initial_xmit_delay_low;
    __be16 initial_dec_delay;
    u8 pps20_reserved;
    u8 initial_scale_value;
    __be16 scale_increment_interval;
    u8 scale_decrement_interval_high;
    u8 scale_decrement_interval_low;
    u8 pps26_reserved;
    u8 first_line_bpg_offset;
    __be16 nfl_bpg_offset;
    __be16 slice_bpg_offset;
    __be16 initial_offset;
    __be16 final_offset;
    u8 flatness_min_qp;
    u8 flatness_max_qp;
    __be16 rc_model_size;
    u8 rc_edge_factor;
    u8 rc_quant_incr_limit0;
    u8 rc_quant_incr_limit1;
    u8 rc_tgt_offset;
    u8[14] rc_buf_thresh;
    __be16[15] rc_range_parameters;
    u8 native_422_420;
    u8 second_line_bpg_offset;
    __be16 nsl_bpg_offset;
    __be16 second_line_offset_adj;
    u32 pps_long_94_reserved;
    u32 pps_long_98_reserved;
    u32 pps_long_102_reserved;
    u32 pps_long_106_reserved;
    u32 pps_long_110_reserved;
    u32 pps_long_114_reserved;
    u32 pps_long_118_reserved;
    u32 pps_long_122_reserved;
    __be16 pps_short_126_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct drm_dsc_picture_parameter_set {
    u8 dsc_version;
    u8 pps_identifier;
    u8 pps_reserved;
    u8 pps_3;
    u8 pps_4;
    u8 bits_per_pixel_low;
    __be16 pic_height;
    __be16 pic_width;
    __be16 slice_height;
    __be16 slice_width;
    __be16 chunk_size;
    u8 initial_xmit_delay_high;
    u8 initial_xmit_delay_low;
    __be16 initial_dec_delay;
    u8 pps20_reserved;
    u8 initial_scale_value;
    __be16 scale_increment_interval;
    u8 scale_decrement_interval_high;
    u8 scale_decrement_interval_low;
    u8 pps26_reserved;
    u8 first_line_bpg_offset;
    __be16 nfl_bpg_offset;
    __be16 slice_bpg_offset;
    __be16 initial_offset;
    __be16 final_offset;
    u8 flatness_min_qp;
    u8 flatness_max_qp;
    __be16 rc_model_size;
    u8 rc_edge_factor;
    u8 rc_quant_incr_limit0;
    u8 rc_quant_incr_limit1;
    u8 rc_tgt_offset;
    u8[14] rc_buf_thresh;
    __be16[15] rc_range_parameters;
    u8 native_422_420;
    u8 second_line_bpg_offset;
    __be16 nsl_bpg_offset;
    __be16 second_line_offset_adj;
    u32 pps_long_94_reserved;
    u32 pps_long_98_reserved;
    u32 pps_long_102_reserved;
    u32 pps_long_106_reserved;
    u32 pps_long_110_reserved;
    u32 pps_long_114_reserved;
    u32 pps_long_118_reserved;
    u32 pps_long_122_reserved;
    __be16 pps_short_126_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct drm_dsc_picture_parameter_set {
    u8 dsc_version;
    u8 pps_identifier;
    u8 pps_reserved;
    u8 pps_3;
    u8 pps_4;
    u8 bits_per_pixel_low;
    __be16 pic_height;
    __be16 pic_width;
    __be16 slice_height;
    __be16 slice_width;
    __be16 chunk_size;
    u8 initial_xmit_delay_high;
    u8 initial_xmit_delay_low;
    __be16 initial_dec_delay;
    u8 pps20_reserved;
    u8 initial_scale_value;
    __be16 scale_increment_interval;
    u8 scale_decrement_interval_high;
    u8 scale_decrement_interval_low;
    u8 pps26_reserved;
    u8 first_line_bpg_offset;
    __be16 nfl_bpg_offset;
    __be16 slice_bpg_offset;
    __be16 initial_offset;
    __be16 final_offset;
    u8 flatness_min_qp;
    u8 flatness_max_qp;
    __be16 rc_model_size;
    u8 rc_edge_factor;
    u8 rc_quant_incr_limit0;
    u8 rc_quant_incr_limit1;
    u8 rc_tgt_offset;
    u8[14] rc_buf_thresh;
    __be16[15] rc_range_parameters;
    u8 native_422_420;
    u8 second_line_bpg_offset;
    __be16 nsl_bpg_offset;
    __be16 second_line_offset_adj;
    u32 pps_long_94_reserved;
    u32 pps_long_98_reserved;
    u32 pps_long_102_reserved;
    u32 pps_long_106_reserved;
    u32 pps_long_110_reserved;
    u32 pps_long_114_reserved;
    u32 pps_long_118_reserved;
    u32 pps_long_122_reserved;
    __be16 pps_short_126_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct drm_dsc_picture_parameter_set {
    u8 dsc_version;
    u8 pps_identifier;
    u8 pps_reserved;
    u8 pps_3;
    u8 pps_4;
    u8 bits_per_pixel_low;
    __be16 pic_height;
    __be16 pic_width;
    __be16 slice_height;
    __be16 slice_width;
    __be16 chunk_size;
    u8 initial_xmit_delay_high;
    u8 initial_xmit_delay_low;
    __be16 initial_dec_delay;
    u8 pps20_reserved;
    u8 initial_scale_value;
    __be16 scale_increment_interval;
    u8 scale_decrement_interval_high;
    u8 scale_decrement_interval_low;
    u8 pps26_reserved;
    u8 first_line_bpg_offset;
    __be16 nfl_bpg_offset;
    __be16 slice_bpg_offset;
    __be16 initial_offset;
    __be16 final_offset;
    u8 flatness_min_qp;
    u8 flatness_max_qp;
    __be16 rc_model_size;
    u8 rc_edge_factor;
    u8 rc_quant_incr_limit0;
    u8 rc_quant_incr_limit1;
    u8 rc_tgt_offset;
    u8[14] rc_buf_thresh;
    __be16[15] rc_range_parameters;
    u8 native_422_420;
    u8 second_line_bpg_offset;
    __be16 nsl_bpg_offset;
    __be16 second_line_offset_adj;
    u32 pps_long_94_reserved;
    u32 pps_long_98_reserved;
    u32 pps_long_102_reserved;
    u32 pps_long_106_reserved;
    u32 pps_long_110_reserved;
    u32 pps_long_114_reserved;
    u32 pps_long_118_reserved;
    u32 pps_long_122_reserved;
    __be16 pps_short_126_reserved;
}
```
</details>
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct drm_dsc_picture_parameter_set {
    u8 dsc_version;
    u8 pps_identifier;
    u8 pps_reserved;
    u8 pps_3;
    u8 pps_4;
    u8 bits_per_pixel_low;
    __be16 pic_height;
    __be16 pic_width;
    __be16 slice_height;
    __be16 slice_width;
    __be16 chunk_size;
    u8 initial_xmit_delay_high;
    u8 initial_xmit_delay_low;
    __be16 initial_dec_delay;
    u8 pps20_reserved;
    u8 initial_scale_value;
    __be16 scale_increment_interval;
    u8 scale_decrement_interval_high;
    u8 scale_decrement_interval_low;
    u8 pps26_reserved;
    u8 first_line_bpg_offset;
    __be16 nfl_bpg_offset;
    __be16 slice_bpg_offset;
    __be16 initial_offset;
    __be16 final_offset;
    u8 flatness_min_qp;
    u8 flatness_max_qp;
    __be16 rc_model_size;
    u8 rc_edge_factor;
    u8 rc_quant_incr_limit0;
    u8 rc_quant_incr_limit1;
    u8 rc_tgt_offset;
    u8[14] rc_buf_thresh;
    __be16[15] rc_range_parameters;
    u8 native_422_420;
    u8 second_line_bpg_offset;
    __be16 nsl_bpg_offset;
    __be16 second_line_offset_adj;
    u32 pps_long_94_reserved;
    u32 pps_long_98_reserved;
    u32 pps_long_102_reserved;
    u32 pps_long_106_reserved;
    u32 pps_long_110_reserved;
    u32 pps_long_114_reserved;
    u32 pps_long_118_reserved;
    u32 pps_long_122_reserved;
    __be16 pps_short_126_reserved;
}
```
</details>
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
