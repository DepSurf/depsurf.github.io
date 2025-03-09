# Function: <code>vp_find_vqs_msix</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int vp_find_vqs_msix(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, bool per_vq_vectors)
```

```json
{
  "name": "vp_find_vqs_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584346896,
      "name": "vp_find_vqs_msix",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:268",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584346896,
      "name": "vp_find_vqs_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1100
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
int vp_find_vqs_msix(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, bool per_vq_vectors, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "vp_find_vqs_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584428176,
      "name": "vp_find_vqs_msix",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:279",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584428176,
      "name": "vp_find_vqs_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1107
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
int vp_find_vqs_msix(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, bool per_vq_vectors, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "vp_find_vqs_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584836112,
      "name": "vp_find_vqs_msix",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:279",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584836112,
      "name": "vp_find_vqs_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1112
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
int vp_find_vqs_msix(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, bool per_vq_vectors, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "vp_find_vqs_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585066640,
      "name": "vp_find_vqs_msix",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:280",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585066640,
      "name": "vp_find_vqs_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1232
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
int vp_find_vqs_msix(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, bool per_vq_vectors, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "vp_find_vqs_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585174928,
      "name": "vp_find_vqs_msix",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:280",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585174928,
      "name": "vp_find_vqs_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1235
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
int vp_find_vqs_msix(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, bool per_vq_vectors, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "vp_find_vqs_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585387536,
      "name": "vp_find_vqs_msix",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:279",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585387536,
      "name": "vp_find_vqs_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1073
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
int vp_find_vqs_msix(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, bool per_vq_vectors, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "vp_find_vqs_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585528048,
      "name": "vp_find_vqs_msix",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:279",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585528048,
      "name": "vp_find_vqs_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1088
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
int vp_find_vqs_msix(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, bool per_vq_vectors, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "vp_find_vqs_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586245664,
      "name": "vp_find_vqs_msix",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:279",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586245664,
      "name": "vp_find_vqs_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 699
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
int vp_find_vqs_msix(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, bool per_vq_vectors, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "vp_find_vqs_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586363888,
      "name": "vp_find_vqs_msix",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:279",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586363888,
      "name": "vp_find_vqs_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 699
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
int vp_find_vqs_msix(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, bool per_vq_vectors, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "vp_find_vqs_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586248576,
      "name": "vp_find_vqs_msix",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:279",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586248576,
      "name": "vp_find_vqs_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 692
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
int vp_find_vqs_msix(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, bool per_vq_vectors, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "vp_find_vqs_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vp_find_vqs_msix",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:279",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586758880,
      "name": "vp_find_vqs_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 743
    },
    {
      "addr": 18446744071592431759,
      "name": "vp_find_vqs_msix.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
int vp_find_vqs_msix(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, bool per_vq_vectors, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "vp_find_vqs_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vp_find_vqs_msix",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:278",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588035824,
      "name": "vp_find_vqs_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
    },
    {
      "addr": 18446744071594299929,
      "name": "vp_find_vqs_msix.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int vp_find_vqs_msix(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, bool per_vq_vectors, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "vp_find_vqs_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vp_find_vqs_msix",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:284",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589413792,
      "name": "vp_find_vqs_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
    },
    {
      "addr": 18446744071596229936,
      "name": "vp_find_vqs_msix.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int vp_find_vqs_msix(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, bool per_vq_vectors, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "vp_find_vqs_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vp_find_vqs_msix",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:284",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589712880,
      "name": "vp_find_vqs_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 785
    },
    {
      "addr": 18446744071596757648,
      "name": "vp_find_vqs_msix.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int vp_find_vqs_msix(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, bool per_vq_vectors, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "vp_find_vqs_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vp_find_vqs_msix",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:287",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590048672,
      "name": "vp_find_vqs_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 785
    },
    {
      "addr": 18446744071597666027,
      "name": "vp_find_vqs_msix.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int vp_find_vqs_msix(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, bool per_vq_vectors, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "vp_find_vqs_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498186272,
      "name": "vp_find_vqs_msix",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:279",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498186272,
      "name": "vp_find_vqs_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1012
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
int vp_find_vqs_msix(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, bool per_vq_vectors, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "vp_find_vqs_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230950628,
      "name": "vp_find_vqs_msix",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:279",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230950628,
      "name": "vp_find_vqs_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1060
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
int vp_find_vqs_msix(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, bool per_vq_vectors, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "vp_find_vqs_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291424032,
      "name": "vp_find_vqs_msix",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:279",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291424032,
      "name": "vp_find_vqs_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1332
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
int vp_find_vqs_msix(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, bool per_vq_vectors, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "vp_find_vqs_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275967026,
      "name": "vp_find_vqs_msix",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:279",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275967026,
      "name": "vp_find_vqs_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 948
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
int vp_find_vqs_msix(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, bool per_vq_vectors, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "vp_find_vqs_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585290080,
      "name": "vp_find_vqs_msix",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:279",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585290080,
      "name": "vp_find_vqs_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1088
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
int vp_find_vqs_msix(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, bool per_vq_vectors, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "vp_find_vqs_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585242592,
      "name": "vp_find_vqs_msix",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:279",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585242592,
      "name": "vp_find_vqs_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1088
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
int vp_find_vqs_msix(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, bool per_vq_vectors, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "vp_find_vqs_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585478448,
      "name": "vp_find_vqs_msix",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:279",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585478448,
      "name": "vp_find_vqs_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1088
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
int vp_find_vqs_msix(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, bool per_vq_vectors, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "vp_find_vqs_msix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585586624,
      "name": "vp_find_vqs_msix",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_common.c:279",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585586624,
      "name": "vp_find_vqs_msix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1088
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
int vp_find_vqs_msix(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, bool per_vq_vectors)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const bool * ctx</code>
</li>
<li>
<b>Param added. </b>
<code>struct irq_affinity * desc</code>
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
