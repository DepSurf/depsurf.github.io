# Function: <code>hcd_alloc_coherent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hcd_alloc_coherent(struct usb_bus * bus, gfp_t mem_flags, dma_addr_t * dma_handle, void * * vaddr_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "hcd_alloc_coherent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585188560,
      "name": "hcd_alloc_coherent",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:1386",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585188560,
      "name": "hcd_alloc_coherent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
int hcd_alloc_coherent(struct usb_bus * bus, gfp_t mem_flags, dma_addr_t * dma_handle, void * * vaddr_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "hcd_alloc_coherent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585580624,
      "name": "hcd_alloc_coherent",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:1378",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585580624,
      "name": "hcd_alloc_coherent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
int hcd_alloc_coherent(struct usb_bus * bus, gfp_t mem_flags, dma_addr_t * dma_handle, void * * vaddr_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "hcd_alloc_coherent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585768272,
      "name": "hcd_alloc_coherent",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:1379",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585768272,
      "name": "hcd_alloc_coherent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
int hcd_alloc_coherent(struct usb_bus * bus, gfp_t mem_flags, dma_addr_t * dma_handle, void * * vaddr_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "hcd_alloc_coherent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585853920,
      "name": "hcd_alloc_coherent",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:1382",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585853920,
      "name": "hcd_alloc_coherent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int hcd_alloc_coherent(struct usb_bus * bus, gfp_t mem_flags, dma_addr_t * dma_handle, void * * vaddr_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "hcd_alloc_coherent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586293712,
      "name": "hcd_alloc_coherent",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:1371",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586293712,
      "name": "hcd_alloc_coherent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
int hcd_alloc_coherent(struct usb_bus * bus, gfp_t mem_flags, dma_addr_t * dma_handle, void * * vaddr_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "hcd_alloc_coherent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586551040,
      "name": "hcd_alloc_coherent",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:1373",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586551040,
      "name": "hcd_alloc_coherent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
int hcd_alloc_coherent(struct usb_bus * bus, gfp_t mem_flags, dma_addr_t * dma_handle, void * * vaddr_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "hcd_alloc_coherent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586699888,
      "name": "hcd_alloc_coherent",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:1371",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586699888,
      "name": "hcd_alloc_coherent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hcd_alloc_coherent(struct usb_bus * bus, gfp_t mem_flags, dma_addr_t * dma_handle, void * * vaddr_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "hcd_alloc_coherent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586955424,
      "name": "hcd_alloc_coherent",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:1273",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586955424,
      "name": "hcd_alloc_coherent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hcd_alloc_coherent(struct usb_bus * bus, gfp_t mem_flags, dma_addr_t * dma_handle, void * * vaddr_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "hcd_alloc_coherent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587154128,
      "name": "hcd_alloc_coherent",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:1270",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587154128,
      "name": "hcd_alloc_coherent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int hcd_alloc_coherent(struct usb_bus * bus, gfp_t mem_flags, dma_addr_t * dma_handle, void * * vaddr_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "hcd_alloc_coherent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588003008,
      "name": "hcd_alloc_coherent",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:1271",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588003008,
      "name": "hcd_alloc_coherent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int hcd_alloc_coherent(struct usb_bus * bus, gfp_t mem_flags, dma_addr_t * dma_handle, void * * vaddr_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "hcd_alloc_coherent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588055680,
      "name": "hcd_alloc_coherent",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:1272",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588055680,
      "name": "hcd_alloc_coherent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int hcd_alloc_coherent(struct usb_bus * bus, gfp_t mem_flags, dma_addr_t * dma_handle, void * * vaddr_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "hcd_alloc_coherent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587938496,
      "name": "hcd_alloc_coherent",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:1272",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587938496,
      "name": "hcd_alloc_coherent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int hcd_alloc_coherent(struct usb_bus * bus, gfp_t mem_flags, dma_addr_t * dma_handle, void * * vaddr_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "hcd_alloc_coherent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588548880,
      "name": "hcd_alloc_coherent",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:1279",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588548880,
      "name": "hcd_alloc_coherent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int hcd_alloc_coherent(struct usb_bus * bus, gfp_t mem_flags, dma_addr_t * dma_handle, void * * vaddr_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "hcd_alloc_coherent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589959072,
      "name": "hcd_alloc_coherent",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:1279",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589959072,
      "name": "hcd_alloc_coherent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
int hcd_alloc_coherent(struct usb_bus * bus, gfp_t mem_flags, dma_addr_t * dma_handle, void * * vaddr_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "hcd_alloc_coherent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591549408,
      "name": "hcd_alloc_coherent",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:1280",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591549408,
      "name": "hcd_alloc_coherent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
int hcd_alloc_coherent(struct usb_bus * bus, gfp_t mem_flags, dma_addr_t * dma_handle, void * * vaddr_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "hcd_alloc_coherent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591971024,
      "name": "hcd_alloc_coherent",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:1284",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591971024,
      "name": "hcd_alloc_coherent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
int hcd_alloc_coherent(struct usb_bus * bus, gfp_t mem_flags, dma_addr_t * dma_handle, void * * vaddr_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "hcd_alloc_coherent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592710864,
      "name": "hcd_alloc_coherent",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:1259",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592710864,
      "name": "hcd_alloc_coherent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
int hcd_alloc_coherent(struct usb_bus * bus, gfp_t mem_flags, dma_addr_t * dma_handle, void * * vaddr_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "hcd_alloc_coherent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500230696,
      "name": "hcd_alloc_coherent",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:1270",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500230696,
      "name": "hcd_alloc_coherent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
int hcd_alloc_coherent(struct usb_bus * bus, gfp_t mem_flags, dma_addr_t * dma_handle, void * * vaddr_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "hcd_alloc_coherent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232709068,
      "name": "hcd_alloc_coherent",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:1270",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232709068,
      "name": "hcd_alloc_coherent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int hcd_alloc_coherent(struct usb_bus * bus, gfp_t mem_flags, dma_addr_t * dma_handle, void * * vaddr_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "hcd_alloc_coherent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293521600,
      "name": "hcd_alloc_coherent",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:1270",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293521600,
      "name": "hcd_alloc_coherent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "hcd_alloc_coherent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277156856,
      "name": "hcd_alloc_coherent",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:1270",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277151640,
      "name": "hcd_alloc_coherent.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int hcd_alloc_coherent(struct usb_bus * bus, gfp_t mem_flags, dma_addr_t * dma_handle, void * * vaddr_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "hcd_alloc_coherent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586860208,
      "name": "hcd_alloc_coherent",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:1270",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586860208,
      "name": "hcd_alloc_coherent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int hcd_alloc_coherent(struct usb_bus * bus, gfp_t mem_flags, dma_addr_t * dma_handle, void * * vaddr_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "hcd_alloc_coherent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586801600,
      "name": "hcd_alloc_coherent",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:1270",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586801600,
      "name": "hcd_alloc_coherent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int hcd_alloc_coherent(struct usb_bus * bus, gfp_t mem_flags, dma_addr_t * dma_handle, void * * vaddr_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "hcd_alloc_coherent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587108688,
      "name": "hcd_alloc_coherent",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:1270",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587108688,
      "name": "hcd_alloc_coherent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int hcd_alloc_coherent(struct usb_bus * bus, gfp_t mem_flags, dma_addr_t * dma_handle, void * * vaddr_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "hcd_alloc_coherent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587216192,
      "name": "hcd_alloc_coherent",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:1270",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587216192,
      "name": "hcd_alloc_coherent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int hcd_alloc_coherent(struct usb_bus * bus, gfp_t mem_flags, dma_addr_t * dma_handle, void * * vaddr_handle, size_t size, enum dma_data_direction dir)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
