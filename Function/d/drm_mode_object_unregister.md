# Function: <code>drm_mode_object_unregister</code>

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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void drm_mode_object_unregister(struct drm_device * dev, struct drm_mode_object * object)
```

```json
{
  "name": "drm_mode_object_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "drm_mode_object_unregister",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mode_object.c:104",
      "file": "drivers/gpu/drm/drm_mode_object.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/drm/drm_connector.c:drm_connector_cleanup",
        "drivers/gpu/drm/drm_connector.c:__drm_connector_init",
        "drivers/gpu/drm/drm_connector.c:drm_connector_free_work_fn",
        "drivers/gpu/drm/drm_connector.c:drm_connector_free",
        "drivers/gpu/drm/drm_crtc.c:drm_crtc_cleanup",
        "drivers/gpu/drm/drm_crtc.c:__drm_crtc_init_with_planes",
        "drivers/gpu/drm/drm_encoder.c:drm_encoder_cleanup",
        "drivers/gpu/drm/drm_encoder.c:__drm_encoder_init",
        "drivers/gpu/drm/drm_framebuffer.c:drm_framebuffer_free",
        "drivers/gpu/drm/drm_plane.c:drm_plane_cleanup",
        "drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init",
        "drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init",
        "drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init",
        "drivers/gpu/drm/drm_property.c:drm_property_free_blob",
        "drivers/gpu/drm/drm_property.c:drm_property_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597707958,
      "name": "drm_mode_object_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071592099840,
      "name": "drm_mode_object_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void drm_mode_object_unregister(struct drm_device * dev, struct drm_mode_object * object)
```
</details>
</li>
</ul>
