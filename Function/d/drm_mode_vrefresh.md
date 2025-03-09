# Function: <code>drm_mode_vrefresh</code>

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
int drm_mode_vrefresh(const struct drm_display_mode * mode)
```

```json
{
  "name": "drm_mode_vrefresh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592102960,
      "name": "drm_mode_vrefresh",
      "external": true,
      "loc": "drivers/gpu/drm/drm_modes.c:1286",
      "file": "drivers/gpu/drm/drm_modes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_crtc_print_state",
        "drivers/gpu/drm/drm_client_modeset.c:drm_connector_pick_cmdline_mode",
        "drivers/gpu/drm/drm_edid.c:drm_add_modes_noedid",
        "drivers/gpu/drm/drm_edid.c:do_hdmi_vsdb_modes",
        "drivers/gpu/drm/drm_edid.c:cea_mode_alternate_clock",
        "drivers/gpu/drm/drm_edid.c:valid_inferred_mode",
        "drivers/gpu/drm/drm_edid.c:valid_inferred_mode",
        "drivers/gpu/drm/drm_edid.c:mode_in_range",
        "drivers/gpu/drm/drm_edid.c:drm_mode_std",
        "drivers/gpu/drm/drm_edid.c:drm_mode_find_dmt",
        "drivers/gpu/drm/drm_modes.c:drm_mode_convert_to_umode",
        "drivers/gpu/drm/drm_modes.c:drm_mode_compare",
        "drivers/gpu/drm/drm_modes.c:drm_mode_compare",
        "drivers/gpu/drm/drm_modes.c:drm_mode_prune_invalid",
        "drivers/gpu/drm/drm_modes.c:fill_analog_mode",
        "drivers/gpu/drm/drm_modes.c:drm_mode_debug_printmodeline",
        "drivers/gpu/drm/drm_probe_helper.c:drm_connector_helper_get_modes_fixed",
        "drivers/gpu/drm/drm_probe_helper.c:drm_helper_probe_single_connector_modes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592102960,
      "name": "drm_mode_vrefresh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int drm_mode_vrefresh(const struct drm_display_mode * mode)
```
</details>
</li>
</ul>
