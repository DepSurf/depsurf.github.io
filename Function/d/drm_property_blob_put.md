# Function: <code>drm_property_blob_put</code>

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
void drm_property_blob_put(struct drm_property_blob * blob)
```

```json
{
  "name": "drm_property_blob_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592144610,
      "name": "drm_property_blob_put",
      "external": true,
      "loc": "drivers/gpu/drm/drm_property.c:601",
      "file": "drivers/gpu/drm/drm_property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_property.c:drm_property_change_valid_put",
        "drivers/gpu/drm/drm_property.c:drm_mode_destroyblob_ioctl",
        "drivers/gpu/drm/drm_property.c:drm_mode_destroyblob_ioctl",
        "drivers/gpu/drm/drm_property.c:drm_mode_destroyblob_ioctl",
        "drivers/gpu/drm/drm_property.c:drm_mode_createblob_ioctl",
        "drivers/gpu/drm/drm_property.c:drm_mode_getblob_ioctl",
        "drivers/gpu/drm/drm_property.c:drm_property_replace_blob_from_id",
        "drivers/gpu/drm/drm_property.c:drm_property_replace_blob_from_id",
        "drivers/gpu/drm/drm_property.c:drm_property_replace_blob_from_id",
        "drivers/gpu/drm/drm_property.c:drm_property_replace_global_blob",
        "drivers/gpu/drm/drm_property.c:drm_property_replace_global_blob",
        "drivers/gpu/drm/drm_property.c:drm_property_destroy_user_blobs"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_crtc_set_property",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_mode_prop_for_crtc",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_mode_for_crtc",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_mode_for_crtc",
        "drivers/gpu/drm/drm_color_mgmt.c:drm_crtc_legacy_gamma_set",
        "drivers/gpu/drm/drm_mode_config.c:drm_mode_config_cleanup",
        "drivers/gpu/drm/drm_writeback.c:drm_writeback_connector_init_with_encoder",
        "drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_connector_destroy_state",
        "drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_plane_destroy_state",
        "drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_plane_destroy_state",
        "drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_crtc_destroy_state",
        "drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_crtc_destroy_state",
        "drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_crtc_destroy_state",
        "drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_crtc_destroy_state",
        "drivers/gpu/drm/drm_damage_helper.c:drm_atomic_helper_dirtyfb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592139808,
      "name": "drm_property_blob_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void drm_property_blob_put(struct drm_property_blob * blob)
```
</details>
</li>
</ul>
