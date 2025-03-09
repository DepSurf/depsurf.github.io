# Struct: <code>drm_bridge_funcs</code>

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
struct drm_bridge_funcs {
    int (*)(struct drm_bridge *, enum drm_bridge_attach_flags) attach;
    void (*)(struct drm_bridge *) detach;
    enum drm_mode_status (*)(struct drm_bridge *, const struct drm_display_info *, const struct drm_display_mode *) mode_valid;
    bool (*)(struct drm_bridge *, const struct drm_display_mode *, struct drm_display_mode *) mode_fixup;
    void (*)(struct drm_bridge *) disable;
    void (*)(struct drm_bridge *) post_disable;
    void (*)(struct drm_bridge *, const struct drm_display_mode *, const struct drm_display_mode *) mode_set;
    void (*)(struct drm_bridge *) pre_enable;
    void (*)(struct drm_bridge *) enable;
    void (*)(struct drm_bridge *, struct drm_bridge_state *) atomic_pre_enable;
    void (*)(struct drm_bridge *, struct drm_bridge_state *) atomic_enable;
    void (*)(struct drm_bridge *, struct drm_bridge_state *) atomic_disable;
    void (*)(struct drm_bridge *, struct drm_bridge_state *) atomic_post_disable;
    struct drm_bridge_state * (*)(struct drm_bridge *) atomic_duplicate_state;
    void (*)(struct drm_bridge *, struct drm_bridge_state *) atomic_destroy_state;
    u32 * (*)(struct drm_bridge *, struct drm_bridge_state *, struct drm_crtc_state *, struct drm_connector_state *, unsigned int *) atomic_get_output_bus_fmts;
    u32 * (*)(struct drm_bridge *, struct drm_bridge_state *, struct drm_crtc_state *, struct drm_connector_state *, u32, unsigned int *) atomic_get_input_bus_fmts;
    int (*)(struct drm_bridge *, struct drm_bridge_state *, struct drm_crtc_state *, struct drm_connector_state *) atomic_check;
    struct drm_bridge_state * (*)(struct drm_bridge *) atomic_reset;
    enum drm_connector_status (*)(struct drm_bridge *) detect;
    int (*)(struct drm_bridge *, struct drm_connector *) get_modes;
    struct edid * (*)(struct drm_bridge *, struct drm_connector *) get_edid;
    void (*)(struct drm_bridge *, enum drm_connector_status) hpd_notify;
    void (*)(struct drm_bridge *) hpd_enable;
    void (*)(struct drm_bridge *) hpd_disable;
    void (*)(struct drm_bridge *, struct dentry *) debugfs_init;
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
struct drm_bridge_funcs {
    int (*)(struct drm_bridge *, enum drm_bridge_attach_flags) attach;
    void (*)(struct drm_bridge *) detach;
    enum drm_mode_status (*)(struct drm_bridge *, const struct drm_display_info *, const struct drm_display_mode *) mode_valid;
    bool (*)(struct drm_bridge *, const struct drm_display_mode *, struct drm_display_mode *) mode_fixup;
    void (*)(struct drm_bridge *) disable;
    void (*)(struct drm_bridge *) post_disable;
    void (*)(struct drm_bridge *, const struct drm_display_mode *, const struct drm_display_mode *) mode_set;
    void (*)(struct drm_bridge *) pre_enable;
    void (*)(struct drm_bridge *) enable;
    void (*)(struct drm_bridge *, struct drm_bridge_state *) atomic_pre_enable;
    void (*)(struct drm_bridge *, struct drm_bridge_state *) atomic_enable;
    void (*)(struct drm_bridge *, struct drm_bridge_state *) atomic_disable;
    void (*)(struct drm_bridge *, struct drm_bridge_state *) atomic_post_disable;
    struct drm_bridge_state * (*)(struct drm_bridge *) atomic_duplicate_state;
    void (*)(struct drm_bridge *, struct drm_bridge_state *) atomic_destroy_state;
    u32 * (*)(struct drm_bridge *, struct drm_bridge_state *, struct drm_crtc_state *, struct drm_connector_state *, unsigned int *) atomic_get_output_bus_fmts;
    u32 * (*)(struct drm_bridge *, struct drm_bridge_state *, struct drm_crtc_state *, struct drm_connector_state *, u32, unsigned int *) atomic_get_input_bus_fmts;
    int (*)(struct drm_bridge *, struct drm_bridge_state *, struct drm_crtc_state *, struct drm_connector_state *) atomic_check;
    struct drm_bridge_state * (*)(struct drm_bridge *) atomic_reset;
    enum drm_connector_status (*)(struct drm_bridge *) detect;
    int (*)(struct drm_bridge *, struct drm_connector *) get_modes;
    struct edid * (*)(struct drm_bridge *, struct drm_connector *) get_edid;
    void (*)(struct drm_bridge *, enum drm_connector_status) hpd_notify;
    void (*)(struct drm_bridge *) hpd_enable;
    void (*)(struct drm_bridge *) hpd_disable;
    void (*)(struct drm_bridge *, struct dentry *) debugfs_init;
}
```
</details>
</li>
</ul>
