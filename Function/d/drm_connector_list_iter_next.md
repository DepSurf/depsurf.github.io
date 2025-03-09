# Function: <code>drm_connector_list_iter_next</code>

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
struct drm_connector * drm_connector_list_iter_next(struct drm_connector_list_iter * iter)
```

```json
{
  "name": "drm_connector_list_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591982736,
      "name": "drm_connector_list_iter_next",
      "external": true,
      "loc": "drivers/gpu/drm/drm_connector.c:828",
      "file": "drivers/gpu/drm/drm_connector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/drm/drm_atomic.c:__drm_state_dump",
        "drivers/gpu/drm/drm_atomic.c:__drm_state_dump",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_add_affected_connectors",
        "drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_probe",
        "drivers/gpu/drm/drm_connector.c:drm_connector_register_all",
        "drivers/gpu/drm/drm_connector.c:drm_connector_register_all",
        "drivers/gpu/drm/drm_encoder.c:drm_mode_getencoder",
        "drivers/gpu/drm/drm_encoder.c:drm_mode_getencoder",
        "drivers/gpu/drm/drm_mode_config.c:drm_mode_config_cleanup",
        "drivers/gpu/drm/drm_mode_config.c:drm_mode_config_cleanup",
        "drivers/gpu/drm/drm_mode_config.c:drm_mode_config_reset",
        "drivers/gpu/drm/drm_mode_config.c:drm_mode_getresources",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_duplicate_state",
        "drivers/gpu/drm/drm_atomic_helper.c:handle_conflicting_encoders",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_helper_resume_force_mode",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_helper_resume_force_mode",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_helper_connector_dpms",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_helper_connector_dpms",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_helper_choose_crtc_dpms",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_helper_choose_crtc_dpms",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_helper_encoder_in_use",
        "drivers/gpu/drm/drm_plane_helper.c:get_connectors_for_crtc",
        "drivers/gpu/drm/drm_plane_helper.c:get_connectors_for_crtc",
        "drivers/gpu/drm/drm_probe_helper.c:drm_helper_hpd_irq_event",
        "drivers/gpu/drm/drm_probe_helper.c:output_poll_execute",
        "drivers/gpu/drm/drm_probe_helper.c:drm_kms_helper_poll_enable",
        "drivers/gpu/drm/drm_probe_helper.c:drm_kms_helper_disable_hpd",
        "drivers/gpu/drm/drm_fb_helper.c:drm_setup_crtcs_fb",
        "drivers/gpu/drm/drm_fb_helper.c:__drm_fb_helper_find_sizes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591982736,
      "name": "drm_connector_list_iter_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
struct drm_connector * drm_connector_list_iter_next(struct drm_connector_list_iter * iter)
```
</details>
</li>
</ul>
