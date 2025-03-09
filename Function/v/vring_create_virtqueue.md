# Function: <code>vring_create_virtqueue</code>

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
struct virtqueue * vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_create_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584151584,
      "name": "vring_create_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1011",
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
      "addr": 18446744071584151584,
      "name": "vring_create_virtqueue",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct virtqueue * vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_create_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584332240,
      "name": "vring_create_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1015",
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
      "addr": 18446744071584332240,
      "name": "vring_create_virtqueue",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct virtqueue * vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_create_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584412416,
      "name": "vring_create_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1060",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584412416,
      "name": "vring_create_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
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
struct virtqueue * vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_create_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584819904,
      "name": "vring_create_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1059",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584819904,
      "name": "vring_create_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct virtqueue * vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_create_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585050368,
      "name": "vring_create_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1058",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585050368,
      "name": "vring_create_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 530
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
struct virtqueue * vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_create_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585160672,
      "name": "vring_create_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2126",
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
      "addr": 18446744071585160672,
      "name": "vring_create_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1285
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
struct virtqueue * vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_create_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vring_create_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2132",
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
      "addr": 18446744071585377426,
      "name": "vring_create_virtqueue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071585365856,
      "name": "vring_create_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
struct virtqueue * vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_create_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vring_create_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2131",
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
      "addr": 18446744071585517906,
      "name": "vring_create_virtqueue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071585504592,
      "name": "vring_create_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
struct virtqueue * vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_create_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586234896,
      "name": "vring_create_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2134",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_mmio.c:vm_setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586234896,
      "name": "vring_create_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct virtqueue * vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_create_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586353248,
      "name": "vring_create_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2134",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_mmio.c:vm_setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586353248,
      "name": "vring_create_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct virtqueue * vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_create_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586237504,
      "name": "vring_create_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2138",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_mmio.c:vm_setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586237504,
      "name": "vring_create_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct virtqueue * vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_create_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586746368,
      "name": "vring_create_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2258",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_mmio.c:vm_setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586746368,
      "name": "vring_create_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct virtqueue * vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_create_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588020752,
      "name": "vring_create_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2273",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_mmio.c:vm_setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588020752,
      "name": "vring_create_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
struct virtqueue * vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_create_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589391152,
      "name": "vring_create_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2536",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_mmio.c:vm_setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589391152,
      "name": "vring_create_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
struct virtqueue * vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_create_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589690512,
      "name": "vring_create_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2569",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_mmio.c:vm_setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589690512,
      "name": "vring_create_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
struct virtqueue * vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_create_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590023312,
      "name": "vring_create_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2665",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_mmio.c:vm_setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590023312,
      "name": "vring_create_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
struct virtqueue * vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_create_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498168456,
      "name": "vring_create_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2131",
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
      "addr": 18446603336498168456,
      "name": "vring_create_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
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
struct virtqueue * vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_create_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230930256,
      "name": "vring_create_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2131",
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
      "addr": 3230930256,
      "name": "vring_create_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 632
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
struct virtqueue * vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_create_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291388352,
      "name": "vring_create_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2131",
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
      "addr": 13835058055291388352,
      "name": "vring_create_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 932
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
struct virtqueue * vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_create_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275947852,
      "name": "vring_create_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2131",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_mmio.c:vm_setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275947852,
      "name": "vring_create_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
struct virtqueue * vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_create_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vring_create_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2131",
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
      "addr": 18446744071585279986,
      "name": "vring_create_virtqueue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071585266672,
      "name": "vring_create_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
struct virtqueue * vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_create_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vring_create_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2131",
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
      "addr": 18446744071585232450,
      "name": "vring_create_virtqueue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071585218944,
      "name": "vring_create_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
struct virtqueue * vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_create_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vring_create_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2131",
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
      "addr": 18446744071585468306,
      "name": "vring_create_virtqueue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071585454992,
      "name": "vring_create_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
struct virtqueue * vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
```

```json
{
  "name": "vring_create_virtqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vring_create_virtqueue",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2131",
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
      "addr": 18446744071585576482,
      "name": "vring_create_virtqueue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071585563168,
      "name": "vring_create_virtqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
struct virtqueue * vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device * vdev, bool weak_barriers, bool may_reduce_num, bool (*)(struct virtqueue *) notify, void (*)(struct virtqueue *) callback, const char * name)
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
<code>index, num, vring_align, vdev, weak_barriers, may_reduce_num, notify, callback, name</code> ➡️ <code>index, num, vring_align, vdev, weak_barriers, may_reduce_num, context, notify, callback, name</code>
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
