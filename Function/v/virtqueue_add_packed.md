# Function: <code>virtqueue_add_packed</code>

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
  "name": "virtqueue_add_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585162015,
      "name": "virtqueue_add_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1086",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int virtqueue_add_packed(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585374610,
      "name": "virtqueue_add_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1091",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf"
      ],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585368384,
      "name": "virtqueue_add_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 990
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int virtqueue_add_packed(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585514481,
      "name": "virtqueue_add_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1091",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf"
      ],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585506304,
      "name": "virtqueue_add_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1658
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
int virtqueue_add_packed(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586232416,
      "name": "virtqueue_add_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1091",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586232416,
      "name": "virtqueue_add_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1045
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
int virtqueue_add_packed(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586350800,
      "name": "virtqueue_add_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1091",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586350800,
      "name": "virtqueue_add_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1045
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
int virtqueue_add_packed(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586233888,
      "name": "virtqueue_add_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1091",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586233888,
      "name": "virtqueue_add_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 999
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
int virtqueue_add_packed(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_add_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1166",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586742496,
      "name": "virtqueue_add_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1156
    },
    {
      "addr": 18446744071592430602,
      "name": "virtqueue_add_packed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
int virtqueue_add_packed(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_add_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1159",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588017872,
      "name": "virtqueue_add_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1200
    },
    {
      "addr": 18446744071594298656,
      "name": "virtqueue_add_packed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
int virtqueue_add_packed(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_add_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1344",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589393696,
      "name": "virtqueue_add_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1241
    },
    {
      "addr": 18446744071596229286,
      "name": "virtqueue_add_packed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
int virtqueue_add_packed(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_add_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1364",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589692896,
      "name": "virtqueue_add_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1204
    },
    {
      "addr": 18446744071596756998,
      "name": "virtqueue_add_packed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
int virtqueue_add_packed(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_add_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1401",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590025616,
      "name": "virtqueue_add_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1256
    },
    {
      "addr": 18446744071597665337,
      "name": "virtqueue_add_packed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int virtqueue_add_packed(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498172784,
      "name": "virtqueue_add_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1091",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf"
      ],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498166376,
      "name": "virtqueue_add_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int virtqueue_add_packed(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230932556,
      "name": "virtqueue_add_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1091",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf"
      ],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230924872,
      "name": "virtqueue_add_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2008
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int virtqueue_add_packed(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291402712,
      "name": "virtqueue_add_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1091",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf"
      ],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291391248,
      "name": "virtqueue_add_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2372
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int virtqueue_add_packed(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275948482,
      "name": "virtqueue_add_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1091",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf"
      ],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275943468,
      "name": "virtqueue_add_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1590
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int virtqueue_add_packed(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585276561,
      "name": "virtqueue_add_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1091",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf"
      ],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585268384,
      "name": "virtqueue_add_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1658
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int virtqueue_add_packed(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585229025,
      "name": "virtqueue_add_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1091",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf"
      ],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585220848,
      "name": "virtqueue_add_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1658
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int virtqueue_add_packed(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585464881,
      "name": "virtqueue_add_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1091",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf"
      ],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585456704,
      "name": "virtqueue_add_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1658
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int virtqueue_add_packed(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585573057,
      "name": "virtqueue_add_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1091",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf"
      ],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585564880,
      "name": "virtqueue_add_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1658
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int virtqueue_add_packed(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```
</details>
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
