# Function: <code>detach_buf_packed</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void detach_buf_packed(struct vring_virtqueue * vq, unsigned int id, void * * ctx)
```

```json
{
  "name": "detach_buf_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585158688,
      "name": "detach_buf_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1276",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf",
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585158688,
      "name": "detach_buf_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
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
void detach_buf_packed(struct vring_virtqueue * vq, unsigned int id, void * * ctx)
```

```json
{
  "name": "detach_buf_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585376320,
      "name": "detach_buf_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1281",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf",
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585376320,
      "name": "detach_buf_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
void detach_buf_packed(struct vring_virtqueue * vq, unsigned int id, void * * ctx)
```

```json
{
  "name": "detach_buf_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585516800,
      "name": "detach_buf_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1281",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf",
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585516800,
      "name": "detach_buf_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
void detach_buf_packed(struct vring_virtqueue * vq, unsigned int id, void * * ctx)
```

```json
{
  "name": "detach_buf_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586228096,
      "name": "detach_buf_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1281",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf",
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586228096,
      "name": "detach_buf_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
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
void detach_buf_packed(struct vring_virtqueue * vq, unsigned int id, void * * ctx)
```

```json
{
  "name": "detach_buf_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586344128,
      "name": "detach_buf_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1281",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf",
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586344128,
      "name": "detach_buf_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
void detach_buf_packed(struct vring_virtqueue * vq, unsigned int id, void * * ctx)
```

```json
{
  "name": "detach_buf_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586228544,
      "name": "detach_buf_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1281",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf",
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586228544,
      "name": "detach_buf_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void detach_buf_packed(struct vring_virtqueue * vq, unsigned int id, void * * ctx)
```

```json
{
  "name": "detach_buf_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "detach_buf_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1367",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf",
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586737968,
      "name": "detach_buf_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
    },
    {
      "addr": 18446744071592429685,
      "name": "detach_buf_packed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void detach_buf_packed(struct vring_virtqueue * vq, unsigned int id, void * * ctx)
```

```json
{
  "name": "detach_buf_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "detach_buf_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1359",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf",
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588009040,
      "name": "detach_buf_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
    },
    {
      "addr": 18446744071594296892,
      "name": "detach_buf_packed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void detach_buf_packed(struct vring_virtqueue * vq, unsigned int id, void * * ctx)
```

```json
{
  "name": "detach_buf_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "detach_buf_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1544",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf",
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589380816,
      "name": "detach_buf_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
    },
    {
      "addr": 18446744071596227411,
      "name": "detach_buf_packed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void detach_buf_packed(struct vring_virtqueue * vq, unsigned int id, void * * ctx)
```

```json
{
  "name": "detach_buf_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "detach_buf_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1564",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf",
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589679584,
      "name": "detach_buf_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
    },
    {
      "addr": 18446744071596755079,
      "name": "detach_buf_packed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void detach_buf_packed(struct vring_virtqueue * vq, unsigned int id, void * * ctx)
```

```json
{
  "name": "detach_buf_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "detach_buf_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1602",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf",
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590011648,
      "name": "detach_buf_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
    },
    {
      "addr": 18446744071597663396,
      "name": "detach_buf_packed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void detach_buf_packed(struct vring_virtqueue * vq, unsigned int id, void * * ctx)
```

```json
{
  "name": "detach_buf_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498163328,
      "name": "detach_buf_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1281",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf",
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498163328,
      "name": "detach_buf_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
void detach_buf_packed(struct vring_virtqueue * vq, unsigned int id, void * * ctx)
```

```json
{
  "name": "detach_buf_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230927388,
      "name": "detach_buf_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1281",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf",
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230927388,
      "name": "detach_buf_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
void detach_buf_packed(struct vring_virtqueue * vq, unsigned int id, void * * ctx)
```

```json
{
  "name": "detach_buf_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291406032,
      "name": "detach_buf_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1281",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf",
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291406032,
      "name": "detach_buf_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
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
void detach_buf_packed(struct vring_virtqueue * vq, unsigned int id, void * * ctx)
```

```json
{
  "name": "detach_buf_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275945474,
      "name": "detach_buf_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1281",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf",
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275945474,
      "name": "detach_buf_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
void detach_buf_packed(struct vring_virtqueue * vq, unsigned int id, void * * ctx)
```

```json
{
  "name": "detach_buf_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585278880,
      "name": "detach_buf_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1281",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf",
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585278880,
      "name": "detach_buf_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
void detach_buf_packed(struct vring_virtqueue * vq, unsigned int id, void * * ctx)
```

```json
{
  "name": "detach_buf_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585231344,
      "name": "detach_buf_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1281",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf",
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585231344,
      "name": "detach_buf_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
void detach_buf_packed(struct vring_virtqueue * vq, unsigned int id, void * * ctx)
```

```json
{
  "name": "detach_buf_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585467200,
      "name": "detach_buf_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1281",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf",
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585467200,
      "name": "detach_buf_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
void detach_buf_packed(struct vring_virtqueue * vq, unsigned int id, void * * ctx)
```

```json
{
  "name": "detach_buf_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585575376,
      "name": "detach_buf_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1281",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf",
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585575376,
      "name": "detach_buf_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void detach_buf_packed(struct vring_virtqueue * vq, unsigned int id, void * * ctx)
```
</details>
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
