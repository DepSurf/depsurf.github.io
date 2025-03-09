# Function: <code>rproc_virtio_find_vqs</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int rproc_virtio_find_vqs(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "rproc_virtio_find_vqs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_virtio_find_vqs",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_virtio.c:143",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588244880,
      "name": "rproc_virtio_find_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 723
    },
    {
      "addr": 18446744071588246422,
      "name": "rproc_virtio_find_vqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int rproc_virtio_find_vqs(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "rproc_virtio_find_vqs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589122096,
      "name": "rproc_virtio_find_vqs",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_virtio.c:143",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589122096,
      "name": "rproc_virtio_find_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
int rproc_virtio_find_vqs(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "rproc_virtio_find_vqs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589120128,
      "name": "rproc_virtio_find_vqs",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_virtio.c:143",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589120128,
      "name": "rproc_virtio_find_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
int rproc_virtio_find_vqs(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "rproc_virtio_find_vqs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589009968,
      "name": "rproc_virtio_find_vqs",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_virtio.c:143",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589009968,
      "name": "rproc_virtio_find_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
int rproc_virtio_find_vqs(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "rproc_virtio_find_vqs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_virtio_find_vqs",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_virtio.c:143",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589724848,
      "name": "rproc_virtio_find_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071592684325,
      "name": "rproc_virtio_find_vqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
int rproc_virtio_find_vqs(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "rproc_virtio_find_vqs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_virtio_find_vqs",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_virtio.c:155",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591233408,
      "name": "rproc_virtio_find_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
    },
    {
      "addr": 18446744071594569730,
      "name": "rproc_virtio_find_vqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int rproc_virtio_find_vqs(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "rproc_virtio_find_vqs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_virtio_find_vqs",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_virtio.c:183",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592983200,
      "name": "rproc_virtio_find_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
    },
    {
      "addr": 18446744071596319549,
      "name": "rproc_virtio_find_vqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int rproc_virtio_find_vqs(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "rproc_virtio_find_vqs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_virtio_find_vqs",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_virtio.c:183",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593434208,
      "name": "rproc_virtio_find_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
    },
    {
      "addr": 18446744071596849212,
      "name": "rproc_virtio_find_vqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int rproc_virtio_find_vqs(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "rproc_virtio_find_vqs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_virtio_find_vqs",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_virtio.c:183",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594180256,
      "name": "rproc_virtio_find_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
    },
    {
      "addr": 18446744071597773923,
      "name": "rproc_virtio_find_vqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int rproc_virtio_find_vqs(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "rproc_virtio_find_vqs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501702664,
      "name": "rproc_virtio_find_vqs",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_virtio.c:143",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501702664,
      "name": "rproc_virtio_find_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 792
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
int rproc_virtio_find_vqs(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "rproc_virtio_find_vqs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234226972,
      "name": "rproc_virtio_find_vqs",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_virtio.c:143",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234226972,
      "name": "rproc_virtio_find_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
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
int rproc_virtio_find_vqs(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "rproc_virtio_find_vqs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295140752,
      "name": "rproc_virtio_find_vqs",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_virtio.c:143",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295140752,
      "name": "rproc_virtio_find_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1028
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int rproc_virtio_find_vqs(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "rproc_virtio_find_vqs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_virtio_find_vqs",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_virtio.c:143",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587856576,
      "name": "rproc_virtio_find_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 723
    },
    {
      "addr": 18446744071587858118,
      "name": "rproc_virtio_find_vqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int rproc_virtio_find_vqs(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, const bool * ctx, struct irq_affinity * desc)
```

```json
{
  "name": "rproc_virtio_find_vqs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_virtio_find_vqs",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_virtio.c:143",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588317216,
      "name": "rproc_virtio_find_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 723
    },
    {
      "addr": 18446744071588318758,
      "name": "rproc_virtio_find_vqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int rproc_virtio_find_vqs(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, const bool * ctx, struct irq_affinity * desc)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int rproc_virtio_find_vqs(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, const bool * ctx, struct irq_affinity * desc)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int rproc_virtio_find_vqs(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, const bool * ctx, struct irq_affinity * desc)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
int rproc_virtio_find_vqs(struct virtio_device * vdev, unsigned int nvqs, struct virtqueue * * vqs, vq_callback_t * * callbacks, const const char * * names, const bool * ctx, struct irq_affinity * desc)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
