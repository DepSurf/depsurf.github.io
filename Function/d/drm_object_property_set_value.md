# Function: <code>drm_object_property_set_value</code>

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
int drm_object_property_set_value(struct drm_mode_object * obj, struct drm_property * property, uint64_t val)
```

```json
{
  "name": "drm_object_property_set_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592098624,
      "name": "drm_object_property_set_value",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mode_object.c:283",
      "file": "drivers/gpu/drm/drm_mode_object.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_dpms",
        "drivers/gpu/drm/drm_connector.c:drm_connector_set_obj_prop",
        "drivers/gpu/drm/drm_connector.c:drm_connector_update_privacy_screen",
        "drivers/gpu/drm/drm_connector.c:drm_connector_attach_privacy_screen_provider",
        "drivers/gpu/drm/drm_connector.c:drm_connector_privacy_screen_notifier",
        "drivers/gpu/drm/drm_connector.c:drm_connector_set_vrr_capable_property",
        "drivers/gpu/drm/drm_crtc.c:drm_mode_crtc_set_obj_prop",
        "drivers/gpu/drm/drm_edid.c:_drm_edid_connector_property_update",
        "drivers/gpu/drm/drm_plane.c:drm_mode_plane_set_obj_prop",
        "drivers/gpu/drm/drm_property.c:drm_property_replace_global_blob",
        "drivers/gpu/drm/drm_property.c:drm_property_replace_global_blob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592098624,
      "name": "drm_object_property_set_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
int drm_object_property_set_value(struct drm_mode_object * obj, struct drm_property * property, uint64_t val)
```
</details>
</li>
</ul>
