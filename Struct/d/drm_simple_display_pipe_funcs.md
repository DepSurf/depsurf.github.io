# Struct: <code>drm_simple_display_pipe_funcs</code>

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
struct drm_simple_display_pipe_funcs {
    enum drm_mode_status (*)(struct drm_simple_display_pipe *, const struct drm_display_mode *) mode_valid;
    void (*)(struct drm_simple_display_pipe *, struct drm_crtc_state *, struct drm_plane_state *) enable;
    void (*)(struct drm_simple_display_pipe *) disable;
    int (*)(struct drm_simple_display_pipe *, struct drm_plane_state *, struct drm_crtc_state *) check;
    void (*)(struct drm_simple_display_pipe *, struct drm_plane_state *) update;
    int (*)(struct drm_simple_display_pipe *, struct drm_plane_state *) prepare_fb;
    void (*)(struct drm_simple_display_pipe *, struct drm_plane_state *) cleanup_fb;
    int (*)(struct drm_simple_display_pipe *, struct drm_plane_state *) begin_fb_access;
    void (*)(struct drm_simple_display_pipe *, struct drm_plane_state *) end_fb_access;
    int (*)(struct drm_simple_display_pipe *) enable_vblank;
    void (*)(struct drm_simple_display_pipe *) disable_vblank;
    void (*)(struct drm_simple_display_pipe *) reset_crtc;
    struct drm_crtc_state * (*)(struct drm_simple_display_pipe *) duplicate_crtc_state;
    void (*)(struct drm_simple_display_pipe *, struct drm_crtc_state *) destroy_crtc_state;
    void (*)(struct drm_simple_display_pipe *) reset_plane;
    struct drm_plane_state * (*)(struct drm_simple_display_pipe *) duplicate_plane_state;
    void (*)(struct drm_simple_display_pipe *, struct drm_plane_state *) destroy_plane_state;
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
struct drm_simple_display_pipe_funcs {
    enum drm_mode_status (*)(struct drm_simple_display_pipe *, const struct drm_display_mode *) mode_valid;
    void (*)(struct drm_simple_display_pipe *, struct drm_crtc_state *, struct drm_plane_state *) enable;
    void (*)(struct drm_simple_display_pipe *) disable;
    int (*)(struct drm_simple_display_pipe *, struct drm_plane_state *, struct drm_crtc_state *) check;
    void (*)(struct drm_simple_display_pipe *, struct drm_plane_state *) update;
    int (*)(struct drm_simple_display_pipe *, struct drm_plane_state *) prepare_fb;
    void (*)(struct drm_simple_display_pipe *, struct drm_plane_state *) cleanup_fb;
    int (*)(struct drm_simple_display_pipe *, struct drm_plane_state *) begin_fb_access;
    void (*)(struct drm_simple_display_pipe *, struct drm_plane_state *) end_fb_access;
    int (*)(struct drm_simple_display_pipe *) enable_vblank;
    void (*)(struct drm_simple_display_pipe *) disable_vblank;
    void (*)(struct drm_simple_display_pipe *) reset_crtc;
    struct drm_crtc_state * (*)(struct drm_simple_display_pipe *) duplicate_crtc_state;
    void (*)(struct drm_simple_display_pipe *, struct drm_crtc_state *) destroy_crtc_state;
    void (*)(struct drm_simple_display_pipe *) reset_plane;
    struct drm_plane_state * (*)(struct drm_simple_display_pipe *) duplicate_plane_state;
    void (*)(struct drm_simple_display_pipe *, struct drm_plane_state *) destroy_plane_state;
}
```
</details>
</li>
</ul>
