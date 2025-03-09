# Struct: <code>drm_display_mode</code>

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
struct drm_display_mode {
    int clock;
    u16 hdisplay;
    u16 hsync_start;
    u16 hsync_end;
    u16 htotal;
    u16 hskew;
    u16 vdisplay;
    u16 vsync_start;
    u16 vsync_end;
    u16 vtotal;
    u16 vscan;
    u32 flags;
    int crtc_clock;
    u16 crtc_hdisplay;
    u16 crtc_hblank_start;
    u16 crtc_hblank_end;
    u16 crtc_hsync_start;
    u16 crtc_hsync_end;
    u16 crtc_htotal;
    u16 crtc_hskew;
    u16 crtc_vdisplay;
    u16 crtc_vblank_start;
    u16 crtc_vblank_end;
    u16 crtc_vsync_start;
    u16 crtc_vsync_end;
    u16 crtc_vtotal;
    u16 width_mm;
    u16 height_mm;
    u8 type;
    bool expose_to_userspace;
    struct list_head head;
    char[32] name;
    enum drm_mode_status status;
    enum hdmi_picture_aspect picture_aspect_ratio;
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
struct drm_display_mode {
    int clock;
    u16 hdisplay;
    u16 hsync_start;
    u16 hsync_end;
    u16 htotal;
    u16 hskew;
    u16 vdisplay;
    u16 vsync_start;
    u16 vsync_end;
    u16 vtotal;
    u16 vscan;
    u32 flags;
    int crtc_clock;
    u16 crtc_hdisplay;
    u16 crtc_hblank_start;
    u16 crtc_hblank_end;
    u16 crtc_hsync_start;
    u16 crtc_hsync_end;
    u16 crtc_htotal;
    u16 crtc_hskew;
    u16 crtc_vdisplay;
    u16 crtc_vblank_start;
    u16 crtc_vblank_end;
    u16 crtc_vsync_start;
    u16 crtc_vsync_end;
    u16 crtc_vtotal;
    u16 width_mm;
    u16 height_mm;
    u8 type;
    bool expose_to_userspace;
    struct list_head head;
    char[32] name;
    enum drm_mode_status status;
    enum hdmi_picture_aspect picture_aspect_ratio;
}
```
</details>
</li>
</ul>
