# Struct: <code>drm_plane_state</code>

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
struct drm_plane_state {
    struct drm_plane * plane;
    struct drm_crtc * crtc;
    struct drm_framebuffer * fb;
    struct dma_fence * fence;
    int32_t crtc_x;
    int32_t crtc_y;
    uint32_t crtc_w;
    uint32_t crtc_h;
    uint32_t src_x;
    uint32_t src_y;
    uint32_t src_h;
    uint32_t src_w;
    int32_t hotspot_x;
    int32_t hotspot_y;
    u16 alpha;
    uint16_t pixel_blend_mode;
    unsigned int rotation;
    unsigned int zpos;
    unsigned int normalized_zpos;
    enum drm_color_encoding color_encoding;
    enum drm_color_range color_range;
    struct drm_property_blob * fb_damage_clips;
    bool ignore_damage_clips;
    struct drm_rect src;
    struct drm_rect dst;
    bool visible;
    enum drm_scaling_filter scaling_filter;
    struct drm_crtc_commit * commit;
    struct drm_atomic_state * state;
    bool color_mgmt_changed;
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
struct drm_plane_state {
    struct drm_plane * plane;
    struct drm_crtc * crtc;
    struct drm_framebuffer * fb;
    struct dma_fence * fence;
    int32_t crtc_x;
    int32_t crtc_y;
    uint32_t crtc_w;
    uint32_t crtc_h;
    uint32_t src_x;
    uint32_t src_y;
    uint32_t src_h;
    uint32_t src_w;
    int32_t hotspot_x;
    int32_t hotspot_y;
    u16 alpha;
    uint16_t pixel_blend_mode;
    unsigned int rotation;
    unsigned int zpos;
    unsigned int normalized_zpos;
    enum drm_color_encoding color_encoding;
    enum drm_color_range color_range;
    struct drm_property_blob * fb_damage_clips;
    bool ignore_damage_clips;
    struct drm_rect src;
    struct drm_rect dst;
    bool visible;
    enum drm_scaling_filter scaling_filter;
    struct drm_crtc_commit * commit;
    struct drm_atomic_state * state;
    bool color_mgmt_changed;
}
```
</details>
</li>
</ul>
