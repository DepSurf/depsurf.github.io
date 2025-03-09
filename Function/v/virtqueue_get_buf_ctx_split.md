# Function: <code>virtqueue_get_buf_ctx_split</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virtqueue_get_buf_ctx_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585159530,
      "name": "virtqueue_get_buf_ctx_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:676",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virtqueue_get_buf_ctx_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585377153,
      "name": "virtqueue_get_buf_ctx_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:678",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virtqueue_get_buf_ctx_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585517633,
      "name": "virtqueue_get_buf_ctx_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:678",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void * virtqueue_get_buf_ctx_split(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_get_buf_ctx_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:678",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586227856,
      "name": "virtqueue_get_buf_ctx_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071586234984,
      "name": "virtqueue_get_buf_ctx_split.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void * virtqueue_get_buf_ctx_split(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_get_buf_ctx_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:678",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586346240,
      "name": "virtqueue_get_buf_ctx_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
    },
    {
      "addr": 18446744071591446032,
      "name": "virtqueue_get_buf_ctx_split.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void * virtqueue_get_buf_ctx_split(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_get_buf_ctx_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:678",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586230080,
      "name": "virtqueue_get_buf_ctx_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
    },
    {
      "addr": 18446744071591387661,
      "name": "virtqueue_get_buf_ctx_split.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void * virtqueue_get_buf_ctx_split(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_get_buf_ctx_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:748",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586737680,
      "name": "virtqueue_get_buf_ctx_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
    },
    {
      "addr": 18446744071592429529,
      "name": "virtqueue_get_buf_ctx_split.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void * virtqueue_get_buf_ctx_split(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_get_buf_ctx_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:740",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588011584,
      "name": "virtqueue_get_buf_ctx_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
    },
    {
      "addr": 18446744071594297564,
      "name": "virtqueue_get_buf_ctx_split.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void * virtqueue_get_buf_ctx_split(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_get_buf_ctx_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:787",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589382464,
      "name": "virtqueue_get_buf_ctx_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
    },
    {
      "addr": 18446744071596227618,
      "name": "virtqueue_get_buf_ctx_split.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void * virtqueue_get_buf_ctx_split(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_get_buf_ctx_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:793",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589680704,
      "name": "virtqueue_get_buf_ctx_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
    },
    {
      "addr": 18446744071596755210,
      "name": "virtqueue_get_buf_ctx_split.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void * virtqueue_get_buf_ctx_split(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_get_buf_ctx_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:823",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590012592,
      "name": "virtqueue_get_buf_ctx_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
    },
    {
      "addr": 18446744071597663521,
      "name": "virtqueue_get_buf_ctx_split.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "virtqueue_get_buf_ctx_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498164288,
      "name": "virtqueue_get_buf_ctx_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:678",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "virtqueue_get_buf_ctx_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230928352,
      "name": "virtqueue_get_buf_ctx_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:678",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "virtqueue_get_buf_ctx_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291407216,
      "name": "virtqueue_get_buf_ctx_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:678",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "virtqueue_get_buf_ctx_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275946086,
      "name": "virtqueue_get_buf_ctx_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:678",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virtqueue_get_buf_ctx_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585279713,
      "name": "virtqueue_get_buf_ctx_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:678",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virtqueue_get_buf_ctx_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585232177,
      "name": "virtqueue_get_buf_ctx_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:678",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virtqueue_get_buf_ctx_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585468033,
      "name": "virtqueue_get_buf_ctx_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:678",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virtqueue_get_buf_ctx_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585576209,
      "name": "virtqueue_get_buf_ctx_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:678",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void * virtqueue_get_buf_ctx_split(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```
</details>
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
