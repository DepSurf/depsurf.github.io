# Function: <code>drm_modeset_unlock</code>

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
void drm_modeset_unlock(struct drm_modeset_lock * lock)
```

```json
{
  "name": "drm_modeset_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592119542,
      "name": "drm_modeset_unlock",
      "external": true,
      "loc": "drivers/gpu/drm/drm_modeset_lock.c:422",
      "file": "drivers/gpu/drm/drm_modeset_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_modeset_lock.c:drm_modeset_backoff",
        "drivers/gpu/drm/drm_modeset_lock.c:drm_modeset_unlock_all"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_atomic.c:__drm_state_dump",
        "drivers/gpu/drm/drm_atomic.c:__drm_state_dump",
        "drivers/gpu/drm/drm_atomic.c:__drm_state_dump",
        "drivers/gpu/drm/drm_atomic.c:__drm_state_dump",
        "drivers/gpu/drm/drm_color_mgmt.c:drm_mode_gamma_get_ioctl",
        "drivers/gpu/drm/drm_connector.c:drm_mode_getconnector",
        "drivers/gpu/drm/drm_connector.c:drm_connector_privacy_screen_notifier",
        "drivers/gpu/drm/drm_connector.c:drm_connector_set_link_status_property",
        "drivers/gpu/drm/drm_crtc.c:drm_mode_getcrtc",
        "drivers/gpu/drm/drm_crtc.c:drm_mode_getcrtc",
        "drivers/gpu/drm/drm_encoder.c:drm_mode_getencoder",
        "drivers/gpu/drm/drm_plane.c:drm_mode_getplane",
        "drivers/gpu/drm/drm_vblank.c:drm_crtc_get_sequence_ioctl",
        "drivers/gpu/drm/drm_debugfs_crc.c:crtc_crc_open",
        "drivers/gpu/drm/drm_debugfs_crc.c:crtc_crc_open",
        "drivers/gpu/drm/drm_damage_helper.c:drm_atomic_helper_dirtyfb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592117920,
      "name": "drm_modeset_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void drm_modeset_unlock(struct drm_modeset_lock * lock)
```
</details>
</li>
</ul>
