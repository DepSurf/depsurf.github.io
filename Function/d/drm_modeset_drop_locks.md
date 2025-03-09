# Function: <code>drm_modeset_drop_locks</code>

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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void drm_modeset_drop_locks(struct drm_modeset_acquire_ctx * ctx)
```

```json
{
  "name": "drm_modeset_drop_locks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592119518,
      "name": "drm_modeset_drop_locks",
      "external": true,
      "loc": "drivers/gpu/drm/drm_modeset_lock.c:274",
      "file": "drivers/gpu/drm/drm_modeset_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_modeset_lock.c:drm_modeset_backoff",
        "drivers/gpu/drm/drm_modeset_lock.c:drm_modeset_unlock_all"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_mode_atomic_ioctl",
        "drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_dpms",
        "drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_commit_atomic",
        "drivers/gpu/drm/drm_color_mgmt.c:drm_mode_gamma_set_ioctl",
        "drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc",
        "drivers/gpu/drm/drm_framebuffer.c:atomic_remove_fb",
        "drivers/gpu/drm/drm_framebuffer.c:atomic_remove_fb",
        "drivers/gpu/drm/drm_mode_object.c:drm_mode_obj_set_property_ioctl",
        "drivers/gpu/drm/drm_mode_object.c:drm_mode_obj_set_property_ioctl",
        "drivers/gpu/drm/drm_mode_object.c:drm_mode_obj_get_properties_ioctl",
        "drivers/gpu/drm/drm_plane.c:drm_mode_page_flip_ioctl",
        "drivers/gpu/drm/drm_plane.c:drm_mode_page_flip_ioctl",
        "drivers/gpu/drm/drm_plane.c:drm_mode_page_flip_ioctl",
        "drivers/gpu/drm/drm_plane.c:drm_mode_cursor_common",
        "drivers/gpu/drm/drm_plane.c:drm_mode_setplane",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_resume",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_suspend",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_suspend",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_suspend",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_shutdown",
        "drivers/gpu/drm/drm_damage_helper.c:drm_atomic_helper_dirtyfb",
        "drivers/gpu/drm/drm_probe_helper.c:drm_helper_probe_single_connector_modes",
        "drivers/gpu/drm/drm_probe_helper.c:drm_helper_probe_detect_ctx",
        "drivers/gpu/drm/drm_self_refresh_helper.c:drm_self_refresh_helper_entry_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592118672,
      "name": "drm_modeset_drop_locks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
    }
  ]
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
void drm_modeset_drop_locks(struct drm_modeset_acquire_ctx * ctx)
```
</details>
</li>
</ul>
