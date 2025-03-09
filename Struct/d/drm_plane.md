# Struct: <code>drm_plane</code>

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
struct drm_plane {
    struct drm_device * dev;
    struct list_head head;
    char * name;
    struct drm_modeset_lock mutex;
    struct drm_mode_object base;
    uint32_t possible_crtcs;
    uint32_t * format_types;
    unsigned int format_count;
    bool format_default;
    uint64_t * modifiers;
    unsigned int modifier_count;
    struct drm_crtc * crtc;
    struct drm_framebuffer * fb;
    struct drm_framebuffer * old_fb;
    const struct drm_plane_funcs * funcs;
    struct drm_object_properties properties;
    enum drm_plane_type type;
    unsigned int index;
    const struct drm_plane_helper_funcs * helper_private;
    struct drm_plane_state * state;
    struct drm_property * alpha_property;
    struct drm_property * zpos_property;
    struct drm_property * rotation_property;
    struct drm_property * blend_mode_property;
    struct drm_property * color_encoding_property;
    struct drm_property * color_range_property;
    struct drm_property * scaling_filter_property;
    struct drm_property * hotspot_x_property;
    struct drm_property * hotspot_y_property;
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
struct drm_plane {
    struct drm_device * dev;
    struct list_head head;
    char * name;
    struct drm_modeset_lock mutex;
    struct drm_mode_object base;
    uint32_t possible_crtcs;
    uint32_t * format_types;
    unsigned int format_count;
    bool format_default;
    uint64_t * modifiers;
    unsigned int modifier_count;
    struct drm_crtc * crtc;
    struct drm_framebuffer * fb;
    struct drm_framebuffer * old_fb;
    const struct drm_plane_funcs * funcs;
    struct drm_object_properties properties;
    enum drm_plane_type type;
    unsigned int index;
    const struct drm_plane_helper_funcs * helper_private;
    struct drm_plane_state * state;
    struct drm_property * alpha_property;
    struct drm_property * zpos_property;
    struct drm_property * rotation_property;
    struct drm_property * blend_mode_property;
    struct drm_property * color_encoding_property;
    struct drm_property * color_range_property;
    struct drm_property * scaling_filter_property;
    struct drm_property * hotspot_x_property;
    struct drm_property * hotspot_y_property;
}
```
</details>
</li>
</ul>
