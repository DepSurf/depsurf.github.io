# Function: <code>xhci_segment_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_segment_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585476112,
      "name": "xhci_segment_alloc",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:39",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585476112,
      "name": "xhci_segment_alloc.isra.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_segment_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585874176,
      "name": "xhci_segment_alloc",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:39",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585874176,
      "name": "xhci_segment_alloc.isra.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_segment_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586063024,
      "name": "xhci_segment_alloc",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:39",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586063024,
      "name": "xhci_segment_alloc.isra.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_segment_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586145440,
      "name": "xhci_segment_alloc",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:39",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586145440,
      "name": "xhci_segment_alloc.isra.28",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_segment_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586590240,
      "name": "xhci_segment_alloc",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:28",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586590240,
      "name": "xhci_segment_alloc.isra.26",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct xhci_segment * xhci_segment_alloc(struct xhci_hcd * xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_segment_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586852720,
      "name": "xhci_segment_alloc",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:28",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586852720,
      "name": "xhci_segment_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
struct xhci_segment * xhci_segment_alloc(struct xhci_hcd * xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_segment_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587009120,
      "name": "xhci_segment_alloc",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:28",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587009120,
      "name": "xhci_segment_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
struct xhci_segment * xhci_segment_alloc(struct xhci_hcd * xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_segment_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587270624,
      "name": "xhci_segment_alloc",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:28",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587270624,
      "name": "xhci_segment_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
struct xhci_segment * xhci_segment_alloc(struct xhci_hcd * xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_segment_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587471008,
      "name": "xhci_segment_alloc",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:28",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587471008,
      "name": "xhci_segment_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
struct xhci_segment * xhci_segment_alloc(struct xhci_hcd * xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_segment_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588333872,
      "name": "xhci_segment_alloc",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:28",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588333872,
      "name": "xhci_segment_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
struct xhci_segment * xhci_segment_alloc(struct xhci_hcd * xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_segment_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588365056,
      "name": "xhci_segment_alloc",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:28",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588365056,
      "name": "xhci_segment_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
struct xhci_segment * xhci_segment_alloc(struct xhci_hcd * xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_segment_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588246992,
      "name": "xhci_segment_alloc",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:28",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588246992,
      "name": "xhci_segment_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
struct xhci_segment * xhci_segment_alloc(struct xhci_hcd * xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_segment_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588895888,
      "name": "xhci_segment_alloc",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:28",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588895888,
      "name": "xhci_segment_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
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
struct xhci_segment * xhci_segment_alloc(struct xhci_hcd * xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_segment_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590324992,
      "name": "xhci_segment_alloc",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:28",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590324992,
      "name": "xhci_segment_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
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
struct xhci_segment * xhci_segment_alloc(struct xhci_hcd * xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_segment_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591952416,
      "name": "xhci_segment_alloc",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:28",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591952416,
      "name": "xhci_segment_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
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
struct xhci_segment * xhci_segment_alloc(struct xhci_hcd * xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_segment_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592373504,
      "name": "xhci_segment_alloc",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:29",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592373504,
      "name": "xhci_segment_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
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
struct xhci_segment * xhci_segment_alloc(struct xhci_hcd * xhci, unsigned int cycle_state, unsigned int max_packet, unsigned int num, gfp_t flags)
```

```json
{
  "name": "xhci_segment_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593116144,
      "name": "xhci_segment_alloc",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:29",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593116144,
      "name": "xhci_segment_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
struct xhci_segment * xhci_segment_alloc(struct xhci_hcd * xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_segment_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500607368,
      "name": "xhci_segment_alloc",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:28",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500607368,
      "name": "xhci_segment_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
struct xhci_segment * xhci_segment_alloc(struct xhci_hcd * xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_segment_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233068320,
      "name": "xhci_segment_alloc",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:28",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233068320,
      "name": "xhci_segment_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
struct xhci_segment * xhci_segment_alloc(struct xhci_hcd * xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_segment_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294022432,
      "name": "xhci_segment_alloc",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:28",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294022432,
      "name": "xhci_segment_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
struct xhci_segment * xhci_segment_alloc(struct xhci_hcd * xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_segment_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277476680,
      "name": "xhci_segment_alloc",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:28",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277476680,
      "name": "xhci_segment_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
struct xhci_segment * xhci_segment_alloc(struct xhci_hcd * xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_segment_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587177040,
      "name": "xhci_segment_alloc",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:28",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587177040,
      "name": "xhci_segment_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
struct xhci_segment * xhci_segment_alloc(struct xhci_hcd * xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_segment_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586935792,
      "name": "xhci_segment_alloc",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:28",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586935792,
      "name": "xhci_segment_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
struct xhci_segment * xhci_segment_alloc(struct xhci_hcd * xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_segment_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587425568,
      "name": "xhci_segment_alloc",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:28",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587425568,
      "name": "xhci_segment_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
struct xhci_segment * xhci_segment_alloc(struct xhci_hcd * xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_segment_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587532432,
      "name": "xhci_segment_alloc",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:28",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587532432,
      "name": "xhci_segment_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct xhci_segment * xhci_segment_alloc(struct xhci_hcd * xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags)
```
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int num</code>
</li>
<li>
<b>Param reordered. </b>
<code>xhci, cycle_state, max_packet, flags</code> ➡️ <code>xhci, cycle_state, max_packet, num, flags</code>
</li>
</ul>
</details>
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
