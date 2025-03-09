# Struct: <code>drm_connector_state</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct drm_connector_state {
    struct drm_connector * connector;
    struct drm_crtc * crtc;
    struct drm_encoder * best_encoder;
    enum drm_link_status link_status;
    struct drm_atomic_state * state;
    struct drm_crtc_commit * commit;
    struct drm_tv_connector_state tv;
    bool self_refresh_aware;
    enum hdmi_picture_aspect picture_aspect_ratio;
    unsigned int content_type;
    unsigned int scaling_mode;
    unsigned int content_protection;
    u32 colorspace;
    struct drm_writeback_job * writeback_job;
    u8 max_requested_bpc;
    u8 max_bpc;
    struct drm_property_blob * hdr_output_metadata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct drm_connector_state {
    struct drm_connector * connector;
    struct drm_crtc * crtc;
    struct drm_encoder * best_encoder;
    enum drm_link_status link_status;
    struct drm_atomic_state * state;
    struct drm_crtc_commit * commit;
    struct drm_tv_connector_state tv;
    bool self_refresh_aware;
    enum hdmi_picture_aspect picture_aspect_ratio;
    unsigned int content_type;
    unsigned int hdcp_content_type;
    unsigned int scaling_mode;
    unsigned int content_protection;
    u32 colorspace;
    struct drm_writeback_job * writeback_job;
    u8 max_requested_bpc;
    u8 max_bpc;
    struct drm_property_blob * hdr_output_metadata;
}
```
</details>
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
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct drm_connector_state {
    struct drm_connector * connector;
    struct drm_crtc * crtc;
    struct drm_encoder * best_encoder;
    enum drm_link_status link_status;
    struct drm_atomic_state * state;
    struct drm_crtc_commit * commit;
    struct drm_tv_connector_state tv;
    bool self_refresh_aware;
    enum hdmi_picture_aspect picture_aspect_ratio;
    unsigned int content_type;
    unsigned int hdcp_content_type;
    unsigned int scaling_mode;
    unsigned int content_protection;
    enum drm_colorspace colorspace;
    struct drm_writeback_job * writeback_job;
    u8 max_requested_bpc;
    u8 max_bpc;
    enum drm_privacy_screen_status privacy_screen_sw_state;
    struct drm_property_blob * hdr_output_metadata;
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
struct drm_connector_state {
    struct drm_connector * connector;
    struct drm_crtc * crtc;
    struct drm_encoder * best_encoder;
    enum drm_link_status link_status;
    struct drm_atomic_state * state;
    struct drm_crtc_commit * commit;
    struct drm_tv_connector_state tv;
    bool self_refresh_aware;
    enum hdmi_picture_aspect picture_aspect_ratio;
    unsigned int content_type;
    unsigned int hdcp_content_type;
    unsigned int scaling_mode;
    unsigned int content_protection;
    u32 colorspace;
    struct drm_writeback_job * writeback_job;
    u8 max_requested_bpc;
    u8 max_bpc;
    struct drm_property_blob * hdr_output_metadata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct drm_connector_state {
    struct drm_connector * connector;
    struct drm_crtc * crtc;
    struct drm_encoder * best_encoder;
    enum drm_link_status link_status;
    struct drm_atomic_state * state;
    struct drm_crtc_commit * commit;
    struct drm_tv_connector_state tv;
    bool self_refresh_aware;
    enum hdmi_picture_aspect picture_aspect_ratio;
    unsigned int content_type;
    unsigned int hdcp_content_type;
    unsigned int scaling_mode;
    unsigned int content_protection;
    u32 colorspace;
    struct drm_writeback_job * writeback_job;
    u8 max_requested_bpc;
    u8 max_bpc;
    struct drm_property_blob * hdr_output_metadata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct drm_connector_state {
    struct drm_connector * connector;
    struct drm_crtc * crtc;
    struct drm_encoder * best_encoder;
    enum drm_link_status link_status;
    struct drm_atomic_state * state;
    struct drm_crtc_commit * commit;
    struct drm_tv_connector_state tv;
    bool self_refresh_aware;
    enum hdmi_picture_aspect picture_aspect_ratio;
    unsigned int content_type;
    unsigned int hdcp_content_type;
    unsigned int scaling_mode;
    unsigned int content_protection;
    u32 colorspace;
    struct drm_writeback_job * writeback_job;
    u8 max_requested_bpc;
    u8 max_bpc;
    struct drm_property_blob * hdr_output_metadata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct drm_connector_state {
    struct drm_connector * connector;
    struct drm_crtc * crtc;
    struct drm_encoder * best_encoder;
    enum drm_link_status link_status;
    struct drm_atomic_state * state;
    struct drm_crtc_commit * commit;
    struct drm_tv_connector_state tv;
    bool self_refresh_aware;
    enum hdmi_picture_aspect picture_aspect_ratio;
    unsigned int content_type;
    unsigned int hdcp_content_type;
    unsigned int scaling_mode;
    unsigned int content_protection;
    u32 colorspace;
    struct drm_writeback_job * writeback_job;
    u8 max_requested_bpc;
    u8 max_bpc;
    struct drm_property_blob * hdr_output_metadata;
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
struct drm_connector_state {
    struct drm_connector * connector;
    struct drm_crtc * crtc;
    struct drm_encoder * best_encoder;
    enum drm_link_status link_status;
    struct drm_atomic_state * state;
    struct drm_crtc_commit * commit;
    struct drm_tv_connector_state tv;
    bool self_refresh_aware;
    enum hdmi_picture_aspect picture_aspect_ratio;
    unsigned int content_type;
    unsigned int hdcp_content_type;
    unsigned int scaling_mode;
    unsigned int content_protection;
    u32 colorspace;
    struct drm_writeback_job * writeback_job;
    u8 max_requested_bpc;
    u8 max_bpc;
    struct drm_property_blob * hdr_output_metadata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct drm_connector_state {
    struct drm_connector * connector;
    struct drm_crtc * crtc;
    struct drm_encoder * best_encoder;
    enum drm_link_status link_status;
    struct drm_atomic_state * state;
    struct drm_crtc_commit * commit;
    struct drm_tv_connector_state tv;
    bool self_refresh_aware;
    enum hdmi_picture_aspect picture_aspect_ratio;
    unsigned int content_type;
    unsigned int hdcp_content_type;
    unsigned int scaling_mode;
    unsigned int content_protection;
    u32 colorspace;
    struct drm_writeback_job * writeback_job;
    u8 max_requested_bpc;
    u8 max_bpc;
    struct drm_property_blob * hdr_output_metadata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct drm_connector_state {
    struct drm_connector * connector;
    struct drm_crtc * crtc;
    struct drm_encoder * best_encoder;
    enum drm_link_status link_status;
    struct drm_atomic_state * state;
    struct drm_crtc_commit * commit;
    struct drm_tv_connector_state tv;
    bool self_refresh_aware;
    enum hdmi_picture_aspect picture_aspect_ratio;
    unsigned int content_type;
    unsigned int hdcp_content_type;
    unsigned int scaling_mode;
    unsigned int content_protection;
    u32 colorspace;
    struct drm_writeback_job * writeback_job;
    u8 max_requested_bpc;
    u8 max_bpc;
    struct drm_property_blob * hdr_output_metadata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct drm_connector_state {
    struct drm_connector * connector;
    struct drm_crtc * crtc;
    struct drm_encoder * best_encoder;
    enum drm_link_status link_status;
    struct drm_atomic_state * state;
    struct drm_crtc_commit * commit;
    struct drm_tv_connector_state tv;
    bool self_refresh_aware;
    enum hdmi_picture_aspect picture_aspect_ratio;
    unsigned int content_type;
    unsigned int hdcp_content_type;
    unsigned int scaling_mode;
    unsigned int content_protection;
    u32 colorspace;
    struct drm_writeback_job * writeback_job;
    u8 max_requested_bpc;
    u8 max_bpc;
    struct drm_property_blob * hdr_output_metadata;
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct drm_connector_state {
    struct drm_connector * connector;
    struct drm_crtc * crtc;
    struct drm_encoder * best_encoder;
    enum drm_link_status link_status;
    struct drm_atomic_state * state;
    struct drm_crtc_commit * commit;
    struct drm_tv_connector_state tv;
    bool self_refresh_aware;
    enum hdmi_picture_aspect picture_aspect_ratio;
    unsigned int content_type;
    unsigned int scaling_mode;
    unsigned int content_protection;
    u32 colorspace;
    struct drm_writeback_job * writeback_job;
    u8 max_requested_bpc;
    u8 max_bpc;
    struct drm_property_blob * hdr_output_metadata;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int hdcp_content_type</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct drm_connector_state {
    struct drm_connector * connector;
    struct drm_crtc * crtc;
    struct drm_encoder * best_encoder;
    enum drm_link_status link_status;
    struct drm_atomic_state * state;
    struct drm_crtc_commit * commit;
    struct drm_tv_connector_state tv;
    bool self_refresh_aware;
    enum hdmi_picture_aspect picture_aspect_ratio;
    unsigned int content_type;
    unsigned int hdcp_content_type;
    unsigned int scaling_mode;
    unsigned int content_protection;
    u32 colorspace;
    struct drm_writeback_job * writeback_job;
    u8 max_requested_bpc;
    u8 max_bpc;
    struct drm_property_blob * hdr_output_metadata;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
struct drm_connector_state {
    struct drm_connector * connector;
    struct drm_crtc * crtc;
    struct drm_encoder * best_encoder;
    enum drm_link_status link_status;
    struct drm_atomic_state * state;
    struct drm_crtc_commit * commit;
    struct drm_tv_connector_state tv;
    bool self_refresh_aware;
    enum hdmi_picture_aspect picture_aspect_ratio;
    unsigned int content_type;
    unsigned int hdcp_content_type;
    unsigned int scaling_mode;
    unsigned int content_protection;
    enum drm_colorspace colorspace;
    struct drm_writeback_job * writeback_job;
    u8 max_requested_bpc;
    u8 max_bpc;
    enum drm_privacy_screen_status privacy_screen_sw_state;
    struct drm_property_blob * hdr_output_metadata;
}
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
