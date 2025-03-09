# Function: <code>drm_property_create_range</code>

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
struct drm_property * drm_property_create_range(struct drm_device * dev, u32 flags, const char * name, uint64_t min, uint64_t max)
```

```json
{
  "name": "drm_property_create_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592141093,
      "name": "drm_property_create_range",
      "external": true,
      "loc": "drivers/gpu/drm/drm_property.c:277",
      "file": "drivers/gpu/drm/drm_property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_property.c:drm_property_create_bool"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_blend.c:drm_plane_create_zpos_immutable_property",
        "drivers/gpu/drm/drm_blend.c:drm_plane_create_zpos_property",
        "drivers/gpu/drm/drm_blend.c:drm_plane_create_alpha_property",
        "drivers/gpu/drm/drm_connector.c:drm_connector_attach_max_bpc_property",
        "drivers/gpu/drm/drm_connector.c:drm_mode_create_suggested_offset_properties",
        "drivers/gpu/drm/drm_connector.c:drm_mode_create_suggested_offset_properties",
        "drivers/gpu/drm/drm_connector.c:drm_mode_create_tv_properties_legacy",
        "drivers/gpu/drm/drm_connector.c:drm_mode_create_tv_properties_legacy",
        "drivers/gpu/drm/drm_connector.c:drm_mode_create_tv_properties_legacy",
        "drivers/gpu/drm/drm_connector.c:drm_mode_create_tv_properties_legacy",
        "drivers/gpu/drm/drm_connector.c:drm_mode_create_tv_properties_legacy",
        "drivers/gpu/drm/drm_connector.c:drm_mode_create_tv_properties_legacy",
        "drivers/gpu/drm/drm_connector.c:drm_mode_create_tv_margin_properties",
        "drivers/gpu/drm/drm_connector.c:drm_mode_create_tv_margin_properties",
        "drivers/gpu/drm/drm_connector.c:drm_mode_create_tv_margin_properties",
        "drivers/gpu/drm/drm_connector.c:drm_mode_create_tv_margin_properties",
        "drivers/gpu/drm/drm_writeback.c:drm_writeback_connector_init_with_encoder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592142064,
      "name": "drm_property_create_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
struct drm_property * drm_property_create_range(struct drm_device * dev, u32 flags, const char * name, uint64_t min, uint64_t max)
```
</details>
</li>
</ul>
