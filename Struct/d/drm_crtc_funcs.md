# Struct: <code>drm_crtc_funcs</code>

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
struct drm_crtc_funcs {
    void (*)(struct drm_crtc *) reset;
    int (*)(struct drm_crtc *, struct drm_file *, uint32_t, uint32_t, uint32_t) cursor_set;
    int (*)(struct drm_crtc *, struct drm_file *, uint32_t, uint32_t, uint32_t, int32_t, int32_t) cursor_set2;
    int (*)(struct drm_crtc *, int, int) cursor_move;
    int (*)(struct drm_crtc *, u16 *, u16 *, u16 *, uint32_t, struct drm_modeset_acquire_ctx *) gamma_set;
    void (*)(struct drm_crtc *) destroy;
    int (*)(struct drm_mode_set *, struct drm_modeset_acquire_ctx *) set_config;
    int (*)(struct drm_crtc *, struct drm_framebuffer *, struct drm_pending_vblank_event *, uint32_t, struct drm_modeset_acquire_ctx *) page_flip;
    int (*)(struct drm_crtc *, struct drm_framebuffer *, struct drm_pending_vblank_event *, uint32_t, uint32_t, struct drm_modeset_acquire_ctx *) page_flip_target;
    int (*)(struct drm_crtc *, struct drm_property *, uint64_t) set_property;
    struct drm_crtc_state * (*)(struct drm_crtc *) atomic_duplicate_state;
    void (*)(struct drm_crtc *, struct drm_crtc_state *) atomic_destroy_state;
    int (*)(struct drm_crtc *, struct drm_crtc_state *, struct drm_property *, uint64_t) atomic_set_property;
    int (*)(struct drm_crtc *, const struct drm_crtc_state *, struct drm_property *, uint64_t *) atomic_get_property;
    int (*)(struct drm_crtc *) late_register;
    void (*)(struct drm_crtc *) early_unregister;
    int (*)(struct drm_crtc *, const char *) set_crc_source;
    int (*)(struct drm_crtc *, const char *, size_t *) verify_crc_source;
    const const char * * (*)(struct drm_crtc *, size_t *) get_crc_sources;
    void (*)(struct drm_printer *, const struct drm_crtc_state *) atomic_print_state;
    u32 (*)(struct drm_crtc *) get_vblank_counter;
    int (*)(struct drm_crtc *) enable_vblank;
    void (*)(struct drm_crtc *) disable_vblank;
    bool (*)(struct drm_crtc *, int *, ktime_t *, bool) get_vblank_timestamp;
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
struct drm_crtc_funcs {
    void (*)(struct drm_crtc *) reset;
    int (*)(struct drm_crtc *, struct drm_file *, uint32_t, uint32_t, uint32_t) cursor_set;
    int (*)(struct drm_crtc *, struct drm_file *, uint32_t, uint32_t, uint32_t, int32_t, int32_t) cursor_set2;
    int (*)(struct drm_crtc *, int, int) cursor_move;
    int (*)(struct drm_crtc *, u16 *, u16 *, u16 *, uint32_t, struct drm_modeset_acquire_ctx *) gamma_set;
    void (*)(struct drm_crtc *) destroy;
    int (*)(struct drm_mode_set *, struct drm_modeset_acquire_ctx *) set_config;
    int (*)(struct drm_crtc *, struct drm_framebuffer *, struct drm_pending_vblank_event *, uint32_t, struct drm_modeset_acquire_ctx *) page_flip;
    int (*)(struct drm_crtc *, struct drm_framebuffer *, struct drm_pending_vblank_event *, uint32_t, uint32_t, struct drm_modeset_acquire_ctx *) page_flip_target;
    int (*)(struct drm_crtc *, struct drm_property *, uint64_t) set_property;
    struct drm_crtc_state * (*)(struct drm_crtc *) atomic_duplicate_state;
    void (*)(struct drm_crtc *, struct drm_crtc_state *) atomic_destroy_state;
    int (*)(struct drm_crtc *, struct drm_crtc_state *, struct drm_property *, uint64_t) atomic_set_property;
    int (*)(struct drm_crtc *, const struct drm_crtc_state *, struct drm_property *, uint64_t *) atomic_get_property;
    int (*)(struct drm_crtc *) late_register;
    void (*)(struct drm_crtc *) early_unregister;
    int (*)(struct drm_crtc *, const char *) set_crc_source;
    int (*)(struct drm_crtc *, const char *, size_t *) verify_crc_source;
    const const char * * (*)(struct drm_crtc *, size_t *) get_crc_sources;
    void (*)(struct drm_printer *, const struct drm_crtc_state *) atomic_print_state;
    u32 (*)(struct drm_crtc *) get_vblank_counter;
    int (*)(struct drm_crtc *) enable_vblank;
    void (*)(struct drm_crtc *) disable_vblank;
    bool (*)(struct drm_crtc *, int *, ktime_t *, bool) get_vblank_timestamp;
}
```
</details>
</li>
</ul>
