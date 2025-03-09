# Function: <code>drm_vblank_put</code>

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
void drm_vblank_put(struct drm_device * dev, unsigned int pipe)
```

```json
{
  "name": "drm_vblank_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "drm_vblank_put",
      "external": true,
      "loc": "drivers/gpu/drm/drm_vblank.c:1229",
      "file": "drivers/gpu/drm/drm_vblank.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/drm/drm_vblank.c:drm_crtc_queue_sequence_ioctl",
        "drivers/gpu/drm/drm_vblank.c:drm_crtc_queue_sequence_ioctl",
        "drivers/gpu/drm/drm_vblank.c:drm_crtc_get_sequence_ioctl",
        "drivers/gpu/drm/drm_vblank.c:drm_handle_vblank_events",
        "drivers/gpu/drm/drm_vblank.c:drm_wait_vblank_ioctl",
        "drivers/gpu/drm/drm_vblank.c:drm_queue_vblank_event",
        "drivers/gpu/drm/drm_vblank.c:drm_queue_vblank_event",
        "drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_off",
        "drivers/gpu/drm/drm_vblank.c:drm_wait_one_vblank",
        "drivers/gpu/drm/drm_vblank_work.c:drm_vblank_work_cancel_sync",
        "drivers/gpu/drm/drm_vblank_work.c:drm_vblank_work_schedule",
        "drivers/gpu/drm/drm_vblank_work.c:drm_vblank_cancel_pending_works",
        "drivers/gpu/drm/drm_vblank_work.c:drm_handle_vblank_works"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597709331,
      "name": "drm_vblank_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071592173296,
      "name": "drm_vblank_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
void drm_vblank_put(struct drm_device * dev, unsigned int pipe)
```
</details>
</li>
</ul>
