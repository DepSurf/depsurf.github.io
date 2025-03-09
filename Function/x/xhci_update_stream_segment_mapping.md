# Function: <code>xhci_update_stream_segment_mapping</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int xhci_update_stream_segment_mapping(struct radix_tree_root * trb_address_map, struct xhci_ring * ring, struct xhci_segment * first_seg, struct xhci_segment * last_seg, gfp_t mem_flags)
```

```json
{
  "name": "xhci_update_stream_segment_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585475760,
      "name": "xhci_update_stream_segment_mapping",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:215",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585475760,
      "name": "xhci_update_stream_segment_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int xhci_update_stream_segment_mapping(struct radix_tree_root * trb_address_map, struct xhci_ring * ring, struct xhci_segment * first_seg, struct xhci_segment * last_seg, gfp_t mem_flags)
```

```json
{
  "name": "xhci_update_stream_segment_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585871408,
      "name": "xhci_update_stream_segment_mapping",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:225",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585871408,
      "name": "xhci_update_stream_segment_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
int xhci_update_stream_segment_mapping(struct radix_tree_root * trb_address_map, struct xhci_ring * ring, struct xhci_segment * first_seg, struct xhci_segment * last_seg, gfp_t mem_flags)
```

```json
{
  "name": "xhci_update_stream_segment_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586060256,
      "name": "xhci_update_stream_segment_mapping",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:225",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586060256,
      "name": "xhci_update_stream_segment_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
int xhci_update_stream_segment_mapping(struct radix_tree_root * trb_address_map, struct xhci_ring * ring, struct xhci_segment * first_seg, struct xhci_segment * last_seg, gfp_t mem_flags)
```

```json
{
  "name": "xhci_update_stream_segment_mapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586142160,
      "name": "xhci_update_stream_segment_mapping",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:225",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586142160,
      "name": "xhci_update_stream_segment_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int xhci_update_stream_segment_mapping(struct radix_tree_root * trb_address_map, struct xhci_ring * ring, struct xhci_segment * first_seg, struct xhci_segment * last_seg, gfp_t mem_flags)
```

```json
{
  "name": "xhci_update_stream_segment_mapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586587104,
      "name": "xhci_update_stream_segment_mapping",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:214",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586587104,
      "name": "xhci_update_stream_segment_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int xhci_update_stream_segment_mapping(struct radix_tree_root * trb_address_map, struct xhci_ring * ring, struct xhci_segment * first_seg, struct xhci_segment * last_seg, gfp_t mem_flags)
```

```json
{
  "name": "xhci_update_stream_segment_mapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586851744,
      "name": "xhci_update_stream_segment_mapping",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:216",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586851744,
      "name": "xhci_update_stream_segment_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int xhci_update_stream_segment_mapping(struct xarray * trb_address_map, struct xhci_ring * ring, struct xhci_segment * first_seg, struct xhci_segment * last_seg, gfp_t mem_flags)
```

```json
{
  "name": "xhci_update_stream_segment_mapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587008144,
      "name": "xhci_update_stream_segment_mapping",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:216",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587008144,
      "name": "xhci_update_stream_segment_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
int xhci_update_stream_segment_mapping(struct xarray * trb_address_map, struct xhci_ring * ring, struct xhci_segment * first_seg, struct xhci_segment * last_seg, gfp_t mem_flags)
```

```json
{
  "name": "xhci_update_stream_segment_mapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587269696,
      "name": "xhci_update_stream_segment_mapping",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:216",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587269696,
      "name": "xhci_update_stream_segment_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
int xhci_update_stream_segment_mapping(struct xarray * trb_address_map, struct xhci_ring * ring, struct xhci_segment * first_seg, struct xhci_segment * last_seg, gfp_t mem_flags)
```

```json
{
  "name": "xhci_update_stream_segment_mapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587470080,
      "name": "xhci_update_stream_segment_mapping",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:216",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587470080,
      "name": "xhci_update_stream_segment_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int xhci_update_stream_segment_mapping(struct xarray * trb_address_map, struct xhci_ring * ring, struct xhci_segment * first_seg, struct xhci_segment * last_seg, gfp_t mem_flags)
```

```json
{
  "name": "xhci_update_stream_segment_mapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588332784,
      "name": "xhci_update_stream_segment_mapping",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:216",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588332784,
      "name": "xhci_update_stream_segment_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int xhci_update_stream_segment_mapping(struct xarray * trb_address_map, struct xhci_ring * ring, struct xhci_segment * first_seg, struct xhci_segment * last_seg, gfp_t mem_flags)
```

```json
{
  "name": "xhci_update_stream_segment_mapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588364032,
      "name": "xhci_update_stream_segment_mapping",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:219",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588364032,
      "name": "xhci_update_stream_segment_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int xhci_update_stream_segment_mapping(struct xarray * trb_address_map, struct xhci_ring * ring, struct xhci_segment * first_seg, struct xhci_segment * last_seg, gfp_t mem_flags)
```

```json
{
  "name": "xhci_update_stream_segment_mapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588246560,
      "name": "xhci_update_stream_segment_mapping",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:219",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588246560,
      "name": "xhci_update_stream_segment_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_update_stream_segment_mapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588908705,
      "name": "xhci_update_stream_segment_mapping",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:219",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588895152,
      "name": "xhci_update_stream_segment_mapping.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
int xhci_update_stream_segment_mapping(struct xarray * trb_address_map, struct xhci_ring * ring, struct xhci_segment * first_seg, struct xhci_segment * last_seg, gfp_t mem_flags)
```

```json
{
  "name": "xhci_update_stream_segment_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590323984,
      "name": "xhci_update_stream_segment_mapping",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:219",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590323984,
      "name": "xhci_update_stream_segment_mapping",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int xhci_update_stream_segment_mapping(struct xarray * trb_address_map, struct xhci_ring * ring, struct xhci_segment * first_seg, struct xhci_segment * last_seg, gfp_t mem_flags)
```

```json
{
  "name": "xhci_update_stream_segment_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591951328,
      "name": "xhci_update_stream_segment_mapping",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:219",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591951328,
      "name": "xhci_update_stream_segment_mapping",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int xhci_update_stream_segment_mapping(struct xarray * trb_address_map, struct xhci_ring * ring, struct xhci_segment * first_seg, struct xhci_segment * last_seg, gfp_t mem_flags)
```

```json
{
  "name": "xhci_update_stream_segment_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592372416,
      "name": "xhci_update_stream_segment_mapping",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:219",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592372416,
      "name": "xhci_update_stream_segment_mapping",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int xhci_update_stream_segment_mapping(struct xarray * trb_address_map, struct xhci_ring * ring, struct xhci_segment * first_seg, struct xhci_segment * last_seg, gfp_t mem_flags)
```

```json
{
  "name": "xhci_update_stream_segment_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593114400,
      "name": "xhci_update_stream_segment_mapping",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:226",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593114400,
      "name": "xhci_update_stream_segment_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
int xhci_update_stream_segment_mapping(struct xarray * trb_address_map, struct xhci_ring * ring, struct xhci_segment * first_seg, struct xhci_segment * last_seg, gfp_t mem_flags)
```

```json
{
  "name": "xhci_update_stream_segment_mapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500606328,
      "name": "xhci_update_stream_segment_mapping",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:216",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500606328,
      "name": "xhci_update_stream_segment_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int xhci_update_stream_segment_mapping(struct xarray * trb_address_map, struct xhci_ring * ring, struct xhci_segment * first_seg, struct xhci_segment * last_seg, gfp_t mem_flags)
```

```json
{
  "name": "xhci_update_stream_segment_mapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233067432,
      "name": "xhci_update_stream_segment_mapping",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:216",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233067432,
      "name": "xhci_update_stream_segment_mapping",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int xhci_update_stream_segment_mapping(struct xarray * trb_address_map, struct xhci_ring * ring, struct xhci_segment * first_seg, struct xhci_segment * last_seg, gfp_t mem_flags)
```

```json
{
  "name": "xhci_update_stream_segment_mapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294017376,
      "name": "xhci_update_stream_segment_mapping",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:216",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294017376,
      "name": "xhci_update_stream_segment_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
int xhci_update_stream_segment_mapping(struct xarray * trb_address_map, struct xhci_ring * ring, struct xhci_segment * first_seg, struct xhci_segment * last_seg, gfp_t mem_flags)
```

```json
{
  "name": "xhci_update_stream_segment_mapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277475620,
      "name": "xhci_update_stream_segment_mapping",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:216",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277475620,
      "name": "xhci_update_stream_segment_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int xhci_update_stream_segment_mapping(struct xarray * trb_address_map, struct xhci_ring * ring, struct xhci_segment * first_seg, struct xhci_segment * last_seg, gfp_t mem_flags)
```

```json
{
  "name": "xhci_update_stream_segment_mapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587176112,
      "name": "xhci_update_stream_segment_mapping",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:216",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587176112,
      "name": "xhci_update_stream_segment_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
int xhci_update_stream_segment_mapping(struct xarray * trb_address_map, struct xhci_ring * ring, struct xhci_segment * first_seg, struct xhci_segment * last_seg, gfp_t mem_flags)
```

```json
{
  "name": "xhci_update_stream_segment_mapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586934864,
      "name": "xhci_update_stream_segment_mapping",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:216",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586934864,
      "name": "xhci_update_stream_segment_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
int xhci_update_stream_segment_mapping(struct xarray * trb_address_map, struct xhci_ring * ring, struct xhci_segment * first_seg, struct xhci_segment * last_seg, gfp_t mem_flags)
```

```json
{
  "name": "xhci_update_stream_segment_mapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587424640,
      "name": "xhci_update_stream_segment_mapping",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:216",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587424640,
      "name": "xhci_update_stream_segment_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
int xhci_update_stream_segment_mapping(struct xarray * trb_address_map, struct xhci_ring * ring, struct xhci_segment * first_seg, struct xhci_segment * last_seg, gfp_t mem_flags)
```

```json
{
  "name": "xhci_update_stream_segment_mapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587531472,
      "name": "xhci_update_stream_segment_mapping",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:216",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587531472,
      "name": "xhci_update_stream_segment_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct radix_tree_root * trb_address_map</code> ➡️ <code>struct xarray * trb_address_map</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int xhci_update_stream_segment_mapping(struct xarray * trb_address_map, struct xhci_ring * ring, struct xhci_segment * first_seg, struct xhci_segment * last_seg, gfp_t mem_flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int xhci_update_stream_segment_mapping(struct xarray * trb_address_map, struct xhci_ring * ring, struct xhci_segment * first_seg, struct xhci_segment * last_seg, gfp_t mem_flags)
```
</details>
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
