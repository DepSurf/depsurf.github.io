# Struct: <code>drm_dsc_config</code>

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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct drm_dsc_config {
    u8 line_buf_depth;
    u8 bits_per_component;
    bool convert_rgb;
    u8 slice_count;
    u16 slice_width;
    u16 slice_height;
    bool simple_422;
    u16 pic_width;
    u16 pic_height;
    u8 rc_tgt_offset_high;
    u8 rc_tgt_offset_low;
    u16 bits_per_pixel;
    u8 rc_edge_factor;
    u8 rc_quant_incr_limit1;
    u8 rc_quant_incr_limit0;
    u16 initial_xmit_delay;
    u16 initial_dec_delay;
    bool block_pred_enable;
    u8 first_line_bpg_offset;
    u16 initial_offset;
    u16[14] rc_buf_thresh;
    struct drm_dsc_rc_range_parameters[15] rc_range_params;
    u16 rc_model_size;
    u8 flatness_min_qp;
    u8 flatness_max_qp;
    u8 initial_scale_value;
    u16 scale_decrement_interval;
    u16 scale_increment_interval;
    u16 nfl_bpg_offset;
    u16 slice_bpg_offset;
    u16 final_offset;
    bool vbr_enable;
    u8 mux_word_size;
    u16 slice_chunk_size;
    u16 rc_bits;
    u8 dsc_version_minor;
    u8 dsc_version_major;
    bool native_422;
    bool native_420;
    u8 second_line_bpg_offset;
    u16 nsl_bpg_offset;
    u16 second_line_offset_adj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct drm_dsc_config {
    u8 line_buf_depth;
    u8 bits_per_component;
    bool convert_rgb;
    u8 slice_count;
    u16 slice_width;
    u16 slice_height;
    bool simple_422;
    u16 pic_width;
    u16 pic_height;
    u8 rc_tgt_offset_high;
    u8 rc_tgt_offset_low;
    u16 bits_per_pixel;
    u8 rc_edge_factor;
    u8 rc_quant_incr_limit1;
    u8 rc_quant_incr_limit0;
    u16 initial_xmit_delay;
    u16 initial_dec_delay;
    bool block_pred_enable;
    u8 first_line_bpg_offset;
    u16 initial_offset;
    u16[14] rc_buf_thresh;
    struct drm_dsc_rc_range_parameters[15] rc_range_params;
    u16 rc_model_size;
    u8 flatness_min_qp;
    u8 flatness_max_qp;
    u8 initial_scale_value;
    u16 scale_decrement_interval;
    u16 scale_increment_interval;
    u16 nfl_bpg_offset;
    u16 slice_bpg_offset;
    u16 final_offset;
    bool vbr_enable;
    u8 mux_word_size;
    u16 slice_chunk_size;
    u16 rc_bits;
    u8 dsc_version_minor;
    u8 dsc_version_major;
    bool native_422;
    bool native_420;
    u8 second_line_bpg_offset;
    u16 nsl_bpg_offset;
    u16 second_line_offset_adj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct drm_dsc_config {
    u8 line_buf_depth;
    u8 bits_per_component;
    bool convert_rgb;
    u8 slice_count;
    u16 slice_width;
    u16 slice_height;
    bool simple_422;
    u16 pic_width;
    u16 pic_height;
    u8 rc_tgt_offset_high;
    u8 rc_tgt_offset_low;
    u16 bits_per_pixel;
    u8 rc_edge_factor;
    u8 rc_quant_incr_limit1;
    u8 rc_quant_incr_limit0;
    u16 initial_xmit_delay;
    u16 initial_dec_delay;
    bool block_pred_enable;
    u8 first_line_bpg_offset;
    u16 initial_offset;
    u16[14] rc_buf_thresh;
    struct drm_dsc_rc_range_parameters[15] rc_range_params;
    u16 rc_model_size;
    u8 flatness_min_qp;
    u8 flatness_max_qp;
    u8 initial_scale_value;
    u16 scale_decrement_interval;
    u16 scale_increment_interval;
    u16 nfl_bpg_offset;
    u16 slice_bpg_offset;
    u16 final_offset;
    bool vbr_enable;
    u8 mux_word_size;
    u16 slice_chunk_size;
    u16 rc_bits;
    u8 dsc_version_minor;
    u8 dsc_version_major;
    bool native_422;
    bool native_420;
    u8 second_line_bpg_offset;
    u16 nsl_bpg_offset;
    u16 second_line_offset_adj;
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
struct drm_dsc_config {
    u8 line_buf_depth;
    u8 bits_per_component;
    bool convert_rgb;
    u8 slice_count;
    u16 slice_width;
    u16 slice_height;
    bool simple_422;
    u16 pic_width;
    u16 pic_height;
    u8 rc_tgt_offset_high;
    u8 rc_tgt_offset_low;
    u16 bits_per_pixel;
    u8 rc_edge_factor;
    u8 rc_quant_incr_limit1;
    u8 rc_quant_incr_limit0;
    u16 initial_xmit_delay;
    u16 initial_dec_delay;
    bool block_pred_enable;
    u8 first_line_bpg_offset;
    u16 initial_offset;
    u16[14] rc_buf_thresh;
    struct drm_dsc_rc_range_parameters[15] rc_range_params;
    u16 rc_model_size;
    u8 flatness_min_qp;
    u8 flatness_max_qp;
    u8 initial_scale_value;
    u16 scale_decrement_interval;
    u16 scale_increment_interval;
    u16 nfl_bpg_offset;
    u16 slice_bpg_offset;
    u16 final_offset;
    bool vbr_enable;
    u8 mux_word_size;
    u16 slice_chunk_size;
    u16 rc_bits;
    u8 dsc_version_minor;
    u8 dsc_version_major;
    bool native_422;
    bool native_420;
    u8 second_line_bpg_offset;
    u16 nsl_bpg_offset;
    u16 second_line_offset_adj;
}
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
