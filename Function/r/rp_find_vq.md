# Function: <code>rp_find_vq</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rp_find_vq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588245352,
      "name": "rp_find_vq",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_virtio.c:65",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs"
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
struct virtqueue * rp_find_vq(struct virtio_device * vdev, unsigned int id, void (*)(struct virtqueue *) callback, const char * name, bool ctx)
```

```json
{
  "name": "rp_find_vq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rp_find_vq",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_virtio.c:65",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589121648,
      "name": "rp_find_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    },
    {
      "addr": 18446744071589123334,
      "name": "rp_find_vq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
struct virtqueue * rp_find_vq(struct virtio_device * vdev, unsigned int id, void (*)(struct virtqueue *) callback, const char * name, bool ctx)
```

```json
{
  "name": "rp_find_vq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rp_find_vq",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_virtio.c:65",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589119680,
      "name": "rp_find_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    },
    {
      "addr": 18446744071591620112,
      "name": "rp_find_vq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
struct virtqueue * rp_find_vq(struct virtio_device * vdev, unsigned int id, void (*)(struct virtqueue *) callback, const char * name, bool ctx)
```

```json
{
  "name": "rp_find_vq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rp_find_vq",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_virtio.c:65",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589009520,
      "name": "rp_find_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    },
    {
      "addr": 18446744071591563491,
      "name": "rp_find_vq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
struct virtqueue * rp_find_vq(struct virtio_device * vdev, unsigned int id, void (*)(struct virtqueue *) callback, const char * name, bool ctx)
```

```json
{
  "name": "rp_find_vq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rp_find_vq",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_virtio.c:65",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589724144,
      "name": "rp_find_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 471
    },
    {
      "addr": 18446744071592684242,
      "name": "rp_find_vq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
struct virtqueue * rp_find_vq(struct virtio_device * vdev, unsigned int id, void (*)(struct virtqueue *) callback, const char * name, bool ctx)
```

```json
{
  "name": "rp_find_vq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rp_find_vq",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_virtio.c:77",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591232624,
      "name": "rp_find_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
    },
    {
      "addr": 18446744071594569648,
      "name": "rp_find_vq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
struct virtqueue * rp_find_vq(struct virtio_device * vdev, unsigned int id, void (*)(struct virtqueue *) callback, const char * name, bool ctx)
```

```json
{
  "name": "rp_find_vq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592982656,
      "name": "rp_find_vq",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_virtio.c:103",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592982656,
      "name": "rp_find_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
struct virtqueue * rp_find_vq(struct virtio_device * vdev, unsigned int id, void (*)(struct virtqueue *) callback, const char * name, bool ctx)
```

```json
{
  "name": "rp_find_vq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593433664,
      "name": "rp_find_vq",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_virtio.c:103",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593433664,
      "name": "rp_find_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 523
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
struct virtqueue * rp_find_vq(struct virtio_device * vdev, unsigned int id, void (*)(struct virtqueue *) callback, const char * name, bool ctx)
```

```json
{
  "name": "rp_find_vq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594179712,
      "name": "rp_find_vq",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_virtio.c:103",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594179712,
      "name": "rp_find_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 523
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
  "name": "rp_find_vq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501703148,
      "name": "rp_find_vq",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_virtio.c:65",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs"
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
  "name": "rp_find_vq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234227476,
      "name": "rp_find_vq",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_virtio.c:65",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs"
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
  "name": "rp_find_vq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295141320,
      "name": "rp_find_vq",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_virtio.c:65",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rp_find_vq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587857048,
      "name": "rp_find_vq",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_virtio.c:65",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs"
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rp_find_vq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588317688,
      "name": "rp_find_vq",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_virtio.c:65",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs"
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
struct virtqueue * rp_find_vq(struct virtio_device * vdev, unsigned int id, void (*)(struct virtqueue *) callback, const char * name, bool ctx)
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
