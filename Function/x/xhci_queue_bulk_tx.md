# Function: <code>xhci_queue_bulk_tx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int xhci_queue_bulk_tx(struct xhci_hcd * xhci, gfp_t mem_flags, struct urb * urb, int slot_id, unsigned int ep_index)
```

```json
{
  "name": "xhci_queue_bulk_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585498592,
      "name": "xhci_queue_bulk_tx",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3255",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585498592,
      "name": "xhci_queue_bulk_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2368
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
int xhci_queue_bulk_tx(struct xhci_hcd * xhci, gfp_t mem_flags, struct urb * urb, int slot_id, unsigned int ep_index)
```

```json
{
  "name": "xhci_queue_bulk_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585894384,
      "name": "xhci_queue_bulk_tx",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3192",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585894384,
      "name": "xhci_queue_bulk_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2293
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
int xhci_queue_bulk_tx(struct xhci_hcd * xhci, gfp_t mem_flags, struct urb * urb, int slot_id, unsigned int ep_index)
```

```json
{
  "name": "xhci_queue_bulk_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586083440,
      "name": "xhci_queue_bulk_tx",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3093",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586083440,
      "name": "xhci_queue_bulk_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2281
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
int xhci_queue_bulk_tx(struct xhci_hcd * xhci, gfp_t mem_flags, struct urb * urb, int slot_id, unsigned int ep_index)
```

```json
{
  "name": "xhci_queue_bulk_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586165536,
      "name": "xhci_queue_bulk_tx",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3193",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586165536,
      "name": "xhci_queue_bulk_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2423
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
int xhci_queue_bulk_tx(struct xhci_hcd * xhci, gfp_t mem_flags, struct urb * urb, int slot_id, unsigned int ep_index)
```

```json
{
  "name": "xhci_queue_bulk_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586610832,
      "name": "xhci_queue_bulk_tx",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3197",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586610832,
      "name": "xhci_queue_bulk_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2417
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
int xhci_queue_bulk_tx(struct xhci_hcd * xhci, gfp_t mem_flags, struct urb * urb, int slot_id, unsigned int ep_index)
```

```json
{
  "name": "xhci_queue_bulk_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586877808,
      "name": "xhci_queue_bulk_tx",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3116",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586877808,
      "name": "xhci_queue_bulk_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2362
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
int xhci_queue_bulk_tx(struct xhci_hcd * xhci, gfp_t mem_flags, struct urb * urb, int slot_id, unsigned int ep_index)
```

```json
{
  "name": "xhci_queue_bulk_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587033312,
      "name": "xhci_queue_bulk_tx",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3180",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587033312,
      "name": "xhci_queue_bulk_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2432
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
int xhci_queue_bulk_tx(struct xhci_hcd * xhci, gfp_t mem_flags, struct urb * urb, int slot_id, unsigned int ep_index)
```

```json
{
  "name": "xhci_queue_bulk_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_queue_bulk_tx",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3231",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587312847,
      "name": "xhci_queue_bulk_tx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071587296416,
      "name": "xhci_queue_bulk_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2658
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
int xhci_queue_bulk_tx(struct xhci_hcd * xhci, gfp_t mem_flags, struct urb * urb, int slot_id, unsigned int ep_index)
```

```json
{
  "name": "xhci_queue_bulk_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_queue_bulk_tx",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3258",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587514105,
      "name": "xhci_queue_bulk_tx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071587497392,
      "name": "xhci_queue_bulk_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2884
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int xhci_queue_bulk_tx(struct xhci_hcd * xhci, gfp_t mem_flags, struct urb * urb, int slot_id, unsigned int ep_index)
```

```json
{
  "name": "xhci_queue_bulk_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_queue_bulk_tx",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3304",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588377728,
      "name": "xhci_queue_bulk_tx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071588368112,
      "name": "xhci_queue_bulk_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1452
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
int xhci_queue_bulk_tx(struct xhci_hcd * xhci, gfp_t mem_flags, struct urb * urb, int slot_id, unsigned int ep_index)
```

```json
{
  "name": "xhci_queue_bulk_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_queue_bulk_tx",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3318",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591568275,
      "name": "xhci_queue_bulk_tx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071588398272,
      "name": "xhci_queue_bulk_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1477
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
int xhci_queue_bulk_tx(struct xhci_hcd * xhci, gfp_t mem_flags, struct urb * urb, int slot_id, unsigned int ep_index)
```

```json
{
  "name": "xhci_queue_bulk_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_queue_bulk_tx",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3507",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591511798,
      "name": "xhci_queue_bulk_tx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071588284608,
      "name": "xhci_queue_bulk_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1573
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
int xhci_queue_bulk_tx(struct xhci_hcd * xhci, gfp_t mem_flags, struct urb * urb, int slot_id, unsigned int ep_index)
```

```json
{
  "name": "xhci_queue_bulk_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_queue_bulk_tx",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3577",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592613998,
      "name": "xhci_queue_bulk_tx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071588937824,
      "name": "xhci_queue_bulk_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1669
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
int xhci_queue_bulk_tx(struct xhci_hcd * xhci, gfp_t mem_flags, struct urb * urb, int slot_id, unsigned int ep_index)
```

```json
{
  "name": "xhci_queue_bulk_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_queue_bulk_tx",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3512",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594497204,
      "name": "xhci_queue_bulk_tx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071590369056,
      "name": "xhci_queue_bulk_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1844
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
int xhci_queue_bulk_tx(struct xhci_hcd * xhci, gfp_t mem_flags, struct urb * urb, int slot_id, unsigned int ep_index)
```

```json
{
  "name": "xhci_queue_bulk_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592002624,
      "name": "xhci_queue_bulk_tx",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3519",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592002624,
      "name": "xhci_queue_bulk_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1949
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
int xhci_queue_bulk_tx(struct xhci_hcd * xhci, gfp_t mem_flags, struct urb * urb, int slot_id, unsigned int ep_index)
```

```json
{
  "name": "xhci_queue_bulk_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592423376,
      "name": "xhci_queue_bulk_tx",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3539",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592423376,
      "name": "xhci_queue_bulk_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1936
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
int xhci_queue_bulk_tx(struct xhci_hcd * xhci, gfp_t mem_flags, struct urb * urb, int slot_id, unsigned int ep_index)
```

```json
{
  "name": "xhci_queue_bulk_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593167120,
      "name": "xhci_queue_bulk_tx",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3582",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593167120,
      "name": "xhci_queue_bulk_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1936
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
int xhci_queue_bulk_tx(struct xhci_hcd * xhci, gfp_t mem_flags, struct urb * urb, int slot_id, unsigned int ep_index)
```

```json
{
  "name": "xhci_queue_bulk_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500638584,
      "name": "xhci_queue_bulk_tx",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3258",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500638584,
      "name": "xhci_queue_bulk_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2724
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
int xhci_queue_bulk_tx(struct xhci_hcd * xhci, gfp_t mem_flags, struct urb * urb, int slot_id, unsigned int ep_index)
```

```json
{
  "name": "xhci_queue_bulk_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233097468,
      "name": "xhci_queue_bulk_tx",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3258",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233097468,
      "name": "xhci_queue_bulk_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2888
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
int xhci_queue_bulk_tx(struct xhci_hcd * xhci, gfp_t mem_flags, struct urb * urb, int slot_id, unsigned int ep_index)
```

```json
{
  "name": "xhci_queue_bulk_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294058336,
      "name": "xhci_queue_bulk_tx",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3258",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294058336,
      "name": "xhci_queue_bulk_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3036
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
int xhci_queue_bulk_tx(struct xhci_hcd * xhci, gfp_t mem_flags, struct urb * urb, int slot_id, unsigned int ep_index)
```

```json
{
  "name": "xhci_queue_bulk_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277503714,
      "name": "xhci_queue_bulk_tx",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3258",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277503714,
      "name": "xhci_queue_bulk_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2374
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
int xhci_queue_bulk_tx(struct xhci_hcd * xhci, gfp_t mem_flags, struct urb * urb, int slot_id, unsigned int ep_index)
```

```json
{
  "name": "xhci_queue_bulk_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_queue_bulk_tx",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3258",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587220137,
      "name": "xhci_queue_bulk_tx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071587203424,
      "name": "xhci_queue_bulk_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2884
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
int xhci_queue_bulk_tx(struct xhci_hcd * xhci, gfp_t mem_flags, struct urb * urb, int slot_id, unsigned int ep_index)
```

```json
{
  "name": "xhci_queue_bulk_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_queue_bulk_tx",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3258",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586978889,
      "name": "xhci_queue_bulk_tx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071586962176,
      "name": "xhci_queue_bulk_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2884
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
int xhci_queue_bulk_tx(struct xhci_hcd * xhci, gfp_t mem_flags, struct urb * urb, int slot_id, unsigned int ep_index)
```

```json
{
  "name": "xhci_queue_bulk_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_queue_bulk_tx",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3258",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587468665,
      "name": "xhci_queue_bulk_tx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071587451952,
      "name": "xhci_queue_bulk_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2884
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
int xhci_queue_bulk_tx(struct xhci_hcd * xhci, gfp_t mem_flags, struct urb * urb, int slot_id, unsigned int ep_index)
```

```json
{
  "name": "xhci_queue_bulk_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_queue_bulk_tx",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3258",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587576268,
      "name": "xhci_queue_bulk_tx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071587559248,
      "name": "xhci_queue_bulk_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2931
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
