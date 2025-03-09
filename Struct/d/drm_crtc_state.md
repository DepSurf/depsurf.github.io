# Struct: <code>drm_crtc_state</code>

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
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct drm_crtc_state {
    struct drm_crtc * crtc;
    bool enable;
    bool active;
    bool planes_changed;
    bool mode_changed;
    bool active_changed;
    bool connectors_changed;
    bool zpos_changed;
    bool color_mgmt_changed;
    bool no_vblank;
    u32 plane_mask;
    u32 connector_mask;
    u32 encoder_mask;
    struct drm_display_mode adjusted_mode;
    struct drm_display_mode mode;
    struct drm_property_blob * mode_blob;
    struct drm_property_blob * degamma_lut;
    struct drm_property_blob * ctm;
    struct drm_property_blob * gamma_lut;
    u32 target_vblank;
    bool async_flip;
    bool vrr_enabled;
    bool self_refresh_active;
    enum drm_scaling_filter scaling_filter;
    struct drm_pending_vblank_event * event;
    struct drm_crtc_commit * commit;
    struct drm_atomic_state * state;
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
struct drm_crtc_state {
    struct drm_crtc * crtc;
    bool enable;
    bool active;
    bool planes_changed;
    bool mode_changed;
    bool active_changed;
    bool connectors_changed;
    bool zpos_changed;
    bool color_mgmt_changed;
    bool no_vblank;
    u32 plane_mask;
    u32 connector_mask;
    u32 encoder_mask;
    struct drm_display_mode adjusted_mode;
    struct drm_display_mode mode;
    struct drm_property_blob * mode_blob;
    struct drm_property_blob * degamma_lut;
    struct drm_property_blob * ctm;
    struct drm_property_blob * gamma_lut;
    u32 target_vblank;
    bool async_flip;
    bool vrr_enabled;
    bool self_refresh_active;
    enum drm_scaling_filter scaling_filter;
    struct drm_pending_vblank_event * event;
    struct drm_crtc_commit * commit;
    struct drm_atomic_state * state;
}
```
</details>
</li>
</ul>
