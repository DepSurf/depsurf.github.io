# Struct: <code>drm_crtc_helper_funcs</code>

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
struct drm_crtc_helper_funcs {
    void (*)(struct drm_crtc *, int) dpms;
    void (*)(struct drm_crtc *) prepare;
    void (*)(struct drm_crtc *) commit;
    enum drm_mode_status (*)(struct drm_crtc *, const struct drm_display_mode *) mode_valid;
    bool (*)(struct drm_crtc *, const struct drm_display_mode *, struct drm_display_mode *) mode_fixup;
    int (*)(struct drm_crtc *, struct drm_display_mode *, struct drm_display_mode *, int, int, struct drm_framebuffer *) mode_set;
    void (*)(struct drm_crtc *) mode_set_nofb;
    int (*)(struct drm_crtc *, int, int, struct drm_framebuffer *) mode_set_base;
    int (*)(struct drm_crtc *, struct drm_framebuffer *, int, int, enum mode_set_atomic) mode_set_base_atomic;
    void (*)(struct drm_crtc *) disable;
    int (*)(struct drm_crtc *, struct drm_atomic_state *) atomic_check;
    void (*)(struct drm_crtc *, struct drm_atomic_state *) atomic_begin;
    void (*)(struct drm_crtc *, struct drm_atomic_state *) atomic_flush;
    void (*)(struct drm_crtc *, struct drm_atomic_state *) atomic_enable;
    void (*)(struct drm_crtc *, struct drm_atomic_state *) atomic_disable;
    bool (*)(struct drm_crtc *, bool, int *, int *, ktime_t *, ktime_t *, const struct drm_display_mode *) get_scanout_position;
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
struct drm_crtc_helper_funcs {
    void (*)(struct drm_crtc *, int) dpms;
    void (*)(struct drm_crtc *) prepare;
    void (*)(struct drm_crtc *) commit;
    enum drm_mode_status (*)(struct drm_crtc *, const struct drm_display_mode *) mode_valid;
    bool (*)(struct drm_crtc *, const struct drm_display_mode *, struct drm_display_mode *) mode_fixup;
    int (*)(struct drm_crtc *, struct drm_display_mode *, struct drm_display_mode *, int, int, struct drm_framebuffer *) mode_set;
    void (*)(struct drm_crtc *) mode_set_nofb;
    int (*)(struct drm_crtc *, int, int, struct drm_framebuffer *) mode_set_base;
    int (*)(struct drm_crtc *, struct drm_framebuffer *, int, int, enum mode_set_atomic) mode_set_base_atomic;
    void (*)(struct drm_crtc *) disable;
    int (*)(struct drm_crtc *, struct drm_atomic_state *) atomic_check;
    void (*)(struct drm_crtc *, struct drm_atomic_state *) atomic_begin;
    void (*)(struct drm_crtc *, struct drm_atomic_state *) atomic_flush;
    void (*)(struct drm_crtc *, struct drm_atomic_state *) atomic_enable;
    void (*)(struct drm_crtc *, struct drm_atomic_state *) atomic_disable;
    bool (*)(struct drm_crtc *, bool, int *, int *, ktime_t *, ktime_t *, const struct drm_display_mode *) get_scanout_position;
}
```
</details>
</li>
</ul>
