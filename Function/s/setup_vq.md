# Function: <code>setup_vq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
struct virtqueue * setup_vq(struct virtio_pci_device * vp_dev, struct virtio_pci_vq_info * info, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, u16 msix_vec)
```

```json
{
  "name": "setup_vq",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583831776,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_modern.c:315",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583838672,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_legacy.c:114",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583831776,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1095
    },
    {
      "addr": 18446744071583838672,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
struct virtqueue * setup_vq(struct virtio_pci_device * vp_dev, struct virtio_pci_vq_info * info, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, u16 msix_vec)
```

```json
{
  "name": "setup_vq",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584160944,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_modern.c:295",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584167696,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_legacy.c:114",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584160944,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 747
    },
    {
      "addr": 18446744071584167696,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
struct virtqueue * setup_vq(struct virtio_pci_device * vp_dev, struct virtio_pci_vq_info * info, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, u16 msix_vec)
```

```json
{
  "name": "setup_vq",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584342080,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_modern.c:295",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584348976,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_legacy.c:114",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584342080,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 747
    },
    {
      "addr": 18446744071584348976,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
struct virtqueue * setup_vq(struct virtio_pci_device * vp_dev, struct virtio_pci_vq_info * info, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "setup_vq",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584423312,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_modern.c:295",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584430336,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_legacy.c:114",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584423312,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 724
    },
    {
      "addr": 18446744071584430336,
      "name": "setup_vq",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
struct virtqueue * setup_vq(struct virtio_pci_device * vp_dev, struct virtio_pci_vq_info * info, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "setup_vq",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584831104,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_modern.c:295",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584838272,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_legacy.c:114",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584831104,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 724
    },
    {
      "addr": 18446744071584838272,
      "name": "setup_vq",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
struct virtqueue * setup_vq(struct virtio_pci_device * vp_dev, struct virtio_pci_vq_info * info, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "setup_vq",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585061488,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_modern.c:309",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585068928,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_legacy.c:114",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585061488,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 738
    },
    {
      "addr": 18446744071585068928,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
struct virtqueue * setup_vq(struct virtio_pci_device * vp_dev, struct virtio_pci_vq_info * info, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "setup_vq",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585170256,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_modern.c:309",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585177248,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_legacy.c:116",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585170256,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 738
    },
    {
      "addr": 18446744071585177248,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
struct virtqueue * setup_vq(struct virtio_pci_device * vp_dev, struct virtio_pci_vq_info * info, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "setup_vq",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_modern.c:306",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_legacy.c:113",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585382656,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
    },
    {
      "addr": 18446744071585385334,
      "name": "setup_vq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071585389696,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071585390735,
      "name": "setup_vq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
struct virtqueue * setup_vq(struct virtio_pci_device * vp_dev, struct virtio_pci_vq_info * info, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "setup_vq",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_modern.c:306",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_legacy.c:113",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585523120,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
    },
    {
      "addr": 18446744071585525846,
      "name": "setup_vq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071585530208,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071585531247,
      "name": "setup_vq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
struct virtqueue * setup_vq(struct virtio_pci_device * vp_dev, struct virtio_pci_vq_info * info, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "setup_vq",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_modern.c:307",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_legacy.c:113",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586240336,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
    },
    {
      "addr": 18446744071586242868,
      "name": "setup_vq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071586247504,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071586248545,
      "name": "setup_vq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
struct virtqueue * setup_vq(struct virtio_pci_device * vp_dev, struct virtio_pci_vq_info * info, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "setup_vq",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_modern.c:307",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_legacy.c:113",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586358880,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
    },
    {
      "addr": 18446744071591446756,
      "name": "setup_vq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071586365728,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071591446864,
      "name": "setup_vq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
struct virtqueue * setup_vq(struct virtio_pci_device * vp_dev, struct virtio_pci_vq_info * info, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "setup_vq",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_modern.c:184",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_legacy.c:113",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586244016,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
    },
    {
      "addr": 18446744071591388340,
      "name": "setup_vq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071586250352,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
    },
    {
      "addr": 18446744071591388473,
      "name": "setup_vq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
struct virtqueue * setup_vq(struct virtio_pci_device * vp_dev, struct virtio_pci_vq_info * info, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "setup_vq",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_modern.c:184",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_legacy.c:113",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586754112,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
    },
    {
      "addr": 18446744071592431584,
      "name": "setup_vq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071586760784,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
    },
    {
      "addr": 18446744071592431966,
      "name": "setup_vq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
struct virtqueue * setup_vq(struct virtio_pci_device * vp_dev, struct virtio_pci_vq_info * info, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "setup_vq",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_modern.c:184",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_legacy.c:110",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588030464,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
    },
    {
      "addr": 18446744071594299711,
      "name": "setup_vq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071588037760,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
    },
    {
      "addr": 18446744071594300107,
      "name": "setup_vq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
struct virtqueue * setup_vq(struct virtio_pci_device * vp_dev, struct virtio_pci_vq_info * info, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "setup_vq",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589407344,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_modern.c:291",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589415856,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_legacy.c:110",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589407344,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
    },
    {
      "addr": 18446744071589415856,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
struct virtqueue * setup_vq(struct virtio_pci_device * vp_dev, struct virtio_pci_vq_info * info, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "setup_vq",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589706480,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_modern.c:300",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589715040,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_legacy.c:110",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589706480,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
    },
    {
      "addr": 18446744071589715040,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision ❓</summary>

```c
struct virtqueue * setup_vq(struct virtio_pci_device * vp_dev, struct virtio_pci_vq_info * info, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "setup_vq",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590042784,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_modern.c:530",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590050896,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_legacy.c:110",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590042784,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
    },
    {
      "addr": 18446744071590050896,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
struct virtqueue * setup_vq(struct virtio_pci_device * vp_dev, struct virtio_pci_vq_info * info, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "setup_vq",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498181672,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_modern.c:306",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498189064,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_legacy.c:113",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498181672,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 712
    },
    {
      "addr": 18446603336498189064,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
struct virtqueue * setup_vq(struct virtio_pci_device * vp_dev, struct virtio_pci_vq_info * info, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "setup_vq",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230946348,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_modern.c:306",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230952828,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_legacy.c:113",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230946348,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 720
    },
    {
      "addr": 3230952828,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision ❓</summary>

```c
struct virtqueue * setup_vq(struct virtio_pci_device * vp_dev, struct virtio_pci_vq_info * info, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "setup_vq",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291417504,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_modern.c:306",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055291427088,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_legacy.c:113",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291417504,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 932
    },
    {
      "addr": 13835058055291427088,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision ❓</summary>

```c
struct virtqueue * setup_vq(struct virtio_pci_device * vp_dev, struct virtio_pci_vq_info * info, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "setup_vq",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275962954,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_modern.c:306",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275969334,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_legacy.c:113",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275962954,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 636
    },
    {
      "addr": 18446743936275969334,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Transformation ❓</summary>

```c
struct virtqueue * setup_vq(struct virtio_pci_device * vp_dev, struct virtio_pci_vq_info * info, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "setup_vq",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_modern.c:306",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_legacy.c:113",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585285200,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
    },
    {
      "addr": 18446744071585287878,
      "name": "setup_vq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071585292240,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071585293279,
      "name": "setup_vq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Transformation ❓</summary>

```c
struct virtqueue * setup_vq(struct virtio_pci_device * vp_dev, struct virtio_pci_vq_info * info, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "setup_vq",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_modern.c:306",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_legacy.c:113",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585237664,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
    },
    {
      "addr": 18446744071585240390,
      "name": "setup_vq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071585244752,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071585245791,
      "name": "setup_vq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Transformation ❓</summary>

```c
struct virtqueue * setup_vq(struct virtio_pci_device * vp_dev, struct virtio_pci_vq_info * info, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "setup_vq",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_modern.c:306",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_legacy.c:113",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585473520,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
    },
    {
      "addr": 18446744071585476246,
      "name": "setup_vq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071585480608,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071585481647,
      "name": "setup_vq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Transformation ❓</summary>

```c
struct virtqueue * setup_vq(struct virtio_pci_device * vp_dev, struct virtio_pci_vq_info * info, unsigned int index, void (*)(struct virtqueue *) callback, const char * name, bool ctx, u16 msix_vec)
```

```json
{
  "name": "setup_vq",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_modern.c:306",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "setup_vq",
      "external": false,
      "loc": "drivers/virtio/virtio_pci_legacy.c:113",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585581696,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
    },
    {
      "addr": 18446744071585584422,
      "name": "setup_vq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071585588784,
      "name": "setup_vq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071585589823,
      "name": "setup_vq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
<code>bool ctx</code>
</li>
<li>
<b>Param reordered. </b>
<code>vp_dev, info, index, callback, name, msix_vec</code> ➡️ <code>vp_dev, info, index, callback, name, ctx, msix_vec</code>
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
