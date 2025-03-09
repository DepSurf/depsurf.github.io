# Function: <code>drm_mode_object_find</code>

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
struct drm_mode_object * drm_mode_object_find(struct drm_device * dev, struct drm_file * file_priv, uint32_t id, uint32_t type)
```

```json
{
  "name": "drm_mode_object_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592101563,
      "name": "drm_mode_object_find",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mode_object.c:175",
      "file": "drivers/gpu/drm/drm_mode_object.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mode_object.c:drm_mode_obj_set_property_ioctl",
        "drivers/gpu/drm/drm_mode_object.c:drm_mode_obj_get_properties_ioctl"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_mode_atomic_ioctl",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_connector_set_property",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_plane_set_property",
        "drivers/gpu/drm/drm_color_mgmt.c:drm_mode_gamma_get_ioctl",
        "drivers/gpu/drm/drm_color_mgmt.c:drm_mode_gamma_set_ioctl",
        "drivers/gpu/drm/drm_connector.c:drm_mode_getconnector",
        "drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc",
        "drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc",
        "drivers/gpu/drm/drm_crtc.c:drm_mode_getcrtc",
        "drivers/gpu/drm/drm_encoder.c:drm_mode_getencoder",
        "drivers/gpu/drm/drm_lease.c:fill_object_idr",
        "drivers/gpu/drm/drm_plane.c:drm_mode_page_flip_ioctl",
        "drivers/gpu/drm/drm_plane.c:drm_mode_cursor_common",
        "drivers/gpu/drm/drm_plane.c:drm_mode_setplane",
        "drivers/gpu/drm/drm_plane.c:drm_mode_setplane",
        "drivers/gpu/drm/drm_plane.c:drm_mode_getplane",
        "drivers/gpu/drm/drm_property.c:drm_mode_getproperty_ioctl",
        "drivers/gpu/drm/drm_vblank.c:drm_crtc_queue_sequence_ioctl",
        "drivers/gpu/drm/drm_vblank.c:drm_crtc_get_sequence_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592100384,
      "name": "drm_mode_object_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
struct drm_mode_object * drm_mode_object_find(struct drm_device * dev, struct drm_file * file_priv, uint32_t id, uint32_t type)
```
</details>
</li>
</ul>
