# Function: <code>drm_mode_object_put</code>

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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void drm_mode_object_put(struct drm_mode_object * obj)
```

```json
{
  "name": "drm_mode_object_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592101947,
      "name": "drm_mode_object_put",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mode_object.c:194",
      "file": "drivers/gpu/drm/drm_mode_object.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mode_object.c:drm_mode_obj_set_property_ioctl",
        "drivers/gpu/drm/drm_mode_object.c:drm_mode_obj_get_properties_ioctl"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_state_default_clear",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_mode_atomic_ioctl",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_mode_atomic_ioctl",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_mode_atomic_ioctl",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_mode_atomic_ioctl",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_mode_atomic_ioctl",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_mode_atomic_ioctl",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_connector_set_property",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_plane_set_property",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_crtc_for_connector",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_fb_for_plane",
        "drivers/gpu/drm/drm_client.c:drm_client_buffer_addfb",
        "drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_probe",
        "drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_release",
        "drivers/gpu/drm/drm_connector.c:drm_connector_oob_hotplug_event",
        "drivers/gpu/drm/drm_connector.c:drm_mode_getconnector",
        "drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc",
        "drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc",
        "drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc",
        "drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc",
        "drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc",
        "drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc",
        "drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc",
        "drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc",
        "drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc",
        "drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc",
        "drivers/gpu/drm/drm_crtc.c:__drm_mode_set_config_internal",
        "drivers/gpu/drm/drm_framebuffer.c:drm_framebuffer_remove",
        "drivers/gpu/drm/drm_framebuffer.c:drm_fb_release",
        "drivers/gpu/drm/drm_framebuffer.c:drm_mode_dirtyfb_ioctl",
        "drivers/gpu/drm/drm_framebuffer.c:drm_mode_dirtyfb_ioctl",
        "drivers/gpu/drm/drm_framebuffer.c:drm_mode_getfb2_ioctl",
        "drivers/gpu/drm/drm_framebuffer.c:drm_mode_getfb",
        "drivers/gpu/drm/drm_framebuffer.c:drm_mode_closefb_ioctl",
        "drivers/gpu/drm/drm_framebuffer.c:drm_mode_rmfb",
        "drivers/gpu/drm/drm_framebuffer.c:drm_mode_closefb",
        "drivers/gpu/drm/drm_lease.c:fill_object_idr",
        "drivers/gpu/drm/drm_mode_config.c:drm_mode_config_cleanup",
        "drivers/gpu/drm/drm_mode_object.c:drm_mode_obj_set_property_ioctl",
        "drivers/gpu/drm/drm_mode_object.c:drm_mode_obj_get_properties_ioctl",
        "drivers/gpu/drm/drm_mode_object.c:drm_mode_obj_get_properties_ioctl",
        "drivers/gpu/drm/drm_plane.c:drm_mode_page_flip_ioctl",
        "drivers/gpu/drm/drm_plane.c:drm_mode_page_flip_ioctl",
        "drivers/gpu/drm/drm_plane.c:drm_mode_page_flip_ioctl",
        "drivers/gpu/drm/drm_plane.c:drm_mode_page_flip_ioctl",
        "drivers/gpu/drm/drm_plane.c:drm_mode_page_flip_ioctl",
        "drivers/gpu/drm/drm_plane.c:drm_mode_page_flip_ioctl",
        "drivers/gpu/drm/drm_plane.c:drm_mode_page_flip_ioctl",
        "drivers/gpu/drm/drm_plane.c:drm_mode_page_flip_ioctl",
        "drivers/gpu/drm/drm_plane.c:drm_mode_page_flip_ioctl",
        "drivers/gpu/drm/drm_plane.c:drm_mode_page_flip_ioctl",
        "drivers/gpu/drm/drm_plane.c:drm_mode_cursor_universal",
        "drivers/gpu/drm/drm_plane.c:drm_mode_setplane",
        "drivers/gpu/drm/drm_plane.c:drm_mode_setplane",
        "drivers/gpu/drm/drm_plane.c:__setplane_internal",
        "drivers/gpu/drm/drm_plane.c:drm_plane_force_disable",
        "drivers/gpu/drm/drm_property.c:drm_property_change_valid_put",
        "drivers/gpu/drm/drm_property.c:drm_mode_destroyblob_ioctl",
        "drivers/gpu/drm/drm_property.c:drm_mode_destroyblob_ioctl",
        "drivers/gpu/drm/drm_property.c:drm_mode_destroyblob_ioctl",
        "drivers/gpu/drm/drm_property.c:drm_mode_createblob_ioctl",
        "drivers/gpu/drm/drm_property.c:drm_mode_getblob_ioctl",
        "drivers/gpu/drm/drm_property.c:drm_property_replace_blob_from_id",
        "drivers/gpu/drm/drm_property.c:drm_property_replace_blob_from_id",
        "drivers/gpu/drm/drm_property.c:drm_property_replace_blob_from_id",
        "drivers/gpu/drm/drm_property.c:drm_property_replace_blob_from_id",
        "drivers/gpu/drm/drm_property.c:drm_property_replace_global_blob",
        "drivers/gpu/drm/drm_property.c:drm_property_replace_global_blob",
        "drivers/gpu/drm/drm_property.c:drm_property_destroy_user_blobs",
        "drivers/gpu/drm/drm_writeback.c:drm_writeback_cleanup_job",
        "drivers/gpu/drm/drm_writeback.c:drm_writeback_set_fb",
        "drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_connector_destroy_state",
        "drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_plane_destroy_state",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config",
        "drivers/gpu/drm/drm_probe_helper.c:drm_helper_hpd_irq_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592098112,
      "name": "drm_mode_object_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071592098288,
      "name": "drm_mode_object_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void drm_mode_object_put(struct drm_mode_object * obj)
```
</details>
</li>
</ul>
