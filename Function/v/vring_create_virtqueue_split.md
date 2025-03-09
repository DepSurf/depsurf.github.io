# Function: <code>vring_create_virtqueue_split</code>

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
  "name": "vring_create_virtqueue_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585160771,
      "name": "vring_create_virtqueue_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:843",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
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
  "name": "vring_create_virtqueue_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585365956,
      "name": "vring_create_virtqueue_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:845",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
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
  "name": "vring_create_virtqueue_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585504692,
      "name": "vring_create_virtqueue_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:845",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
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
struct virtqueue * vring_create_virtqueue_split(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_create_virtqueue_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vring_create_virtqueue_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:845",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586231040,
      "name": "vring_create_virtqueue_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
    },
    {
      "addr": 18446744071586235132,
      "name": "vring_create_virtqueue_split.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
struct virtqueue * vring_create_virtqueue_split(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_create_virtqueue_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vring_create_virtqueue_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:845",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586349408,
      "name": "vring_create_virtqueue_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
    },
    {
      "addr": 18446744071591446107,
      "name": "vring_create_virtqueue_split.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
struct virtqueue * vring_create_virtqueue_split(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_create_virtqueue_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vring_create_virtqueue_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:845",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586236048,
      "name": "vring_create_virtqueue_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
    },
    {
      "addr": 18446744071591387736,
      "name": "vring_create_virtqueue_split.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
struct virtqueue * vring_create_virtqueue_split(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_create_virtqueue_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vring_create_virtqueue_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:918",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586744960,
      "name": "vring_create_virtqueue_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
    },
    {
      "addr": 18446744071592430953,
      "name": "vring_create_virtqueue_split.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
struct virtqueue * vring_create_virtqueue_split(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_create_virtqueue_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vring_create_virtqueue_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:910",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588016336,
      "name": "vring_create_virtqueue_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 644
    },
    {
      "addr": 18446744071594298439,
      "name": "vring_create_virtqueue_split.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vring_create_virtqueue_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589391242,
      "name": "vring_create_virtqueue_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1093",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct virtqueue * vring_create_virtqueue_split(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name, struct device * dma_dev)
```

```json
{
  "name": "vring_create_virtqueue_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589689136,
      "name": "vring_create_virtqueue_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1111",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue_dma",
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589689136,
      "name": "vring_create_virtqueue_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
struct virtqueue * vring_create_virtqueue_split(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name, struct device * dma_dev)
```

```json
{
  "name": "vring_create_virtqueue_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590023008,
      "name": "vring_create_virtqueue_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1141",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue_dma",
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590023008,
      "name": "vring_create_virtqueue_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
  "name": "vring_create_virtqueue_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498168564,
      "name": "vring_create_virtqueue_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:845",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
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
  "name": "vring_create_virtqueue_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230930388,
      "name": "vring_create_virtqueue_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:845",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
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
  "name": "vring_create_virtqueue_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291388464,
      "name": "vring_create_virtqueue_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:845",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
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
  "name": "vring_create_virtqueue_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275947920,
      "name": "vring_create_virtqueue_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:845",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
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
  "name": "vring_create_virtqueue_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585266772,
      "name": "vring_create_virtqueue_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:845",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
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
  "name": "vring_create_virtqueue_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585219044,
      "name": "vring_create_virtqueue_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:845",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
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
  "name": "vring_create_virtqueue_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585455092,
      "name": "vring_create_virtqueue_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:845",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
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
  "name": "vring_create_virtqueue_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585563268,
      "name": "vring_create_virtqueue_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:845",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
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
struct virtqueue * vring_create_virtqueue_split(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
struct virtqueue * vring_create_virtqueue_split(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
struct virtqueue * vring_create_virtqueue_split(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name, struct device * dma_dev)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
