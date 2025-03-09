# Function: <code>drm_edid_free</code>

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
void drm_edid_free(const struct drm_edid * drm_edid)
```

```json
{
  "name": "drm_edid_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592041522,
      "name": "drm_edid_free",
      "external": true,
      "loc": "drivers/gpu/drm/drm_edid.c:2594",
      "file": "drivers/gpu/drm/drm_edid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_edid.c:drm_edid_connector_add_modes",
        "drivers/gpu/drm/drm_edid.c:drm_edid_connector_add_modes",
        "drivers/gpu/drm/drm_edid.c:_drm_do_get_edid",
        "drivers/gpu/drm/drm_edid.c:_drm_do_get_edid",
        "drivers/gpu/drm/drm_edid.c:drm_edid_override_connector_update",
        "drivers/gpu/drm/drm_edid.c:drm_edid_override_connector_update",
        "drivers/gpu/drm/drm_edid.c:drm_edid_override_reset",
        "drivers/gpu/drm/drm_edid.c:drm_edid_override_reset",
        "drivers/gpu/drm/drm_edid.c:drm_edid_override_set",
        "drivers/gpu/drm/drm_edid.c:drm_edid_override_set",
        "drivers/gpu/drm/drm_edid.c:drm_edid_override_set",
        "drivers/gpu/drm/drm_edid.c:drm_edid_override_set"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_edid_load.c:drm_edid_load_firmware",
        "drivers/gpu/drm/drm_probe_helper.c:drm_connector_helper_get_modes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592015600,
      "name": "drm_edid_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void drm_edid_free(const struct drm_edid * drm_edid)
```
</details>
</li>
</ul>
