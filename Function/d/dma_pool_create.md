# Function: <code>dma_pool_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dma_pool * dma_pool_create(const char * name, struct device * dev, size_t size, size_t align, size_t boundary)
```

```json
{
  "name": "dma_pool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580783088,
      "name": "dma_pool_create",
      "external": true,
      "loc": "mm/dmapool.c:131",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_create",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580783088,
      "name": "dma_pool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 537
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
struct dma_pool * dma_pool_create(const char * name, struct device * dev, size_t size, size_t align, size_t boundary)
```

```json
{
  "name": "dma_pool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580906400,
      "name": "dma_pool_create",
      "external": true,
      "loc": "mm/dmapool.c:131",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_create",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580906400,
      "name": "dma_pool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 558
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
struct dma_pool * dma_pool_create(const char * name, struct device * dev, size_t size, size_t align, size_t boundary)
```

```json
{
  "name": "dma_pool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580974416,
      "name": "dma_pool_create",
      "external": true,
      "loc": "mm/dmapool.c:131",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_create",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580974416,
      "name": "dma_pool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 558
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
struct dma_pool * dma_pool_create(const char * name, struct device * dev, size_t size, size_t align, size_t boundary)
```

```json
{
  "name": "dma_pool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581021312,
      "name": "dma_pool_create",
      "external": true,
      "loc": "mm/dmapool.c:131",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_create",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581021312,
      "name": "dma_pool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 507
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
struct dma_pool * dma_pool_create(const char * name, struct device * dev, size_t size, size_t align, size_t boundary)
```

```json
{
  "name": "dma_pool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581130752,
      "name": "dma_pool_create",
      "external": true,
      "loc": "mm/dmapool.c:131",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_create",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581130752,
      "name": "dma_pool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 507
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
struct dma_pool * dma_pool_create(const char * name, struct device * dev, size_t size, size_t align, size_t boundary)
```

```json
{
  "name": "dma_pool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581273680,
      "name": "dma_pool_create",
      "external": true,
      "loc": "mm/dmapool.c:131",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_create",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581273680,
      "name": "dma_pool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 513
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
struct dma_pool * dma_pool_create(const char * name, struct device * dev, size_t size, size_t align, size_t boundary)
```

```json
{
  "name": "dma_pool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581356848,
      "name": "dma_pool_create",
      "external": true,
      "loc": "mm/dmapool.c:131",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_create",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581356848,
      "name": "dma_pool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 513
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
struct dma_pool * dma_pool_create(const char * name, struct device * dev, size_t size, size_t align, size_t boundary)
```

```json
{
  "name": "dma_pool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581467392,
      "name": "dma_pool_create",
      "external": true,
      "loc": "mm/dmapool.c:130",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_create",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581467392,
      "name": "dma_pool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
struct dma_pool * dma_pool_create(const char * name, struct device * dev, size_t size, size_t align, size_t boundary)
```

```json
{
  "name": "dma_pool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581531440,
      "name": "dma_pool_create",
      "external": true,
      "loc": "mm/dmapool.c:130",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_create",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581531440,
      "name": "dma_pool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
struct dma_pool * dma_pool_create(const char * name, struct device * dev, size_t size, size_t align, size_t boundary)
```

```json
{
  "name": "dma_pool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581739408,
      "name": "dma_pool_create",
      "external": true,
      "loc": "mm/dmapool.c:130",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_create",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581739408,
      "name": "dma_pool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 507
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
struct dma_pool * dma_pool_create(const char * name, struct device * dev, size_t size, size_t align, size_t boundary)
```

```json
{
  "name": "dma_pool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581787856,
      "name": "dma_pool_create",
      "external": true,
      "loc": "mm/dmapool.c:130",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_create",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581787856,
      "name": "dma_pool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 653
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
struct dma_pool * dma_pool_create(const char * name, struct device * dev, size_t size, size_t align, size_t boundary)
```

```json
{
  "name": "dma_pool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_pool_create",
      "external": true,
      "loc": "mm/dmapool.c:131",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_create",
        "drivers/dma/lgm/lgm-dma.c:ldma_alloc_chan_resources",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591274773,
      "name": "dma_pool_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581815648,
      "name": "dma_pool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 565
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
struct dma_pool * dma_pool_create(const char * name, struct device * dev, size_t size, size_t align, size_t boundary)
```

```json
{
  "name": "dma_pool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_pool_create",
      "external": true,
      "loc": "mm/dmapool.c:130",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_create",
        "drivers/dma/lgm/lgm-dma.c:ldma_alloc_chan_resources",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592210590,
      "name": "dma_pool_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582101888,
      "name": "dma_pool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 565
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
struct dma_pool * dma_pool_create(const char * name, struct device * dev, size_t size, size_t align, size_t boundary)
```

```json
{
  "name": "dma_pool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_pool_create",
      "external": true,
      "loc": "mm/dmapool.c:130",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_create",
        "drivers/dma/lgm/lgm-dma.c:ldma_alloc_chan_resources",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593988790,
      "name": "dma_pool_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582542208,
      "name": "dma_pool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
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
struct dma_pool * dma_pool_create(const char * name, struct device * dev, size_t size, size_t align, size_t boundary)
```

```json
{
  "name": "dma_pool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583057856,
      "name": "dma_pool_create",
      "external": true,
      "loc": "mm/dmapool.c:130",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_create",
        "drivers/dma/lgm/lgm-dma.c:ldma_alloc_chan_resources",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583057856,
      "name": "dma_pool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
struct dma_pool * dma_pool_create(const char * name, struct device * dev, size_t size, size_t align, size_t boundary)
```

```json
{
  "name": "dma_pool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583269776,
      "name": "dma_pool_create",
      "external": true,
      "loc": "mm/dmapool.c:224",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_create",
        "drivers/dma/lgm/lgm-dma.c:ldma_alloc_chan_resources",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583269776,
      "name": "dma_pool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 593
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
struct dma_pool * dma_pool_create(const char * name, struct device * dev, size_t size, size_t align, size_t boundary)
```

```json
{
  "name": "dma_pool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583505664,
      "name": "dma_pool_create",
      "external": true,
      "loc": "mm/dmapool.c:224",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_create",
        "drivers/dma/lgm/lgm-dma.c:ldma_alloc_chan_resources",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583505664,
      "name": "dma_pool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
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
struct dma_pool * dma_pool_create(const char * name, struct device * dev, size_t size, size_t align, size_t boundary)
```

```json
{
  "name": "dma_pool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492960496,
      "name": "dma_pool_create",
      "external": true,
      "loc": "mm/dmapool.c:130",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_create",
        "drivers/dma/amba-pl08x.c:pl08x_probe",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_alloc_chan_resources",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492960496,
      "name": "dma_pool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
struct dma_pool * dma_pool_create(const char * name, struct device * dev, size_t size, size_t align, size_t boundary)
```

```json
{
  "name": "dma_pool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226741812,
      "name": "dma_pool_create",
      "external": true,
      "loc": "mm/dmapool.c:130",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_create",
        "drivers/dma/amba-pl08x.c:pl08x_probe",
        "drivers/dma/ti/omap-dma.c:omap_dma_probe",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226741812,
      "name": "dma_pool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
struct dma_pool * dma_pool_create(const char * name, struct device * dev, size_t size, size_t align, size_t boundary)
```

```json
{
  "name": "dma_pool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286375968,
      "name": "dma_pool_create",
      "external": true,
      "loc": "mm/dmapool.c:130",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_create",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286375968,
      "name": "dma_pool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 748
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
struct dma_pool * dma_pool_create(const char * name, struct device * dev, size_t size, size_t align, size_t boundary)
```

```json
{
  "name": "dma_pool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272872708,
      "name": "dma_pool_create",
      "external": true,
      "loc": "mm/dmapool.c:130",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_create",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272872708,
      "name": "dma_pool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
struct dma_pool * dma_pool_create(const char * name, struct device * dev, size_t size, size_t align, size_t boundary)
```

```json
{
  "name": "dma_pool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581500176,
      "name": "dma_pool_create",
      "external": true,
      "loc": "mm/dmapool.c:130",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_create",
        "drivers/nvme/host/lightnvm.c:nvme_nvm_create_dma_pool",
        "drivers/nvme/host/pci.c:nvme_probe",
        "drivers/nvme/host/pci.c:nvme_probe",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581500176,
      "name": "dma_pool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
struct dma_pool * dma_pool_create(const char * name, struct device * dev, size_t size, size_t align, size_t boundary)
```

```json
{
  "name": "dma_pool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581442400,
      "name": "dma_pool_create",
      "external": true,
      "loc": "mm/dmapool.c:130",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_create",
        "drivers/nvme/host/pci.c:nvme_probe",
        "drivers/nvme/host/pci.c:nvme_probe",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581442400,
      "name": "dma_pool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
struct dma_pool * dma_pool_create(const char * name, struct device * dev, size_t size, size_t align, size_t boundary)
```

```json
{
  "name": "dma_pool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581491488,
      "name": "dma_pool_create",
      "external": true,
      "loc": "mm/dmapool.c:130",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_create",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581491488,
      "name": "dma_pool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
struct dma_pool * dma_pool_create(const char * name, struct device * dev, size_t size, size_t align, size_t boundary)
```

```json
{
  "name": "dma_pool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581556512,
      "name": "dma_pool_create",
      "external": true,
      "loc": "mm/dmapool.c:130",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dmam_pool_create",
        "drivers/usb/core/buffer.c:hcd_buffer_create",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581556512,
      "name": "dma_pool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
