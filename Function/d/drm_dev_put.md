# Function: <code>drm_dev_put</code>

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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void drm_dev_put(struct drm_device * dev)
```

```json
{
  "name": "drm_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592003446,
      "name": "drm_dev_put",
      "external": true,
      "loc": "drivers/gpu/drm/drm_drv.c:816",
      "file": "drivers/gpu/drm/drm_drv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_drv.c:drm_stub_open",
        "drivers/gpu/drm/drm_drv.c:devm_drm_dev_init_release",
        "drivers/gpu/drm/drm_drv.c:devm_drm_dev_init_release",
        "drivers/gpu/drm/drm_drv.c:drm_minor_acquire"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_atomic.c:__drm_atomic_state_free",
        "drivers/gpu/drm/drm_atomic.c:__drm_atomic_state_free",
        "drivers/gpu/drm/drm_client.c:drm_client_release",
        "drivers/gpu/drm/drm_drv.c:drm_stub_open",
        "drivers/gpu/drm/drm_drv.c:drm_minor_acquire",
        "drivers/gpu/drm/drm_prime.c:drm_gem_dmabuf_release",
        "drivers/gpu/drm/drm_prime.c:drm_gem_dmabuf_release",
        "drivers/accel/drm_accel.c:accel_stub_open",
        "drivers/accel/drm_accel.c:accel_open",
        "drivers/accel/drm_accel.c:accel_minor_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592002048,
      "name": "drm_dev_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071592002704,
      "name": "drm_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void drm_dev_put(struct drm_device * dev)
```
</details>
</li>
</ul>
