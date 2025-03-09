# Function: <code>__drm_err</code>

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
void __drm_err(const char * format, void (anon))
```

```json
{
  "name": "__drm_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592137600,
      "name": "__drm_err",
      "external": true,
      "loc": "drivers/gpu/drm/drm_print.c:326",
      "file": "drivers/gpu/drm/drm_print.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/drm/drm_bridge.c:drm_bridge_attach",
        "drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_probe",
        "drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_probe",
        "drivers/gpu/drm/drm_drv.c:drm_core_init",
        "drivers/gpu/drm/drm_drv.c:drm_dev_init",
        "drivers/gpu/drm/drm_drv.c:drm_dev_init",
        "drivers/gpu/drm/drm_drv.c:drm_dev_init",
        "drivers/gpu/drm/drm_drv.c:drm_dev_init",
        "drivers/gpu/drm/drm_drv.c:drm_dev_init",
        "drivers/gpu/drm/drm_drv.c:drm_minor_register",
        "drivers/gpu/drm/drm_framebuffer.c:drm_framebuffer_remove",
        "drivers/gpu/drm/drm_gem.c:drm_gem_init",
        "drivers/gpu/drm/drm_mode_config.c:drm_mode_config_cleanup",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_plane.c:drm_plane_force_disable",
        "drivers/gpu/drm/drm_debugfs_crc.c:drm_crtc_add_crc_entry",
        "drivers/accel/drm_accel.c:accel_core_init",
        "drivers/accel/drm_accel.c:accel_core_init",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_helper_resume_force_mode",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config",
        "drivers/gpu/drm/drm_modeset_helper.c:drm_mode_config_helper_resume",
        "drivers/gpu/drm/bridge/panel.c:panel_bridge_attach",
        "drivers/gpu/drm/bridge/panel.c:panel_bridge_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592137600,
      "name": "__drm_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void __drm_err(const char * format, void (anon))
```
</details>
</li>
</ul>
