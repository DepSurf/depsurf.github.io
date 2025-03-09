# Function: <code>vp_setup_vq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vp_setup_vq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583837112,
      "name": "vp_setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:225",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_try_to_find_vqs"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vp_setup_vq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584166189,
      "name": "vp_setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:225",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_try_to_find_vqs"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct virtqueue * vp_setup_vq(struct virtio_device * vdev, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, u16 msix_vec)
```

```json
{
  "name": "vp_setup_vq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584345296,
      "name": "vp_setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:170",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584345296,
      "name": "vp_setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
struct virtqueue * vp_setup_vq(struct virtio_device * vdev, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "vp_setup_vq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584426576,
      "name": "vp_setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:176",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584426576,
      "name": "vp_setup_vq",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct virtqueue * vp_setup_vq(struct virtio_device * vdev, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "vp_setup_vq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584834480,
      "name": "vp_setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:176",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584834480,
      "name": "vp_setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
struct virtqueue * vp_setup_vq(struct virtio_device * vdev, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "vp_setup_vq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585064784,
      "name": "vp_setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:177",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585064784,
      "name": "vp_setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
struct virtqueue * vp_setup_vq(struct virtio_device * vdev, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "vp_setup_vq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585173072,
      "name": "vp_setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:177",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585173072,
      "name": "vp_setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
struct virtqueue * vp_setup_vq(struct virtio_device * vdev, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "vp_setup_vq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585385648,
      "name": "vp_setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:174",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585385648,
      "name": "vp_setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
struct virtqueue * vp_setup_vq(struct virtio_device * vdev, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "vp_setup_vq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585526160,
      "name": "vp_setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:174",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585526160,
      "name": "vp_setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
struct virtqueue * vp_setup_vq(struct virtio_device * vdev, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "vp_setup_vq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586243200,
      "name": "vp_setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:174",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_intx",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586243200,
      "name": "vp_setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
struct virtqueue * vp_setup_vq(struct virtio_device * vdev, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "vp_setup_vq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586361424,
      "name": "vp_setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:174",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_intx",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586361424,
      "name": "vp_setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
struct virtqueue * vp_setup_vq(struct virtio_device * vdev, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "vp_setup_vq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586246096,
      "name": "vp_setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:174",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586246096,
      "name": "vp_setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
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
struct virtqueue * vp_setup_vq(struct virtio_device * vdev, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "vp_setup_vq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586756352,
      "name": "vp_setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:174",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586756352,
      "name": "vp_setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
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
struct virtqueue * vp_setup_vq(struct virtio_device * vdev, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "vp_setup_vq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588033136,
      "name": "vp_setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:174",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588033136,
      "name": "vp_setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
struct virtqueue * vp_setup_vq(struct virtio_device * vdev, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "vp_setup_vq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589410896,
      "name": "vp_setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:174",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589410896,
      "name": "vp_setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
struct virtqueue * vp_setup_vq(struct virtio_device * vdev, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "vp_setup_vq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589710000,
      "name": "vp_setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:174",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589710000,
      "name": "vp_setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
struct virtqueue * vp_setup_vq(struct virtio_device * vdev, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "vp_setup_vq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590045280,
      "name": "vp_setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:174",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590045280,
      "name": "vp_setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
struct virtqueue * vp_setup_vq(struct virtio_device * vdev, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "vp_setup_vq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498184832,
      "name": "vp_setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:174",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498184832,
      "name": "vp_setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
struct virtqueue * vp_setup_vq(struct virtio_device * vdev, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "vp_setup_vq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230948964,
      "name": "vp_setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:174",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230948964,
      "name": "vp_setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
struct virtqueue * vp_setup_vq(struct virtio_device * vdev, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "vp_setup_vq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291421088,
      "name": "vp_setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:174",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291421088,
      "name": "vp_setup_vq",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct virtqueue * vp_setup_vq(struct virtio_device * vdev, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "vp_setup_vq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275965356,
      "name": "vp_setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:174",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275965356,
      "name": "vp_setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
struct virtqueue * vp_setup_vq(struct virtio_device * vdev, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "vp_setup_vq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585288192,
      "name": "vp_setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:174",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585288192,
      "name": "vp_setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
struct virtqueue * vp_setup_vq(struct virtio_device * vdev, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "vp_setup_vq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585240704,
      "name": "vp_setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:174",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585240704,
      "name": "vp_setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
struct virtqueue * vp_setup_vq(struct virtio_device * vdev, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "vp_setup_vq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585476560,
      "name": "vp_setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:174",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585476560,
      "name": "vp_setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
struct virtqueue * vp_setup_vq(struct virtio_device * vdev, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "vp_setup_vq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585584736,
      "name": "vp_setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:174",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585584736,
      "name": "vp_setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
struct virtqueue * vp_setup_vq(struct virtio_device * vdev, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, u16 msix_vec)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool ctx</code>
</li>
<li>
<b>Param reordered. </b>
<code>vdev, index, callback, name, msix_vec</code> ➡️ <code>vdev, index, callback, name, ctx, msix_vec</code>
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
