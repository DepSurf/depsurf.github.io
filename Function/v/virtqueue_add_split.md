# Function: <code>virtqueue_add_split</code>

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
  "name": "virtqueue_add_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585162450,
      "name": "virtqueue_add_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:417",
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
int virtqueue_add_split(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_split",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585374984,
      "name": "virtqueue_add_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:415",
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
      "addr": 18446744071585369488,
      "name": "virtqueue_add_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1195
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
int virtqueue_add_split(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_split",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585514852,
      "name": "virtqueue_add_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:415",
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
      "addr": 18446744071585508080,
      "name": "virtqueue_add_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1219
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
int virtqueue_add_split(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586229104,
      "name": "virtqueue_add_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:415",
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
      "addr": 18446744071586229104,
      "name": "virtqueue_add_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1249
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
int virtqueue_add_split(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586347456,
      "name": "virtqueue_add_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:415",
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
      "addr": 18446744071586347456,
      "name": "virtqueue_add_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1249
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
int virtqueue_add_split(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586231424,
      "name": "virtqueue_add_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:415",
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
      "addr": 18446744071586231424,
      "name": "virtqueue_add_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1177
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
int virtqueue_add_split(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_add_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:478",
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
      "addr": 18446744071586739552,
      "name": "virtqueue_add_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1528
    },
    {
      "addr": 18446744071592430105,
      "name": "virtqueue_add_split.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
int virtqueue_add_split(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_add_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:470",
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
      "addr": 18446744071588013824,
      "name": "virtqueue_add_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1653
    },
    {
      "addr": 18446744071594298088,
      "name": "virtqueue_add_split.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
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
int virtqueue_add_split(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_add_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:517",
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
      "addr": 18446744071589387472,
      "name": "virtqueue_add_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1678
    },
    {
      "addr": 18446744071596228475,
      "name": "virtqueue_add_split.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
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
int virtqueue_add_split(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_add_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:523",
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
      "addr": 18446744071589686304,
      "name": "virtqueue_add_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1665
    },
    {
      "addr": 18446744071596756164,
      "name": "virtqueue_add_split.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
int virtqueue_add_split(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_add_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:544",
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
      "addr": 18446744071590019088,
      "name": "virtqueue_add_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1730
    },
    {
      "addr": 18446744071597664600,
      "name": "virtqueue_add_split.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
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
int virtqueue_add_split(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_split",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498173132,
      "name": "virtqueue_add_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:415",
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
      "addr": 18446603336498161624,
      "name": "virtqueue_add_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1316
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
int virtqueue_add_split(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_split",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230933020,
      "name": "virtqueue_add_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:415",
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
      "addr": 3230930888,
      "name": "virtqueue_add_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1404
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
int virtqueue_add_split(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_split",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291403536,
      "name": "virtqueue_add_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:415",
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
      "addr": 13835058055291393824,
      "name": "virtqueue_add_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1512
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
int virtqueue_add_split(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_split",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275948764,
      "name": "virtqueue_add_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:415",
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
      "addr": 18446743936275954696,
      "name": "virtqueue_add_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1000
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
int virtqueue_add_split(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_split",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585276932,
      "name": "virtqueue_add_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:415",
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
      "addr": 18446744071585270160,
      "name": "virtqueue_add_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1219
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
int virtqueue_add_split(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_split",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585229396,
      "name": "virtqueue_add_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:415",
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
      "addr": 18446744071585222624,
      "name": "virtqueue_add_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1219
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
int virtqueue_add_split(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_split",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585465252,
      "name": "virtqueue_add_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:415",
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
      "addr": 18446744071585458480,
      "name": "virtqueue_add_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1219
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
int virtqueue_add_split(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_split",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585573428,
      "name": "virtqueue_add_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:415",
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
      "addr": 18446744071585566656,
      "name": "virtqueue_add_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1219
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
int virtqueue_add_split(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
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
