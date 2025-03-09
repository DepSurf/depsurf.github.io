# Function: <code>drm_gem_object_free</code>

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
void drm_gem_object_free(struct kref * kref)
```

```json
{
  "name": "drm_gem_object_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592068538,
      "name": "drm_gem_object_free",
      "external": true,
      "loc": "drivers/gpu/drm/drm_gem.c:974",
      "file": "drivers/gpu/drm/drm_gem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_gem.c:drm_gem_lru_scan",
        "drivers/gpu/drm/drm_gem.c:drm_gem_mmap",
        "drivers/gpu/drm/drm_gem.c:drm_gem_mmap",
        "drivers/gpu/drm/drm_gem.c:drm_gem_mmap_obj",
        "drivers/gpu/drm/drm_gem.c:drm_gem_vm_close",
        "drivers/gpu/drm/drm_gem.c:drm_gem_open_ioctl",
        "drivers/gpu/drm/drm_gem.c:drm_gem_flink_ioctl",
        "drivers/gpu/drm/drm_gem.c:drm_gem_dma_resv_wait",
        "drivers/gpu/drm/drm_gem.c:drm_gem_dumb_map_offset",
        "drivers/gpu/drm/drm_gem.c:drm_gem_object_handle_put_unlocked"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_client.c:drm_client_buffer_delete",
        "drivers/gpu/drm/drm_prime.c:drm_gem_prime_mmap",
        "drivers/gpu/drm/drm_prime.c:drm_gem_prime_handle_to_fd",
        "drivers/gpu/drm/drm_prime.c:drm_gem_prime_fd_to_handle",
        "drivers/gpu/drm/drm_prime.c:drm_gem_dmabuf_release",
        "drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_dumb_create",
        "drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_init_with_funcs",
        "drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_init_with_funcs",
        "drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592064464,
      "name": "drm_gem_object_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void drm_gem_object_free(struct kref * kref)
```
</details>
</li>
</ul>
