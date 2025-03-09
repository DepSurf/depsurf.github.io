# Function: <code>virtqueue_get_buf_ctx</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * virtqueue_get_buf_ctx(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584413632,
      "name": "virtqueue_get_buf_ctx",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:700",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584413632,
      "name": "virtqueue_get_buf_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * virtqueue_get_buf_ctx(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584820864,
      "name": "virtqueue_get_buf_ctx",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:699",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584820864,
      "name": "virtqueue_get_buf_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
void * virtqueue_get_buf_ctx(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585051568,
      "name": "virtqueue_get_buf_ctx",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:698",
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
      "addr": 18446744071585051568,
      "name": "virtqueue_get_buf_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void * virtqueue_get_buf_ctx(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585159328,
      "name": "virtqueue_get_buf_ctx",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1889",
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
      "addr": 18446744071585159328,
      "name": "virtqueue_get_buf_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 633
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void * virtqueue_get_buf_ctx(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_get_buf_ctx",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1895",
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
      "addr": 18446744071585377451,
      "name": "virtqueue_get_buf_ctx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071585376928,
      "name": "virtqueue_get_buf_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 477
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void * virtqueue_get_buf_ctx(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_get_buf_ctx",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1894",
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
      "addr": 18446744071585517931,
      "name": "virtqueue_get_buf_ctx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071585517408,
      "name": "virtqueue_get_buf_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 477
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * virtqueue_get_buf_ctx(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586229077,
      "name": "virtqueue_get_buf_ctx",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1894",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586229040,
      "name": "virtqueue_get_buf_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * virtqueue_get_buf_ctx(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586346693,
      "name": "virtqueue_get_buf_ctx",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1894",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586346464,
      "name": "virtqueue_get_buf_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * virtqueue_get_buf_ctx(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586231045,
      "name": "virtqueue_get_buf_ctx",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1896",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586230304,
      "name": "virtqueue_get_buf_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * virtqueue_get_buf_ctx(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586739390,
      "name": "virtqueue_get_buf_ctx",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1994",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592430036,
      "name": "virtqueue_get_buf_ctx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071586739024,
      "name": "virtqueue_get_buf_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * virtqueue_get_buf_ctx(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588013648,
      "name": "virtqueue_get_buf_ctx",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1998",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594297717,
      "name": "virtqueue_get_buf_ctx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071588011888,
      "name": "virtqueue_get_buf_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * virtqueue_get_buf_ctx(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589387056,
      "name": "virtqueue_get_buf_ctx",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2284",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596227701,
      "name": "virtqueue_get_buf_ctx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071589382848,
      "name": "virtqueue_get_buf_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * virtqueue_get_buf_ctx(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589685888,
      "name": "virtqueue_get_buf_ctx",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2321",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf"
      ],
      "caller_func": [
        "drivers/net/virtio_net.c:receive_mergeable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596756009,
      "name": "virtqueue_get_buf_ctx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071589683856,
      "name": "virtqueue_get_buf_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * virtqueue_get_buf_ctx(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590017952,
      "name": "virtqueue_get_buf_ctx",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2415",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_get_buf"
      ],
      "caller_func": [
        "drivers/net/virtio_net.c:virtnet_rq_get_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597664341,
      "name": "virtqueue_get_buf_ctx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071590015920,
      "name": "virtqueue_get_buf_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void * virtqueue_get_buf_ctx(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498164008,
      "name": "virtqueue_get_buf_ctx",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1894",
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
      "addr": 18446603336498164008,
      "name": "virtqueue_get_buf_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 708
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
void * virtqueue_get_buf_ctx(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230928056,
      "name": "virtqueue_get_buf_ctx",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1894",
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
      "addr": 3230928056,
      "name": "virtqueue_get_buf_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 680
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
void * virtqueue_get_buf_ctx(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291407104,
      "name": "virtqueue_get_buf_ctx",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1894",
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
      "addr": 13835058055291407104,
      "name": "virtqueue_get_buf_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 912
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
void * virtqueue_get_buf_ctx(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275945996,
      "name": "virtqueue_get_buf_ctx",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1894",
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
      "addr": 18446743936275945996,
      "name": "virtqueue_get_buf_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 586
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void * virtqueue_get_buf_ctx(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_get_buf_ctx",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1894",
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
      "addr": 18446744071585280011,
      "name": "virtqueue_get_buf_ctx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071585279488,
      "name": "virtqueue_get_buf_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 477
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void * virtqueue_get_buf_ctx(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_get_buf_ctx",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1894",
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
      "addr": 18446744071585232475,
      "name": "virtqueue_get_buf_ctx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071585231952,
      "name": "virtqueue_get_buf_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 477
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void * virtqueue_get_buf_ctx(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_get_buf_ctx",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1894",
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
      "addr": 18446744071585468331,
      "name": "virtqueue_get_buf_ctx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071585467808,
      "name": "virtqueue_get_buf_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 477
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void * virtqueue_get_buf_ctx(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```

```json
{
  "name": "virtqueue_get_buf_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_get_buf_ctx",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1894",
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
      "addr": 18446744071585576507,
      "name": "virtqueue_get_buf_ctx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071585575984,
      "name": "virtqueue_get_buf_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 477
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void * virtqueue_get_buf_ctx(struct virtqueue * _vq, unsigned int * len, void * * ctx)
```
</details>
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
