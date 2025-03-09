# Function: <code>dma_pool_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dma_pool_destroy(struct dma_pool * pool)
```

```json
{
  "name": "dma_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580784640,
      "name": "dma_pool_destroy",
      "external": true,
      "loc": "mm/dmapool.c:270",
      "file": "mm/dmapool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_release",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580784640,
      "name": "dma_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dma_pool_destroy(struct dma_pool * pool)
```

```json
{
  "name": "dma_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580907984,
      "name": "dma_pool_destroy",
      "external": true,
      "loc": "mm/dmapool.c:270",
      "file": "mm/dmapool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_release",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580907984,
      "name": "dma_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dma_pool_destroy(struct dma_pool * pool)
```

```json
{
  "name": "dma_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580976000,
      "name": "dma_pool_destroy",
      "external": true,
      "loc": "mm/dmapool.c:270",
      "file": "mm/dmapool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_release",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580976000,
      "name": "dma_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
void dma_pool_destroy(struct dma_pool * pool)
```

```json
{
  "name": "dma_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581022816,
      "name": "dma_pool_destroy",
      "external": true,
      "loc": "mm/dmapool.c:270",
      "file": "mm/dmapool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_release",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581022816,
      "name": "dma_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
void dma_pool_destroy(struct dma_pool * pool)
```

```json
{
  "name": "dma_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581132272,
      "name": "dma_pool_destroy",
      "external": true,
      "loc": "mm/dmapool.c:270",
      "file": "mm/dmapool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_release",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581132272,
      "name": "dma_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dma_pool_destroy(struct dma_pool * pool)
```

```json
{
  "name": "dma_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_pool_destroy",
      "external": true,
      "loc": "mm/dmapool.c:270",
      "file": "mm/dmapool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_release",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581275677,
      "name": "dma_pool_destroy.cold.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581275232,
      "name": "dma_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dma_pool_destroy(struct dma_pool * pool)
```

```json
{
  "name": "dma_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581358370,
      "name": "dma_pool_destroy",
      "external": true,
      "loc": "mm/dmapool.c:270",
      "file": "mm/dmapool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_release",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581358631,
      "name": "dma_pool_destroy.cold.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581358192,
      "name": "dma_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dma_pool_destroy(struct dma_pool * pool)
```

```json
{
  "name": "dma_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581468970,
      "name": "dma_pool_destroy",
      "external": true,
      "loc": "mm/dmapool.c:269",
      "file": "mm/dmapool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_release",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581469249,
      "name": "dma_pool_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071581468800,
      "name": "dma_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dma_pool_destroy(struct dma_pool * pool)
```

```json
{
  "name": "dma_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581533018,
      "name": "dma_pool_destroy",
      "external": true,
      "loc": "mm/dmapool.c:269",
      "file": "mm/dmapool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_release",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581533297,
      "name": "dma_pool_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071581532848,
      "name": "dma_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
void dma_pool_destroy(struct dma_pool * pool)
```

```json
{
  "name": "dma_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_pool_destroy",
      "external": true,
      "loc": "mm/dmapool.c:267",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_release",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:release_uhci",
        "drivers/usb/host/uhci-hcd.c:release_uhci",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581741255,
      "name": "dma_pool_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071581740864,
      "name": "dma_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
void dma_pool_destroy(struct dma_pool * pool)
```

```json
{
  "name": "dma_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_pool_destroy",
      "external": true,
      "loc": "mm/dmapool.c:267",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_release",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:release_uhci",
        "drivers/usb/host/uhci-hcd.c:release_uhci",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591332194,
      "name": "dma_pool_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071581789440,
      "name": "dma_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
void dma_pool_destroy(struct dma_pool * pool)
```

```json
{
  "name": "dma_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_pool_destroy",
      "external": true,
      "loc": "mm/dmapool.c:268",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_release",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591274865,
      "name": "dma_pool_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071581817120,
      "name": "dma_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
void dma_pool_destroy(struct dma_pool * pool)
```

```json
{
  "name": "dma_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_pool_destroy",
      "external": true,
      "loc": "mm/dmapool.c:267",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_release",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592210682,
      "name": "dma_pool_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071582103408,
      "name": "dma_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
void dma_pool_destroy(struct dma_pool * pool)
```

```json
{
  "name": "dma_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_pool_destroy",
      "external": true,
      "loc": "mm/dmapool.c:267",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_release",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593988882,
      "name": "dma_pool_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071582543776,
      "name": "dma_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
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
void dma_pool_destroy(struct dma_pool * pool)
```

```json
{
  "name": "dma_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583059632,
      "name": "dma_pool_destroy",
      "external": true,
      "loc": "mm/dmapool.c:267",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_release",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583059632,
      "name": "dma_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 415
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
void dma_pool_destroy(struct dma_pool * pool)
```

```json
{
  "name": "dma_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583268624,
      "name": "dma_pool_destroy",
      "external": true,
      "loc": "mm/dmapool.c:360",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_release",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583268624,
      "name": "dma_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
void dma_pool_destroy(struct dma_pool * pool)
```

```json
{
  "name": "dma_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583504496,
      "name": "dma_pool_destroy",
      "external": true,
      "loc": "mm/dmapool.c:360",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_release",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583504496,
      "name": "dma_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void dma_pool_destroy(struct dma_pool * pool)
```

```json
{
  "name": "dma_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492961192,
      "name": "dma_pool_destroy",
      "external": true,
      "loc": "mm/dmapool.c:269",
      "file": "mm/dmapool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_release",
        "drivers/dma/amba-pl08x.c:pl08x_probe",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492961192,
      "name": "dma_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void dma_pool_destroy(struct dma_pool * pool)
```

```json
{
  "name": "dma_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226743216,
      "name": "dma_pool_destroy",
      "external": true,
      "loc": "mm/dmapool.c:269",
      "file": "mm/dmapool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_release",
        "drivers/dma/amba-pl08x.c:pl08x_probe",
        "drivers/dma/ti/omap-dma.c:omap_dma_remove",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226743216,
      "name": "dma_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void dma_pool_destroy(struct dma_pool * pool)
```

```json
{
  "name": "dma_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286378176,
      "name": "dma_pool_destroy",
      "external": true,
      "loc": "mm/dmapool.c:269",
      "file": "mm/dmapool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_release",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286378176,
      "name": "dma_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void dma_pool_destroy(struct dma_pool * pool)
```

```json
{
  "name": "dma_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272873994,
      "name": "dma_pool_destroy",
      "external": true,
      "loc": "mm/dmapool.c:269",
      "file": "mm/dmapool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_release",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272873994,
      "name": "dma_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dma_pool_destroy(struct dma_pool * pool)
```

```json
{
  "name": "dma_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581501754,
      "name": "dma_pool_destroy",
      "external": true,
      "loc": "mm/dmapool.c:269",
      "file": "mm/dmapool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_release",
        "drivers/nvme/host/lightnvm.c:nvme_nvm_destroy_dma_pool",
        "drivers/nvme/host/pci.c:nvme_remove",
        "drivers/nvme/host/pci.c:nvme_remove",
        "drivers/nvme/host/pci.c:nvme_probe",
        "drivers/nvme/host/pci.c:nvme_probe",
        "drivers/nvme/host/pci.c:nvme_probe",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581502033,
      "name": "dma_pool_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071581501584,
      "name": "dma_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dma_pool_destroy(struct dma_pool * pool)
```

```json
{
  "name": "dma_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581443978,
      "name": "dma_pool_destroy",
      "external": true,
      "loc": "mm/dmapool.c:269",
      "file": "mm/dmapool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_release",
        "drivers/nvme/host/pci.c:nvme_remove",
        "drivers/nvme/host/pci.c:nvme_remove",
        "drivers/nvme/host/pci.c:nvme_probe",
        "drivers/nvme/host/pci.c:nvme_probe",
        "drivers/nvme/host/pci.c:nvme_probe",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581444257,
      "name": "dma_pool_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071581443808,
      "name": "dma_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dma_pool_destroy(struct dma_pool * pool)
```

```json
{
  "name": "dma_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581493066,
      "name": "dma_pool_destroy",
      "external": true,
      "loc": "mm/dmapool.c:269",
      "file": "mm/dmapool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_release",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581493345,
      "name": "dma_pool_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071581492896,
      "name": "dma_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dma_pool_destroy(struct dma_pool * pool)
```

```json
{
  "name": "dma_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581558074,
      "name": "dma_pool_destroy",
      "external": true,
      "loc": "mm/dmapool.c:269",
      "file": "mm/dmapool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_release",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581558353,
      "name": "dma_pool_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071581557904,
      "name": "dma_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
