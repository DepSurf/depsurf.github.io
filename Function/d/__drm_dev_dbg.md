# Function: <code>__drm_dev_dbg</code>

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
void __drm_dev_dbg(struct _ddebug * desc, const struct device * dev, enum drm_debug_category category, const char * format, void (anon))
```

```json
{
  "name": "__drm_dev_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__drm_dev_dbg",
      "external": true,
      "loc": "drivers/gpu/drm/drm_print.c:282",
      "file": "drivers/gpu/drm/drm_print.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_nonblocking_commit",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_commit",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_check_only",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_check_only",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_check_only",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_check_only",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_check_only",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_add_affected_planes",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_add_affected_connectors",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_add_encoder_bridges",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_get_connector_state",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_get_private_obj_state",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_plane_check",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_plane_check",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_plane_check",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_plane_check",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_plane_check",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_plane_check",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_plane_check",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_plane_check",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_get_plane_state",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_connector_check",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_connector_check",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_connector_check",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_crtc_check",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_crtc_check",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_crtc_check",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_crtc_check",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_get_crtc_state",
        "drivers/gpu/drm/drm_atomic.c:__drm_atomic_state_free",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_state_default_clear",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_state_init",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_mode_atomic_ioctl",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_mode_atomic_ioctl",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_mode_atomic_ioctl",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_mode_atomic_ioctl",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_mode_atomic_ioctl",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_mode_atomic_ioctl",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_mode_atomic_ioctl",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_mode_atomic_ioctl",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_mode_atomic_ioctl",
        "drivers/gpu/drm/drm_atomic_uapi.c:prepare_signaling",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_property",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_property",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_property",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_get_property",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_connector_get_property",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_connector_set_property",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_connector_set_property",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_connector_set_property",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_connector_set_property",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_connector_set_property",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_connector_set_property",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_plane_get_property",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_plane_set_property",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_plane_set_property",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_plane_set_property",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_crtc_get_property",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_crtc_set_property",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_crtc_for_connector",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_crtc_for_connector",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_fb_for_plane",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_fb_for_plane",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_crtc_for_plane",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_crtc_for_plane",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_mode_prop_for_crtc",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_mode_prop_for_crtc",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_mode_prop_for_crtc",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_mode_prop_for_crtc",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_mode_for_crtc",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_mode_for_crtc",
        "drivers/gpu/drm/drm_auth.c:drm_dropmaster_ioctl",
        "drivers/gpu/drm/drm_auth.c:drm_setmaster_ioctl",
        "drivers/gpu/drm/drm_auth.c:drm_authmagic",
        "drivers/gpu/drm/drm_auth.c:drm_getmagic",
        "drivers/gpu/drm/drm_blend.c:drm_atomic_helper_crtc_normalize_zpos",
        "drivers/gpu/drm/drm_blend.c:drm_atomic_helper_crtc_normalize_zpos",
        "drivers/gpu/drm/drm_blend.c:drm_atomic_helper_crtc_normalize_zpos",
        "drivers/gpu/drm/drm_client.c:drm_client_dev_restore",
        "drivers/gpu/drm/drm_client.c:drm_client_release",
        "drivers/gpu/drm/drm_client.c:drm_client_register",
        "drivers/gpu/drm/drm_connector.c:drm_mode_getconnector",
        "drivers/gpu/drm/drm_edid.c:drm_parse_tiled_block",
        "drivers/gpu/drm/drm_edid.c:_drm_edid_connector_property_update",
        "drivers/gpu/drm/drm_edid.c:_drm_edid_connector_property_update",
        "drivers/gpu/drm/drm_edid.c:drm_parse_vesa_mso_data",
        "drivers/gpu/drm/drm_edid.c:drm_parse_vesa_mso_data",
        "drivers/gpu/drm/drm_edid.c:drm_parse_vesa_mso_data",
        "drivers/gpu/drm/drm_edid.c:drm_parse_vesa_mso_data",
        "drivers/gpu/drm/drm_edid.c:drm_parse_vesa_mso_data",
        "drivers/gpu/drm/drm_edid.c:drm_parse_cea_ext",
        "drivers/gpu/drm/drm_edid.c:drm_parse_cea_ext",
        "drivers/gpu/drm/drm_edid.c:drm_parse_cea_ext",
        "drivers/gpu/drm/drm_edid.c:drm_parse_cea_ext",
        "drivers/gpu/drm/drm_edid.c:drm_parse_cea_ext",
        "drivers/gpu/drm/drm_edid.c:drm_parse_hdmi_deep_color_info",
        "drivers/gpu/drm/drm_edid.c:drm_parse_hdmi_deep_color_info",
        "drivers/gpu/drm/drm_edid.c:drm_parse_hdmi_deep_color_info",
        "drivers/gpu/drm/drm_edid.c:drm_parse_hdmi_deep_color_info",
        "drivers/gpu/drm/drm_edid.c:drm_parse_hdmi_deep_color_info",
        "drivers/gpu/drm/drm_edid.c:drm_parse_hdmi_deep_color_info",
        "drivers/gpu/drm/drm_edid.c:drm_parse_hdmi_deep_color_info",
        "drivers/gpu/drm/drm_edid.c:drm_edid_to_eld",
        "drivers/gpu/drm/drm_edid.c:drm_edid_to_eld",
        "drivers/gpu/drm/drm_edid.c:drm_edid_to_eld",
        "drivers/gpu/drm/drm_edid.c:fixup_detailed_cea_mode_clock",
        "drivers/gpu/drm/drm_edid.c:drm_mode_detailed",
        "drivers/gpu/drm/drm_edid.c:drm_mode_detailed",
        "drivers/gpu/drm/drm_edid.c:drm_mode_detailed",
        "drivers/gpu/drm/drm_edid.c:drm_mode_detailed",
        "drivers/gpu/drm/drm_edid.c:drm_mode_detailed",
        "drivers/gpu/drm/drm_edid.c:drm_edid_override_connector_update",
        "drivers/gpu/drm/drm_edid.c:drm_edid_override_reset",
        "drivers/gpu/drm/drm_edid.c:drm_edid_override_set",
        "drivers/gpu/drm/drm_edid.c:drm_edid_override_set",
        "drivers/gpu/drm/drm_edid.c:connector_bad_edid",
        "drivers/gpu/drm/drm_file.c:drm_release",
        "drivers/gpu/drm/drm_file.c:drm_lastclose",
        "drivers/gpu/drm/drm_file.c:drm_lastclose",
        "drivers/gpu/drm/drm_file.c:drm_lastclose",
        "drivers/gpu/drm/drm_file.c:drm_open_helper",
        "drivers/gpu/drm/drm_file.c:drm_file_free",
        "drivers/gpu/drm/drm_framebuffer.c:drm_framebuffer_remove",
        "drivers/gpu/drm/drm_framebuffer.c:drm_framebuffer_remove",
        "drivers/gpu/drm/drm_framebuffer.c:atomic_remove_fb",
        "drivers/gpu/drm/drm_framebuffer.c:atomic_remove_fb",
        "drivers/gpu/drm/drm_framebuffer.c:drm_mode_rmfb_work_fn",
        "drivers/gpu/drm/drm_framebuffer.c:drm_mode_addfb2",
        "drivers/gpu/drm/drm_framebuffer.c:drm_internal_framebuffer_create",
        "drivers/gpu/drm/drm_framebuffer.c:drm_internal_framebuffer_create",
        "drivers/gpu/drm/drm_framebuffer.c:drm_internal_framebuffer_create",
        "drivers/gpu/drm/drm_framebuffer.c:drm_internal_framebuffer_create",
        "drivers/gpu/drm/drm_framebuffer.c:framebuffer_check",
        "drivers/gpu/drm/drm_framebuffer.c:framebuffer_check",
        "drivers/gpu/drm/drm_framebuffer.c:framebuffer_check",
        "drivers/gpu/drm/drm_framebuffer.c:framebuffer_check",
        "drivers/gpu/drm/drm_framebuffer.c:framebuffer_check",
        "drivers/gpu/drm/drm_framebuffer.c:framebuffer_check",
        "drivers/gpu/drm/drm_framebuffer.c:framebuffer_check",
        "drivers/gpu/drm/drm_framebuffer.c:framebuffer_check",
        "drivers/gpu/drm/drm_framebuffer.c:framebuffer_check",
        "drivers/gpu/drm/drm_framebuffer.c:framebuffer_check",
        "drivers/gpu/drm/drm_framebuffer.c:framebuffer_check",
        "drivers/gpu/drm/drm_framebuffer.c:framebuffer_check",
        "drivers/gpu/drm/drm_framebuffer.c:drm_mode_addfb",
        "drivers/gpu/drm/drm_framebuffer.c:drm_framebuffer_check_src_coords",
        "drivers/gpu/drm/drm_ioctl.c:drm_ioctl",
        "drivers/gpu/drm/drm_ioctl.c:drm_ioctl",
        "drivers/gpu/drm/drm_ioctl.c:drm_ioctl",
        "drivers/gpu/drm/drm_ioctl.c:drm_ioctl",
        "drivers/gpu/drm/drm_ioctl.c:drm_ioctl",
        "drivers/gpu/drm/drm_ioctl.c:drm_noop",
        "drivers/gpu/drm/drm_lease.c:drm_mode_revoke_lease_ioctl",
        "drivers/gpu/drm/drm_lease.c:drm_mode_get_lease_ioctl",
        "drivers/gpu/drm/drm_lease.c:drm_mode_get_lease_ioctl",
        "drivers/gpu/drm/drm_lease.c:drm_mode_list_lessees_ioctl",
        "drivers/gpu/drm/drm_lease.c:drm_mode_list_lessees_ioctl",
        "drivers/gpu/drm/drm_lease.c:drm_mode_list_lessees_ioctl",
        "drivers/gpu/drm/drm_lease.c:drm_mode_list_lessees_ioctl",
        "drivers/gpu/drm/drm_lease.c:drm_mode_list_lessees_ioctl",
        "drivers/gpu/drm/drm_lease.c:drm_mode_list_lessees_ioctl",
        "drivers/gpu/drm/drm_lease.c:drm_mode_list_lessees_ioctl",
        "drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl",
        "drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl",
        "drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl",
        "drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl",
        "drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl",
        "drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl",
        "drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl",
        "drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl",
        "drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl",
        "drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl",
        "drivers/gpu/drm/drm_lease.c:fill_object_idr",
        "drivers/gpu/drm/drm_lease.c:fill_object_idr",
        "drivers/gpu/drm/drm_lease.c:fill_object_idr",
        "drivers/gpu/drm/drm_lease.c:_drm_lease_revoke",
        "drivers/gpu/drm/drm_lease.c:drm_lease_destroy",
        "drivers/gpu/drm/drm_lease.c:drm_lease_destroy",
        "drivers/gpu/drm/drm_lease.c:drm_lease_destroy",
        "drivers/gpu/drm/drm_lease.c:drm_lease_create",
        "drivers/gpu/drm/drm_lease.c:drm_lease_create",
        "drivers/gpu/drm/drm_lease.c:drm_lease_create",
        "drivers/gpu/drm/drm_lease.c:drm_lease_create",
        "drivers/gpu/drm/drm_lease.c:drm_lease_create",
        "drivers/gpu/drm/drm_managed.c:drmm_kmalloc",
        "drivers/gpu/drm/drm_managed.c:__drmm_add_action",
        "drivers/gpu/drm/drm_managed.c:add_dr",
        "drivers/gpu/drm/drm_managed.c:drm_managed_release",
        "drivers/gpu/drm/drm_managed.c:drm_managed_release",
        "drivers/gpu/drm/drm_managed.c:drm_managed_release",
        "drivers/gpu/drm/drm_managed.c:drm_managed_release",
        "drivers/gpu/drm/drm_mode_object.c:__drm_mode_object_find",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_property.c:drm_property_replace_blob_from_id",
        "drivers/gpu/drm/drm_property.c:drm_property_replace_blob_from_id",
        "drivers/gpu/drm/drm_sysfs.c:drm_sysfs_connector_property_event",
        "drivers/gpu/drm/drm_sysfs.c:drm_sysfs_connector_hotplug_event",
        "drivers/gpu/drm/drm_vblank.c:drm_crtc_queue_sequence_ioctl",
        "drivers/gpu/drm/drm_vblank.c:drm_crtc_get_sequence_ioctl",
        "drivers/gpu/drm/drm_vblank.c:drm_handle_vblank_events",
        "drivers/gpu/drm/drm_vblank.c:drm_wait_vblank_ioctl",
        "drivers/gpu/drm/drm_vblank.c:drm_wait_vblank_ioctl",
        "drivers/gpu/drm/drm_vblank.c:drm_wait_vblank_ioctl",
        "drivers/gpu/drm/drm_vblank.c:drm_wait_vblank_ioctl",
        "drivers/gpu/drm/drm_vblank.c:drm_wait_vblank_ioctl",
        "drivers/gpu/drm/drm_vblank.c:drm_queue_vblank_event",
        "drivers/gpu/drm/drm_vblank.c:drm_vblank_restore",
        "drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_on",
        "drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_off",
        "drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_off",
        "drivers/gpu/drm/drm_vblank.c:drm_vblank_enable",
        "drivers/gpu/drm/drm_vblank.c:drm_vblank_enable",
        "drivers/gpu/drm/drm_vblank.c:drm_vblank_enable",
        "drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_helper_get_vblank_timestamp_internal",
        "drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_helper_get_vblank_timestamp_internal",
        "drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_helper_get_vblank_timestamp_internal",
        "drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_helper_get_vblank_timestamp_internal",
        "drivers/gpu/drm/drm_vblank.c:drm_calc_timestamping_constants",
        "drivers/gpu/drm/drm_vblank.c:drm_calc_timestamping_constants",
        "drivers/gpu/drm/drm_vblank.c:drm_calc_timestamping_constants",
        "drivers/gpu/drm/drm_vblank.c:vblank_disable_fn",
        "drivers/gpu/drm/drm_vblank.c:drm_update_vblank_count",
        "drivers/gpu/drm/drm_vblank.c:drm_update_vblank_count",
        "drivers/gpu/drm/drm_vblank.c:drm_update_vblank_count",
        "drivers/gpu/drm/drm_vblank.c:drm_update_vblank_count",
        "drivers/gpu/drm/drm_vblank.c:drm_update_vblank_count",
        "drivers/gpu/drm/drm_vblank.c:drm_update_vblank_count",
        "drivers/gpu/drm/drm_vblank.c:drm_update_vblank_count",
        "drivers/gpu/drm/drm_vblank.c:drm_update_vblank_count",
        "drivers/gpu/drm/drm_vblank_work.c:drm_vblank_work_schedule",
        "drivers/gpu/drm/drm_ioc32.c:drm_compat_ioctl",
        "drivers/gpu/drm/drm_ioc32.c:drm_compat_ioctl",
        "drivers/gpu/drm/drm_ioc32.c:drm_compat_ioctl",
        "drivers/gpu/drm/drm_edid_load.c:drm_edid_load_firmware",
        "drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_prime_import_sg_table",
        "drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_vmap",
        "drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_get_pages",
        "drivers/gpu/drm/drm_atomic_helper.c:page_flip_common",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_async_check",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_async_check",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_async_check",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_async_check",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_async_check",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_async_check",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_commit_modeset_enables",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_commit_modeset_enables",
        "drivers/gpu/drm/drm_atomic_helper.c:crtc_set_mode",
        "drivers/gpu/drm/drm_atomic_helper.c:crtc_set_mode",
        "drivers/gpu/drm/drm_atomic_helper.c:disable_outputs",
        "drivers/gpu/drm/drm_atomic_helper.c:disable_outputs",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_check_planes",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_check_planes",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_check_crtc_primary_plane",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_check_plane_state",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_check_plane_state",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_check_plane_state",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_check_wb_connector_state",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_check_modeset",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_check_modeset",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_check_modeset",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_check_modeset",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_check_modeset",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_check_modeset",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_check_modeset",
        "drivers/gpu/drm/drm_atomic_helper.c:mode_valid",
        "drivers/gpu/drm/drm_atomic_helper.c:mode_valid",
        "drivers/gpu/drm/drm_atomic_helper.c:mode_valid",
        "drivers/gpu/drm/drm_atomic_helper.c:mode_fixup",
        "drivers/gpu/drm/drm_atomic_helper.c:mode_fixup",
        "drivers/gpu/drm/drm_atomic_helper.c:mode_fixup",
        "drivers/gpu/drm/drm_atomic_helper.c:mode_fixup",
        "drivers/gpu/drm/drm_atomic_helper.c:update_connector_routing",
        "drivers/gpu/drm/drm_atomic_helper.c:update_connector_routing",
        "drivers/gpu/drm/drm_atomic_helper.c:update_connector_routing",
        "drivers/gpu/drm/drm_atomic_helper.c:update_connector_routing",
        "drivers/gpu/drm/drm_atomic_helper.c:update_connector_routing",
        "drivers/gpu/drm/drm_atomic_helper.c:update_connector_routing",
        "drivers/gpu/drm/drm_atomic_helper.c:update_connector_routing",
        "drivers/gpu/drm/drm_atomic_helper.c:update_connector_routing",
        "drivers/gpu/drm/drm_atomic_helper.c:handle_conflicting_encoders",
        "drivers/gpu/drm/drm_atomic_helper.c:handle_conflicting_encoders",
        "drivers/gpu/drm/drm_atomic_helper.c:handle_conflicting_encoders",
        "drivers/gpu/drm/drm_format_helper.c:drm_fb_build_fourcc_list",
        "drivers/gpu/drm/drm_format_helper.c:drm_fb_build_fourcc_list",
        "drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_afbc_min_size",
        "drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_afbc_min_size",
        "drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_init_with_funcs",
        "drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_init_with_funcs",
        "drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_init_with_funcs",
        "drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_init_with_funcs",
        "drivers/gpu/drm/drm_probe_helper.c:drm_connector_helper_hpd_irq_event",
        "drivers/gpu/drm/drm_probe_helper.c:check_connector_changed",
        "drivers/gpu/drm/drm_probe_helper.c:check_connector_changed",
        "drivers/gpu/drm/drm_probe_helper.c:check_connector_changed",
        "drivers/gpu/drm/drm_probe_helper.c:check_connector_changed",
        "drivers/gpu/drm/drm_probe_helper.c:__drm_helper_update_and_validate",
        "drivers/gpu/drm/drm_fbdev_generic.c:drm_fbdev_generic_helper_fb_probe",
        "drivers/gpu/drm/drm_fb_helper.c:drm_fb_helper_hotplug_event",
        "drivers/gpu/drm/drm_fb_helper.c:drm_fb_helper_single_fb_probe",
        "drivers/gpu/drm/drm_fb_helper.c:__drm_fb_helper_find_sizes",
        "drivers/gpu/drm/drm_fb_helper.c:drm_fb_helper_check_var",
        "drivers/gpu/drm/drm_fb_helper.c:drm_fb_helper_check_var",
        "drivers/gpu/drm/drm_fb_helper.c:drm_fb_helper_check_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597708849,
      "name": "__drm_dev_dbg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071592138272,
      "name": "__drm_dev_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
void __drm_dev_dbg(struct _ddebug * desc, const struct device * dev, enum drm_debug_category category, const char * format, void (anon))
```
</details>
</li>
</ul>
