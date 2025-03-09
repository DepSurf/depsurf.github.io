# Function: <code>virtqueue_get_buf_ctx_packed</code>

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
  "name": "virtqueue_get_buf_ctx_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585159359,
      "name": "virtqueue_get_buf_ctx_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1341",
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
  "name": "virtqueue_get_buf_ctx_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585376959,
      "name": "virtqueue_get_buf_ctx_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1346",
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
  "name": "virtqueue_get_buf_ctx_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585517439,
      "name": "virtqueue_get_buf_ctx_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1346",
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
void * virtqueue_get_buf_ctx_packed(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_get_buf_ctx_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1346",
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
      "addr": 18446744071586228736,
      "name": "virtqueue_get_buf_ctx_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
    },
    {
      "addr": 18446744071586235059,
      "name": "virtqueue_get_buf_ctx_packed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void * virtqueue_get_buf_ctx_packed(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_get_buf_ctx_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1346",
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
      "addr": 18446744071586344528,
      "name": "virtqueue_get_buf_ctx_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
    },
    {
      "addr": 18446744071591445959,
      "name": "virtqueue_get_buf_ctx_packed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void * virtqueue_get_buf_ctx_packed(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_get_buf_ctx_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1346",
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
      "addr": 18446744071586228928,
      "name": "virtqueue_get_buf_ctx_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
    },
    {
      "addr": 18446744071591387588,
      "name": "virtqueue_get_buf_ctx_packed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void * virtqueue_get_buf_ctx_packed(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_get_buf_ctx_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1432",
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
      "addr": 18446744071586738592,
      "name": "virtqueue_get_buf_ctx_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
    },
    {
      "addr": 18446744071592429796,
      "name": "virtqueue_get_buf_ctx_packed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
void * virtqueue_get_buf_ctx_packed(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_get_buf_ctx_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1430",
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
      "addr": 18446744071588009440,
      "name": "virtqueue_get_buf_ctx_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
    },
    {
      "addr": 18446744071594296955,
      "name": "virtqueue_get_buf_ctx_packed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void * virtqueue_get_buf_ctx_packed(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_get_buf_ctx_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1615",
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
      "addr": 18446744071589381232,
      "name": "virtqueue_get_buf_ctx_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 511
    },
    {
      "addr": 18446744071596227474,
      "name": "virtqueue_get_buf_ctx_packed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void * virtqueue_get_buf_ctx_packed(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_get_buf_ctx_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1635",
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
      "addr": 18446744071589683328,
      "name": "virtqueue_get_buf_ctx_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
    },
    {
      "addr": 18446744071596755933,
      "name": "virtqueue_get_buf_ctx_packed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void * virtqueue_get_buf_ctx_packed(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_get_buf_ctx_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1673",
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
      "addr": 18446744071590015392,
      "name": "virtqueue_get_buf_ctx_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
    },
    {
      "addr": 18446744071597664265,
      "name": "virtqueue_get_buf_ctx_packed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
  "name": "virtqueue_get_buf_ctx_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498164056,
      "name": "virtqueue_get_buf_ctx_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1346",
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
  "name": "virtqueue_get_buf_ctx_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230928100,
      "name": "virtqueue_get_buf_ctx_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1346",
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
  "name": "virtqueue_get_buf_ctx_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291407152,
      "name": "virtqueue_get_buf_ctx_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1346",
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
  "name": "virtqueue_get_buf_ctx_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275946038,
      "name": "virtqueue_get_buf_ctx_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1346",
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
  "name": "virtqueue_get_buf_ctx_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585279519,
      "name": "virtqueue_get_buf_ctx_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1346",
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
  "name": "virtqueue_get_buf_ctx_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585231983,
      "name": "virtqueue_get_buf_ctx_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1346",
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
  "name": "virtqueue_get_buf_ctx_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585467839,
      "name": "virtqueue_get_buf_ctx_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1346",
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
  "name": "virtqueue_get_buf_ctx_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585576015,
      "name": "virtqueue_get_buf_ctx_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1346",
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
void * virtqueue_get_buf_ctx_packed(struct virtqueue * _vq, unsigned int * len, void * * ctx)
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
