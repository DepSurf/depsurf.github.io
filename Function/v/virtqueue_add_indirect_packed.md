# Function: <code>virtqueue_add_indirect_packed</code>

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
  "name": "virtqueue_add_indirect_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585162835,
      "name": "virtqueue_add_indirect_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:975",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int virtqueue_add_indirect_packed(struct vring_virtqueue * vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_indirect_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585367568,
      "name": "virtqueue_add_indirect_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:979",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585367568,
      "name": "virtqueue_add_indirect_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 804
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virtqueue_add_indirect_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585515834,
      "name": "virtqueue_add_indirect_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:979",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int virtqueue_add_indirect_packed(struct vring_virtqueue * vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_indirect_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586231536,
      "name": "virtqueue_add_indirect_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:979",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586231536,
      "name": "virtqueue_add_indirect_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 879
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
int virtqueue_add_indirect_packed(struct vring_virtqueue * vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_indirect_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586349904,
      "name": "virtqueue_add_indirect_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:979",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586349904,
      "name": "virtqueue_add_indirect_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 884
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
int virtqueue_add_indirect_packed(struct vring_virtqueue * vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_indirect_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586233104,
      "name": "virtqueue_add_indirect_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:979",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586233104,
      "name": "virtqueue_add_indirect_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 779
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
int virtqueue_add_indirect_packed(struct vring_virtqueue * vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_indirect_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_add_indirect_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1052",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586741600,
      "name": "virtqueue_add_indirect_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 886
    },
    {
      "addr": 18446744071592430436,
      "name": "virtqueue_add_indirect_packed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
int virtqueue_add_indirect_packed(struct vring_virtqueue * vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_indirect_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_add_indirect_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1045",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588016992,
      "name": "virtqueue_add_indirect_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 877
    },
    {
      "addr": 18446744071594298462,
      "name": "virtqueue_add_indirect_packed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
int virtqueue_add_indirect_packed(struct vring_virtqueue * vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_indirect_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_add_indirect_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1230",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589392768,
      "name": "virtqueue_add_indirect_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 911
    },
    {
      "addr": 18446744071596229092,
      "name": "virtqueue_add_indirect_packed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
int virtqueue_add_indirect_packed(struct vring_virtqueue * vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_indirect_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_add_indirect_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1250",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589691984,
      "name": "virtqueue_add_indirect_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 890
    },
    {
      "addr": 18446744071596756804,
      "name": "virtqueue_add_indirect_packed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
int virtqueue_add_indirect_packed(struct vring_virtqueue * vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_indirect_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_add_indirect_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1283",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590024640,
      "name": "virtqueue_add_indirect_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 951
    },
    {
      "addr": 18446744071597665158,
      "name": "virtqueue_add_indirect_packed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int virtqueue_add_indirect_packed(struct vring_virtqueue * vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_indirect_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498165456,
      "name": "virtqueue_add_indirect_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:979",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498165456,
      "name": "virtqueue_add_indirect_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 916
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "virtqueue_add_indirect_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230934132,
      "name": "virtqueue_add_indirect_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:979",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf"
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
  "name": "virtqueue_add_indirect_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291404336,
      "name": "virtqueue_add_indirect_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:979",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf"
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
  "name": "virtqueue_add_indirect_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275949758,
      "name": "virtqueue_add_indirect_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:979",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf"
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
  "name": "virtqueue_add_indirect_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585277914,
      "name": "virtqueue_add_indirect_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:979",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf"
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
  "name": "virtqueue_add_indirect_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585230378,
      "name": "virtqueue_add_indirect_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:979",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf"
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
  "name": "virtqueue_add_indirect_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585466234,
      "name": "virtqueue_add_indirect_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:979",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf"
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
  "name": "virtqueue_add_indirect_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585574410,
      "name": "virtqueue_add_indirect_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:979",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf"
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int virtqueue_add_indirect_packed(struct vring_virtqueue * vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, gfp_t gfp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
int virtqueue_add_indirect_packed(struct vring_virtqueue * vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, gfp_t gfp)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int virtqueue_add_indirect_packed(struct vring_virtqueue * vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, gfp_t gfp)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int virtqueue_add_indirect_packed(struct vring_virtqueue * vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, gfp_t gfp)
```
</details>
</li>
</ul>
