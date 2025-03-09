# Function: <code>sync_file_create</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct sync_file * sync_file_create(struct fence * fence)
```

```json
{
  "name": "sync_file_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585125072,
      "name": "sync_file_create",
      "external": true,
      "loc": "drivers/dma-buf/sync_file.c:75",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585125072,
      "name": "sync_file_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct sync_file * sync_file_create(struct dma_fence * fence)
```

```json
{
  "name": "sync_file_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585314416,
      "name": "sync_file_create",
      "external": true,
      "loc": "drivers/dma-buf/sync_file.c:74",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585314416,
      "name": "sync_file_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct sync_file * sync_file_create(struct dma_fence * fence)
```

```json
{
  "name": "sync_file_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585401984,
      "name": "sync_file_create",
      "external": true,
      "loc": "drivers/dma-buf/sync_file.c:73",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585401984,
      "name": "sync_file_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct sync_file * sync_file_create(struct dma_fence * fence)
```

```json
{
  "name": "sync_file_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585831632,
      "name": "sync_file_create",
      "external": true,
      "loc": "drivers/dma-buf/sync_file.c:73",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585831632,
      "name": "sync_file_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct sync_file * sync_file_create(struct dma_fence * fence)
```

```json
{
  "name": "sync_file_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586078720,
      "name": "sync_file_create",
      "external": true,
      "loc": "drivers/dma-buf/sync_file.c:73",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586078720,
      "name": "sync_file_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct sync_file * sync_file_create(struct dma_fence * fence)
```

```json
{
  "name": "sync_file_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586222992,
      "name": "sync_file_create",
      "external": true,
      "loc": "drivers/dma-buf/sync_file.c:73",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586222992,
      "name": "sync_file_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct sync_file * sync_file_create(struct dma_fence * fence)
```

```json
{
  "name": "sync_file_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586466640,
      "name": "sync_file_create",
      "external": true,
      "loc": "drivers/dma-buf/sync_file.c:64",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586466640,
      "name": "sync_file_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct sync_file * sync_file_create(struct dma_fence * fence)
```

```json
{
  "name": "sync_file_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586614528,
      "name": "sync_file_create",
      "external": true,
      "loc": "drivers/dma-buf/sync_file.c:64",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586614528,
      "name": "sync_file_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct sync_file * sync_file_create(struct dma_fence * fence)
```

```json
{
  "name": "sync_file_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587409040,
      "name": "sync_file_create",
      "external": true,
      "loc": "drivers/dma-buf/sync_file.c:64",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl_create_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587409040,
      "name": "sync_file_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct sync_file * sync_file_create(struct dma_fence * fence)
```

```json
{
  "name": "sync_file_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587478128,
      "name": "sync_file_create",
      "external": true,
      "loc": "drivers/dma-buf/sync_file.c:64",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl_create_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587478128,
      "name": "sync_file_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct sync_file * sync_file_create(struct dma_fence * fence)
```

```json
{
  "name": "sync_file_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587359584,
      "name": "sync_file_create",
      "external": true,
      "loc": "drivers/dma-buf/sync_file.c:64",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587359584,
      "name": "sync_file_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct sync_file * sync_file_create(struct dma_fence * fence)
```

```json
{
  "name": "sync_file_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587926512,
      "name": "sync_file_create",
      "external": true,
      "loc": "drivers/dma-buf/sync_file.c:64",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587926512,
      "name": "sync_file_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct sync_file * sync_file_create(struct dma_fence * fence)
```

```json
{
  "name": "sync_file_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589278064,
      "name": "sync_file_create",
      "external": true,
      "loc": "drivers/dma-buf/sync_file.c:65",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589278064,
      "name": "sync_file_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct sync_file * sync_file_create(struct dma_fence * fence)
```

```json
{
  "name": "sync_file_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590842080,
      "name": "sync_file_create",
      "external": true,
      "loc": "drivers/dma-buf/sync_file.c:65",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590842080,
      "name": "sync_file_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct sync_file * sync_file_create(struct dma_fence * fence)
```

```json
{
  "name": "sync_file_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591184144,
      "name": "sync_file_create",
      "external": true,
      "loc": "drivers/dma-buf/sync_file.c:65",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591184144,
      "name": "sync_file_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct sync_file * sync_file_create(struct dma_fence * fence)
```

```json
{
  "name": "sync_file_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591530176,
      "name": "sync_file_create",
      "external": true,
      "loc": "drivers/dma-buf/sync_file.c:65",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/gpu/drm/drm_atomic_uapi.c:prepare_signaling",
        "drivers/gpu/drm/drm_atomic_uapi.c:prepare_signaling",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_handle_to_fd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591530176,
      "name": "sync_file_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct sync_file * sync_file_create(struct dma_fence * fence)
```

```json
{
  "name": "sync_file_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499502824,
      "name": "sync_file_create",
      "external": true,
      "loc": "drivers/dma-buf/sync_file.c:64",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499502824,
      "name": "sync_file_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct sync_file * sync_file_create(struct dma_fence * fence)
```

```json
{
  "name": "sync_file_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231973300,
      "name": "sync_file_create",
      "external": true,
      "loc": "drivers/dma-buf/sync_file.c:64",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231973300,
      "name": "sync_file_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct sync_file * sync_file_create(struct dma_fence * fence)
```

```json
{
  "name": "sync_file_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292791312,
      "name": "sync_file_create",
      "external": true,
      "loc": "drivers/dma-buf/sync_file.c:64",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292791312,
      "name": "sync_file_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct sync_file * sync_file_create(struct dma_fence * fence)
```

```json
{
  "name": "sync_file_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276715738,
      "name": "sync_file_create",
      "external": true,
      "loc": "drivers/dma-buf/sync_file.c:64",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276715738,
      "name": "sync_file_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct sync_file * sync_file_create(struct dma_fence * fence)
```

```json
{
  "name": "sync_file_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586305008,
      "name": "sync_file_create",
      "external": true,
      "loc": "drivers/dma-buf/sync_file.c:64",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586305008,
      "name": "sync_file_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct sync_file * sync_file_create(struct dma_fence * fence)
```

```json
{
  "name": "sync_file_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586146384,
      "name": "sync_file_create",
      "external": true,
      "loc": "drivers/dma-buf/sync_file.c:64",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586146384,
      "name": "sync_file_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct sync_file * sync_file_create(struct dma_fence * fence)
```

```json
{
  "name": "sync_file_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586562496,
      "name": "sync_file_create",
      "external": true,
      "loc": "drivers/dma-buf/sync_file.c:64",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586562496,
      "name": "sync_file_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct sync_file * sync_file_create(struct dma_fence * fence)
```

```json
{
  "name": "sync_file_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586674784,
      "name": "sync_file_create",
      "external": true,
      "loc": "drivers/dma-buf/sync_file.c:64",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586674784,
      "name": "sync_file_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct sync_file * sync_file_create(struct fence * fence)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct fence * fence</code> ➡️ <code>struct dma_fence * fence</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
