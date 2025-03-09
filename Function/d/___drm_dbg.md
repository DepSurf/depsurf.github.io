# Function: <code>___drm_dbg</code>

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
void ___drm_dbg(struct _ddebug * desc, enum drm_debug_category category, const char * format, void (anon))
```

```json
{
  "name": "___drm_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "___drm_dbg",
      "external": true,
      "loc": "drivers/gpu/drm/drm_print.c:307",
      "file": "drivers/gpu/drm/drm_print.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_probe",
        "drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_probe",
        "drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_probe",
        "drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_probe",
        "drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_probe",
        "drivers/gpu/drm/drm_client_modeset.c:drm_client_target_preferred",
        "drivers/gpu/drm/drm_client_modeset.c:drm_client_target_preferred",
        "drivers/gpu/drm/drm_client_modeset.c:drm_client_target_preferred",
        "drivers/gpu/drm/drm_client_modeset.c:drm_client_target_preferred",
        "drivers/gpu/drm/drm_client_modeset.c:drm_client_target_preferred",
        "drivers/gpu/drm/drm_client_modeset.c:drm_client_target_preferred",
        "drivers/gpu/drm/drm_color_mgmt.c:drm_color_lut_check",
        "drivers/gpu/drm/drm_color_mgmt.c:drm_color_lut_check",
        "drivers/gpu/drm/drm_connector.c:__drm_connector_init",
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
        "drivers/gpu/drm/drm_displayid.c:__displayid_iter_next",
        "drivers/gpu/drm/drm_drv.c:drm_core_init",
        "drivers/gpu/drm/drm_drv.c:drm_stub_open",
        "drivers/gpu/drm/drm_drv.c:drm_minor_register",
        "drivers/gpu/drm/drm_drv.c:drm_minor_register",
        "drivers/gpu/drm/drm_edid.c:drm_detect_monitor_audio",
        "drivers/gpu/drm/drm_edid.c:drm_detect_monitor_audio",
        "drivers/gpu/drm/drm_edid.c:drm_edid_to_speaker_allocation",
        "drivers/gpu/drm/drm_edid.c:_drm_edid_to_sad",
        "drivers/gpu/drm/drm_edid.c:drm_do_probe_ddc_edid",
        "drivers/gpu/drm/drm_edid.c:drm_edid_block_valid",
        "drivers/gpu/drm/drm_gem.c:drm_gem_dma_resv_wait",
        "drivers/gpu/drm/drm_gem.c:drm_gem_objects_lookup",
        "drivers/gpu/drm/drm_lease.c:drm_mode_get_lease_ioctl",
        "drivers/gpu/drm/drm_lease.c:drm_mode_get_lease_ioctl",
        "drivers/gpu/drm/drm_lease.c:fill_object_idr",
        "drivers/gpu/drm/drm_modes.c:drm_mode_prune_invalid",
        "drivers/gpu/drm/drm_modes.c:drm_mode_debug_printmodeline",
        "drivers/gpu/drm/drm_plane.c:drm_mode_page_flip_ioctl",
        "drivers/gpu/drm/drm_plane.c:drm_mode_page_flip_ioctl",
        "drivers/gpu/drm/drm_plane.c:drm_mode_page_flip_ioctl",
        "drivers/gpu/drm/drm_plane.c:drm_mode_cursor_common",
        "drivers/gpu/drm/drm_plane.c:drm_mode_cursor_universal",
        "drivers/gpu/drm/drm_plane.c:drm_mode_setplane",
        "drivers/gpu/drm/drm_plane.c:drm_mode_setplane",
        "drivers/gpu/drm/drm_plane.c:drm_mode_setplane",
        "drivers/gpu/drm/drm_plane.c:__setplane_check",
        "drivers/gpu/drm/drm_plane.c:__setplane_check",
        "drivers/gpu/drm/drm_plane.c:__setplane_check",
        "drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init",
        "drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_add_point",
        "drivers/gpu/drm/drm_sysfs.c:drm_sysfs_hotplug_event",
        "drivers/gpu/drm/drm_sysfs.c:drm_sysfs_lease_event",
        "drivers/gpu/drm/drm_sysfs.c:drm_sysfs_connector_remove",
        "drivers/gpu/drm/drm_sysfs.c:drm_sysfs_connector_add",
        "drivers/gpu/drm/drm_sysfs.c:status_store",
        "drivers/gpu/drm/drm_sysfs.c:status_store",
        "drivers/gpu/drm/drm_debugfs_crc.c:crc_control_write",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_mode",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_mode",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_mode",
        "drivers/gpu/drm/drm_probe_helper.c:output_poll_execute",
        "drivers/gpu/drm/drm_probe_helper.c:output_poll_execute",
        "drivers/gpu/drm/drm_probe_helper.c:drm_helper_probe_single_connector_modes",
        "drivers/gpu/drm/drm_probe_helper.c:drm_helper_probe_single_connector_modes",
        "drivers/gpu/drm/drm_probe_helper.c:drm_helper_probe_single_connector_modes",
        "drivers/gpu/drm/drm_probe_helper.c:drm_helper_probe_single_connector_modes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597708873,
      "name": "___drm_dbg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071592139184,
      "name": "___drm_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
void ___drm_dbg(struct _ddebug * desc, enum drm_debug_category category, const char * format, void (anon))
```
</details>
</li>
</ul>
