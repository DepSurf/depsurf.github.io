# Function: <code>__vring_new_virtqueue</code>

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
struct virtqueue * __vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device * vdev, bool weak_barriers, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "__vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584151088,
      "name": "__vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:912",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:vring_new_virtqueue",
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584151088,
      "name": "__vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
struct virtqueue * __vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device * vdev, bool weak_barriers, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "__vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584331728,
      "name": "__vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:915",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:vring_new_virtqueue",
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584331728,
      "name": "__vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
struct virtqueue * __vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device * vdev, bool weak_barriers, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "__vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584411936,
      "name": "__vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:958",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:vring_new_virtqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584411936,
      "name": "__vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
struct virtqueue * __vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device * vdev, bool weak_barriers, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "__vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584819424,
      "name": "__vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:957",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:vring_new_virtqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584819424,
      "name": "__vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
struct virtqueue * __vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device * vdev, bool weak_barriers, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "__vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585049872,
      "name": "__vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:956",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:vring_new_virtqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585049872,
      "name": "__vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
struct virtqueue * __vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device * vdev, bool weak_barriers, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "__vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585160000,
      "name": "__vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2048",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:vring_new_virtqueue",
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585160000,
      "name": "__vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
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
struct virtqueue * __vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device * vdev, bool weak_barriers, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "__vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585365184,
      "name": "__vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2054",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:vring_new_virtqueue",
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585365184,
      "name": "__vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 554
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
struct virtqueue * __vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device * vdev, bool weak_barriers, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "__vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585503920,
      "name": "__vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2053",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:vring_new_virtqueue",
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585503920,
      "name": "__vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 554
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
struct virtqueue * __vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device * vdev, bool weak_barriers, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "__vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586230368,
      "name": "__vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2056",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:vring_new_virtqueue",
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586230368,
      "name": "__vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
struct virtqueue * __vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device * vdev, bool weak_barriers, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "__vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586348720,
      "name": "__vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2056",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:vring_new_virtqueue",
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586348720,
      "name": "__vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 566
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
struct virtqueue * __vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device * vdev, bool weak_barriers, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "__vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586235344,
      "name": "__vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2058",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:vring_new_virtqueue",
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586235344,
      "name": "__vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 589
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
struct virtqueue * __vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device * vdev, bool weak_barriers, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "__vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586744272,
      "name": "__vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2172",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:vring_new_virtqueue",
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586744272,
      "name": "__vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 569
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
struct virtqueue * __vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device * vdev, bool weak_barriers, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "__vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588015600,
      "name": "__vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2183",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:vring_new_virtqueue",
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588015600,
      "name": "__vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 562
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
struct virtqueue * __vring_new_virtqueue(unsigned int index, struct vring_virtqueue_split * vring_split, struct virtio_device * vdev, bool weak_barriers, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "__vring_new_virtqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__vring_new_virtqueue",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:2477",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:vring_new_virtqueue",
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589389440,
      "name": "__vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 581
    },
    {
      "addr": 18446744071596228826,
      "name": "__vring_new_virtqueue.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct virtqueue * __vring_new_virtqueue(unsigned int index, struct vring_virtqueue_split * vring_split, struct virtio_device * vdev, bool weak_barriers, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name, struct device * dma_dev)
```

```json
{
  "name": "__vring_new_virtqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__vring_new_virtqueue",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:2508",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:vring_new_virtqueue",
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589688272,
      "name": "__vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 589
    },
    {
      "addr": 18446744071596756524,
      "name": "__vring_new_virtqueue.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct virtqueue * __vring_new_virtqueue(unsigned int index, struct vring_virtqueue_split * vring_split, struct virtio_device * vdev, bool weak_barriers, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name, struct device * dma_dev)
```

```json
{
  "name": "__vring_new_virtqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__vring_new_virtqueue",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:2602",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:vring_new_virtqueue",
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590022080,
      "name": "__vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 647
    },
    {
      "addr": 18446744071597664948,
      "name": "__vring_new_virtqueue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
struct virtqueue * __vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device * vdev, bool weak_barriers, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "__vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498164776,
      "name": "__vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2053",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:vring_new_virtqueue",
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498164776,
      "name": "__vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
struct virtqueue * __vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device * vdev, bool weak_barriers, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "__vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230928768,
      "name": "__vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2053",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:vring_new_virtqueue",
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230928768,
      "name": "__vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
struct virtqueue * __vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device * vdev, bool weak_barriers, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "__vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291387520,
      "name": "__vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2053",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:vring_new_virtqueue",
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291387520,
      "name": "__vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
struct virtqueue * __vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device * vdev, bool weak_barriers, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "__vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275946634,
      "name": "__vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2053",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:vring_new_virtqueue",
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275946634,
      "name": "__vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
struct virtqueue * __vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device * vdev, bool weak_barriers, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "__vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585266000,
      "name": "__vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2053",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:vring_new_virtqueue",
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585266000,
      "name": "__vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 554
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
struct virtqueue * __vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device * vdev, bool weak_barriers, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "__vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585218288,
      "name": "__vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2053",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:vring_new_virtqueue",
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585218288,
      "name": "__vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
struct virtqueue * __vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device * vdev, bool weak_barriers, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "__vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585454320,
      "name": "__vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2053",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:vring_new_virtqueue",
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585454320,
      "name": "__vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 554
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
struct virtqueue * __vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device * vdev, bool weak_barriers, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "__vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585562496,
      "name": "__vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2053",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:vring_new_virtqueue",
        "drivers/virtio/virtio_ring.c:vring_create_virtqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585562496,
      "name": "__vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 554
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
struct virtqueue * __vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device * vdev, bool weak_barriers, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool context</code>
</li>
<li>
<b>Param reordered. </b>
<code>index, vring, vdev, weak_barriers, notify, callback, name</code> ➡️ <code>index, vring, vdev, weak_barriers, context, notify, callback, name</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vring_virtqueue_split * vring_split</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vring vring</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device * dma_dev</code>
</li>
</ul>
</details>
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
