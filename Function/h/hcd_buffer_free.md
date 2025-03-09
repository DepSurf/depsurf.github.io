# Function: <code>hcd_buffer_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void hcd_buffer_free(struct usb_bus * bus, size_t size, void * addr, dma_addr_t dma)
```

```json
{
  "name": "hcd_buffer_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585233424,
      "name": "hcd_buffer_free",
      "external": true,
      "loc": "drivers/usb/core/buffer.c:135",
      "file": "drivers/usb/core/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_free_coherent",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585233424,
      "name": "hcd_buffer_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
void hcd_buffer_free(struct usb_bus * bus, size_t size, void * addr, dma_addr_t dma)
```

```json
{
  "name": "hcd_buffer_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585626848,
      "name": "hcd_buffer_free",
      "external": true,
      "loc": "drivers/usb/core/buffer.c:143",
      "file": "drivers/usb/core/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_free_coherent",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585626848,
      "name": "hcd_buffer_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
void hcd_buffer_free(struct usb_bus * bus, size_t size, void * addr, dma_addr_t dma)
```

```json
{
  "name": "hcd_buffer_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585814464,
      "name": "hcd_buffer_free",
      "external": true,
      "loc": "drivers/usb/core/buffer.c:146",
      "file": "drivers/usb/core/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_free_coherent",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585814464,
      "name": "hcd_buffer_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
void hcd_buffer_free(struct usb_bus * bus, size_t size, void * addr, dma_addr_t dma)
```

```json
{
  "name": "hcd_buffer_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585901392,
      "name": "hcd_buffer_free",
      "external": true,
      "loc": "drivers/usb/core/buffer.c:146",
      "file": "drivers/usb/core/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_free_coherent",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585901392,
      "name": "hcd_buffer_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
void hcd_buffer_free(struct usb_bus * bus, size_t size, void * addr, dma_addr_t dma)
```

```json
{
  "name": "hcd_buffer_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586342160,
      "name": "hcd_buffer_free",
      "external": true,
      "loc": "drivers/usb/core/buffer.c:146",
      "file": "drivers/usb/core/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_free_coherent",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586342160,
      "name": "hcd_buffer_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
void hcd_buffer_free(struct usb_bus * bus, size_t size, void * addr, dma_addr_t dma)
```

```json
{
  "name": "hcd_buffer_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586599696,
      "name": "hcd_buffer_free",
      "external": true,
      "loc": "drivers/usb/core/buffer.c:146",
      "file": "drivers/usb/core/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_free_coherent",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586599696,
      "name": "hcd_buffer_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void hcd_buffer_free(struct usb_bus * bus, size_t size, void * addr, dma_addr_t dma)
```

```json
{
  "name": "hcd_buffer_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586748624,
      "name": "hcd_buffer_free",
      "external": true,
      "loc": "drivers/usb/core/buffer.c:142",
      "file": "drivers/usb/core/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_free_coherent",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586748624,
      "name": "hcd_buffer_free",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void hcd_buffer_free(struct usb_bus * bus, size_t size, void * addr, dma_addr_t dma)
```

```json
{
  "name": "hcd_buffer_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587003664,
      "name": "hcd_buffer_free",
      "external": true,
      "loc": "drivers/usb/core/buffer.c:142",
      "file": "drivers/usb/core/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_free_coherent",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587003664,
      "name": "hcd_buffer_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void hcd_buffer_free(struct usb_bus * bus, size_t size, void * addr, dma_addr_t dma)
```

```json
{
  "name": "hcd_buffer_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587203136,
      "name": "hcd_buffer_free",
      "external": true,
      "loc": "drivers/usb/core/buffer.c:142",
      "file": "drivers/usb/core/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_free_coherent",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587203136,
      "name": "hcd_buffer_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void hcd_buffer_free(struct usb_bus * bus, size_t size, void * addr, dma_addr_t dma)
```

```json
{
  "name": "hcd_buffer_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588055456,
      "name": "hcd_buffer_free",
      "external": true,
      "loc": "drivers/usb/core/buffer.c:142",
      "file": "drivers/usb/core/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_free_coherent",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588055456,
      "name": "hcd_buffer_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void hcd_buffer_free(struct usb_bus * bus, size_t size, void * addr, dma_addr_t dma)
```

```json
{
  "name": "hcd_buffer_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588100848,
      "name": "hcd_buffer_free",
      "external": true,
      "loc": "drivers/usb/core/buffer.c:144",
      "file": "drivers/usb/core/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_free_coherent",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588100848,
      "name": "hcd_buffer_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void hcd_buffer_free(struct usb_bus * bus, size_t size, void * addr, dma_addr_t dma)
```

```json
{
  "name": "hcd_buffer_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587983440,
      "name": "hcd_buffer_free",
      "external": true,
      "loc": "drivers/usb/core/buffer.c:144",
      "file": "drivers/usb/core/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_free_coherent",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587983440,
      "name": "hcd_buffer_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void hcd_buffer_free(struct usb_bus * bus, size_t size, void * addr, dma_addr_t dma)
```

```json
{
  "name": "hcd_buffer_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588596528,
      "name": "hcd_buffer_free",
      "external": true,
      "loc": "drivers/usb/core/buffer.c:144",
      "file": "drivers/usb/core/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_free_coherent",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588596528,
      "name": "hcd_buffer_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void hcd_buffer_free(struct usb_bus * bus, size_t size, void * addr, dma_addr_t dma)
```

```json
{
  "name": "hcd_buffer_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590008576,
      "name": "hcd_buffer_free",
      "external": true,
      "loc": "drivers/usb/core/buffer.c:144",
      "file": "drivers/usb/core/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_free_coherent",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590008576,
      "name": "hcd_buffer_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
void hcd_buffer_free(struct usb_bus * bus, size_t size, void * addr, dma_addr_t dma)
```

```json
{
  "name": "hcd_buffer_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591608688,
      "name": "hcd_buffer_free",
      "external": true,
      "loc": "drivers/usb/core/buffer.c:144",
      "file": "drivers/usb/core/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_free_coherent",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591608688,
      "name": "hcd_buffer_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
void hcd_buffer_free(struct usb_bus * bus, size_t size, void * addr, dma_addr_t dma)
```

```json
{
  "name": "hcd_buffer_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592030464,
      "name": "hcd_buffer_free",
      "external": true,
      "loc": "drivers/usb/core/buffer.c:144",
      "file": "drivers/usb/core/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_free_coherent",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592030464,
      "name": "hcd_buffer_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
void hcd_buffer_free(struct usb_bus * bus, size_t size, void * addr, dma_addr_t dma)
```

```json
{
  "name": "hcd_buffer_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592770480,
      "name": "hcd_buffer_free",
      "external": true,
      "loc": "drivers/usb/core/buffer.c:144",
      "file": "drivers/usb/core/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_free_coherent",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592770480,
      "name": "hcd_buffer_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
void hcd_buffer_free(struct usb_bus * bus, size_t size, void * addr, dma_addr_t dma)
```

```json
{
  "name": "hcd_buffer_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500286920,
      "name": "hcd_buffer_free",
      "external": true,
      "loc": "drivers/usb/core/buffer.c:142",
      "file": "drivers/usb/core/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_free_coherent",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500286920,
      "name": "hcd_buffer_free",
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
void hcd_buffer_free(struct usb_bus * bus, size_t size, void * addr, dma_addr_t dma)
```

```json
{
  "name": "hcd_buffer_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232757044,
      "name": "hcd_buffer_free",
      "external": true,
      "loc": "drivers/usb/core/buffer.c:142",
      "file": "drivers/usb/core/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_free_coherent",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232757044,
      "name": "hcd_buffer_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void hcd_buffer_free(struct usb_bus * bus, size_t size, void * addr, dma_addr_t dma)
```

```json
{
  "name": "hcd_buffer_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293590304,
      "name": "hcd_buffer_free",
      "external": true,
      "loc": "drivers/usb/core/buffer.c:142",
      "file": "drivers/usb/core/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_free_coherent",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293590304,
      "name": "hcd_buffer_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
void hcd_buffer_free(struct usb_bus * bus, size_t size, void * addr, dma_addr_t dma)
```

```json
{
  "name": "hcd_buffer_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277196774,
      "name": "hcd_buffer_free",
      "external": true,
      "loc": "drivers/usb/core/buffer.c:142",
      "file": "drivers/usb/core/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_free_coherent",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277196774,
      "name": "hcd_buffer_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void hcd_buffer_free(struct usb_bus * bus, size_t size, void * addr, dma_addr_t dma)
```

```json
{
  "name": "hcd_buffer_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586909216,
      "name": "hcd_buffer_free",
      "external": true,
      "loc": "drivers/usb/core/buffer.c:142",
      "file": "drivers/usb/core/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_free_coherent",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586909216,
      "name": "hcd_buffer_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void hcd_buffer_free(struct usb_bus * bus, size_t size, void * addr, dma_addr_t dma)
```

```json
{
  "name": "hcd_buffer_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586850384,
      "name": "hcd_buffer_free",
      "external": true,
      "loc": "drivers/usb/core/buffer.c:142",
      "file": "drivers/usb/core/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_free_coherent",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586850384,
      "name": "hcd_buffer_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void hcd_buffer_free(struct usb_bus * bus, size_t size, void * addr, dma_addr_t dma)
```

```json
{
  "name": "hcd_buffer_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587157696,
      "name": "hcd_buffer_free",
      "external": true,
      "loc": "drivers/usb/core/buffer.c:142",
      "file": "drivers/usb/core/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_free_coherent",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587157696,
      "name": "hcd_buffer_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void hcd_buffer_free(struct usb_bus * bus, size_t size, void * addr, dma_addr_t dma)
```

```json
{
  "name": "hcd_buffer_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587264768,
      "name": "hcd_buffer_free",
      "external": true,
      "loc": "drivers/usb/core/buffer.c:142",
      "file": "drivers/usb/core/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_free_coherent",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587264768,
      "name": "hcd_buffer_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
