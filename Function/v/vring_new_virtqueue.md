# Function: <code>vring_new_virtqueue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct virtqueue * vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, void * pages, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583822848,
      "name": "vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:723",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583822848,
      "name": "vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 407
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct virtqueue * vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, void * pages, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584151472,
      "name": "vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1073",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584151472,
      "name": "vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct virtqueue * vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, void * pages, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584332128,
      "name": "vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1077",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584332128,
      "name": "vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct virtqueue * vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool context, void * pages, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584412320,
      "name": "vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1123",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584412320,
      "name": "vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct virtqueue * vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool context, void * pages, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584819808,
      "name": "vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1122",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584819808,
      "name": "vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct virtqueue * vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool context, void * pages, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585050272,
      "name": "vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1121",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585050272,
      "name": "vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct virtqueue * vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool context, void * pages, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585160560,
      "name": "vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2151",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585160560,
      "name": "vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
struct virtqueue * vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool context, void * pages, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585365744,
      "name": "vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2157",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585365744,
      "name": "vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
struct virtqueue * vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool context, void * pages, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585504480,
      "name": "vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2156",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585504480,
      "name": "vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
struct virtqueue * vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool context, void * pages, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586230928,
      "name": "vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2159",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_virtio.c:rp_find_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586230928,
      "name": "vring_new_virtqueue",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct virtqueue * vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool context, void * pages, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586349296,
      "name": "vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2159",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_virtio.c:rp_find_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586349296,
      "name": "vring_new_virtqueue",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct virtqueue * vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool context, void * pages, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586235936,
      "name": "vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2163",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_virtio.c:rp_find_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586235936,
      "name": "vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
struct virtqueue * vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool context, void * pages, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586744848,
      "name": "vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2283",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_virtio.c:rp_find_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586744848,
      "name": "vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
struct virtqueue * vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool context, void * pages, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588016176,
      "name": "vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2298",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_virtio.c:rp_find_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588016176,
      "name": "vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct virtqueue * vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool context, void * pages, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589390048,
      "name": "vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2630",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_virtio.c:rp_find_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589390048,
      "name": "vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct virtqueue * vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool context, void * pages, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589688880,
      "name": "vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2688",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_virtio.c:rp_find_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589688880,
      "name": "vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
struct virtqueue * vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool context, void * pages, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590022752,
      "name": "vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2849",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_virtio.c:rp_find_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590022752,
      "name": "vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
struct virtqueue * vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool context, void * pages, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498165232,
      "name": "vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2156",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498165232,
      "name": "vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
struct virtqueue * vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool context, void * pages, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230929296,
      "name": "vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2156",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230929296,
      "name": "vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct virtqueue * vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool context, void * pages, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291388176,
      "name": "vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2156",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291388176,
      "name": "vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
struct virtqueue * vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool context, void * pages, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275947038,
      "name": "vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2156",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275947038,
      "name": "vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
struct virtqueue * vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool context, void * pages, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585266560,
      "name": "vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2156",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585266560,
      "name": "vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
struct virtqueue * vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool context, void * pages, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585218832,
      "name": "vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2156",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585218832,
      "name": "vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
struct virtqueue * vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool context, void * pages, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585454880,
      "name": "vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2156",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585454880,
      "name": "vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
struct virtqueue * vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool context, void * pages, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_new_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585563056,
      "name": "vring_new_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2156",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585563056,
      "name": "vring_new_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
<code>index, num, vring_align, vdev, weak_barriers, pages, notify, callback, name</code> ➡️ <code>index, num, vring_align, vdev, weak_barriers, context, pages, notify, callback, name</code>
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
