# Function: <code>vring_unmap_desc_packed</code>

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
  "name": "vring_unmap_desc_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585163016,
      "name": "vring_unmap_desc_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:933",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add",
        "drivers/virtio/virtio_ring.c:virtqueue_add",
        "drivers/virtio/virtio_ring.c:detach_buf_packed"
      ],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add",
        "drivers/virtio/virtio_ring.c:virtqueue_add",
        "drivers/virtio/virtio_ring.c:detach_buf_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585158144,
      "name": "vring_unmap_desc_packed.part.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vring_unmap_desc_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585375772,
      "name": "vring_unmap_desc_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:937",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:detach_buf_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed"
      ],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:detach_buf_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585367472,
      "name": "vring_unmap_desc_packed.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
  "name": "vring_unmap_desc_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585515484,
      "name": "vring_unmap_desc_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:937",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:detach_buf_packed"
      ],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:detach_buf_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585506208,
      "name": "vring_unmap_desc_packed.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vring_unmap_desc_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586228288,
      "name": "vring_unmap_desc_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:937",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:detach_buf_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed"
      ],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:detach_buf_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586227344,
      "name": "vring_unmap_desc_packed.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vring_unmap_desc_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586344293,
      "name": "vring_unmap_desc_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:937",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:detach_buf_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed"
      ],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:detach_buf_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586344000,
      "name": "vring_unmap_desc_packed.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vring_unmap_desc_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586228710,
      "name": "vring_unmap_desc_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:937",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:detach_buf_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed"
      ],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:detach_buf_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586228128,
      "name": "vring_unmap_desc_packed.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vring_unmap_desc_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586738181,
      "name": "vring_unmap_desc_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1010",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:detach_buf_packed",
        "drivers/virtio/virtio_ring.c:detach_buf_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed"
      ],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586735728,
      "name": "vring_unmap_desc_packed.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
void vring_unmap_desc_packed(const struct vring_virtqueue * vq, struct vring_packed_desc * desc)
```

```json
{
  "name": "vring_unmap_desc_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588008969,
      "name": "vring_unmap_desc_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1011",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:detach_buf_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588008928,
      "name": "vring_unmap_desc_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071594296871,
      "name": "vring_unmap_desc_packed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void vring_unmap_desc_packed(const struct vring_virtqueue * vq, struct vring_packed_desc * desc)
```

```json
{
  "name": "vring_unmap_desc_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589380729,
      "name": "vring_unmap_desc_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1196",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:detach_buf_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589380688,
      "name": "vring_unmap_desc_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071596227390,
      "name": "vring_unmap_desc_packed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void vring_unmap_desc_packed(const struct vring_virtqueue * vq, const struct vring_packed_desc * desc)
```

```json
{
  "name": "vring_unmap_desc_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589679497,
      "name": "vring_unmap_desc_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1216",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:detach_buf_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589679456,
      "name": "vring_unmap_desc_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071596755058,
      "name": "vring_unmap_desc_packed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void vring_unmap_desc_packed(const struct vring_virtqueue * vq, const struct vring_packed_desc * desc)
```

```json
{
  "name": "vring_unmap_desc_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590011561,
      "name": "vring_unmap_desc_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1249",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:detach_buf_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590011520,
      "name": "vring_unmap_desc_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071597663375,
      "name": "vring_unmap_desc_packed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
  "name": "vring_unmap_desc_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498173976,
      "name": "vring_unmap_desc_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:937",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:detach_buf_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed"
      ],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:detach_buf_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498161384,
      "name": "vring_unmap_desc_packed.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
  "name": "vring_unmap_desc_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230933676,
      "name": "vring_unmap_desc_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:937",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:detach_buf_packed"
      ],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:detach_buf_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230924740,
      "name": "vring_unmap_desc_packed.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "vring_unmap_desc_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291405632,
      "name": "vring_unmap_desc_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:937",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:detach_buf_packed"
      ],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:detach_buf_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291391056,
      "name": "vring_unmap_desc_packed.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "vring_unmap_desc_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275949684,
      "name": "vring_unmap_desc_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:937",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:detach_buf_packed"
      ],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:detach_buf_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275943370,
      "name": "vring_unmap_desc_packed.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vring_unmap_desc_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585277564,
      "name": "vring_unmap_desc_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:937",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:detach_buf_packed"
      ],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:detach_buf_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585268288,
      "name": "vring_unmap_desc_packed.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vring_unmap_desc_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585230028,
      "name": "vring_unmap_desc_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:937",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:detach_buf_packed"
      ],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:detach_buf_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585220752,
      "name": "vring_unmap_desc_packed.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vring_unmap_desc_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585465884,
      "name": "vring_unmap_desc_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:937",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:detach_buf_packed"
      ],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:detach_buf_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585456608,
      "name": "vring_unmap_desc_packed.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vring_unmap_desc_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585574060,
      "name": "vring_unmap_desc_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:937",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:detach_buf_packed"
      ],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:detach_buf_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585564784,
      "name": "vring_unmap_desc_packed.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void vring_unmap_desc_packed(const struct vring_virtqueue * vq, struct vring_packed_desc * desc)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct vring_packed_desc * desc</code> ➡️ <code>const struct vring_packed_desc * desc</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
