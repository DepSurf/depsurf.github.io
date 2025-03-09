# Function: <code>prepare_ring</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int prepare_ring(struct xhci_hcd * xhci, struct xhci_ring * ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags)
```

```json
{
  "name": "prepare_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585492640,
      "name": "prepare_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2804",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585492640,
      "name": "prepare_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
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
int prepare_ring(struct xhci_hcd * xhci, struct xhci_ring * ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags)
```

```json
{
  "name": "prepare_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585887840,
      "name": "prepare_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2834",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:prepare_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585887840,
      "name": "prepare_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
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
int prepare_ring(struct xhci_hcd * xhci, struct xhci_ring * ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags)
```

```json
{
  "name": "prepare_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586076944,
      "name": "prepare_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2736",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:prepare_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586076944,
      "name": "prepare_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
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
int prepare_ring(struct xhci_hcd * xhci, struct xhci_ring * ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags)
```

```json
{
  "name": "prepare_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586158528,
      "name": "prepare_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2838",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:prepare_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586158528,
      "name": "prepare_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
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
int prepare_ring(struct xhci_hcd * xhci, struct xhci_ring * ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags)
```

```json
{
  "name": "prepare_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586603808,
      "name": "prepare_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2842",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:prepare_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586603808,
      "name": "prepare_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
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
int prepare_ring(struct xhci_hcd * xhci, struct xhci_ring * ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags)
```

```json
{
  "name": "prepare_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586869344,
      "name": "prepare_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2761",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:prepare_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586869344,
      "name": "prepare_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
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
int prepare_ring(struct xhci_hcd * xhci, struct xhci_ring * ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags)
```

```json
{
  "name": "prepare_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587024656,
      "name": "prepare_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2825",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:prepare_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587024656,
      "name": "prepare_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
int prepare_ring(struct xhci_hcd * xhci, struct xhci_ring * ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags)
```

```json
{
  "name": "prepare_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "prepare_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2871",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:prepare_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587286400,
      "name": "prepare_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
    },
    {
      "addr": 18446744071587311011,
      "name": "prepare_ring.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
int prepare_ring(struct xhci_hcd * xhci, struct xhci_ring * ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags)
```

```json
{
  "name": "prepare_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "prepare_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2898",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:prepare_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587487344,
      "name": "prepare_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
    },
    {
      "addr": 18446744071587512269,
      "name": "prepare_ring.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
int prepare_ring(struct xhci_hcd * xhci, struct xhci_ring * ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags)
```

```json
{
  "name": "prepare_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "prepare_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2944",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:prepare_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588350272,
      "name": "prepare_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    },
    {
      "addr": 18446744071588375066,
      "name": "prepare_ring.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
int prepare_ring(struct xhci_hcd * xhci, struct xhci_ring * ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags)
```

```json
{
  "name": "prepare_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "prepare_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2953",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:prepare_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588381120,
      "name": "prepare_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    },
    {
      "addr": 18446744071591565631,
      "name": "prepare_ring.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
int prepare_ring(struct xhci_hcd * xhci, struct xhci_ring * ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags)
```

```json
{
  "name": "prepare_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "prepare_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3128",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:prepare_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588263568,
      "name": "prepare_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
    },
    {
      "addr": 18446744071591508594,
      "name": "prepare_ring.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
int prepare_ring(struct xhci_hcd * xhci, struct xhci_ring * ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags)
```

```json
{
  "name": "prepare_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "prepare_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3198",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:prepare_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588914448,
      "name": "prepare_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
    },
    {
      "addr": 18446744071592610029,
      "name": "prepare_ring.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
int prepare_ring(struct xhci_hcd * xhci, struct xhci_ring * ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags)
```

```json
{
  "name": "prepare_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "prepare_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3133",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:prepare_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590344160,
      "name": "prepare_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
    },
    {
      "addr": 18446744071594493054,
      "name": "prepare_ring.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int prepare_ring(struct xhci_hcd * xhci, struct xhci_ring * ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags)
```

```json
{
  "name": "prepare_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591973296,
      "name": "prepare_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3140",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:prepare_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591973296,
      "name": "prepare_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
int prepare_ring(struct xhci_hcd * xhci, struct xhci_ring * ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags)
```

```json
{
  "name": "prepare_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592394976,
      "name": "prepare_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3163",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:prepare_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592394976,
      "name": "prepare_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 961
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
int prepare_ring(struct xhci_hcd * xhci, struct xhci_ring * ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags)
```

```json
{
  "name": "prepare_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593137920,
      "name": "prepare_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3206",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:prepare_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593137920,
      "name": "prepare_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 961
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
int prepare_ring(struct xhci_hcd * xhci, struct xhci_ring * ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags)
```

```json
{
  "name": "prepare_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500624720,
      "name": "prepare_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2898",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:prepare_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500624720,
      "name": "prepare_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
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
int prepare_ring(struct xhci_hcd * xhci, struct xhci_ring * ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags)
```

```json
{
  "name": "prepare_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233086392,
      "name": "prepare_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2898",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:prepare_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233086392,
      "name": "prepare_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
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
int prepare_ring(struct xhci_hcd * xhci, struct xhci_ring * ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags)
```

```json
{
  "name": "prepare_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294041408,
      "name": "prepare_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2898",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:prepare_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294041408,
      "name": "prepare_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 784
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
int prepare_ring(struct xhci_hcd * xhci, struct xhci_ring * ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags)
```

```json
{
  "name": "prepare_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277491818,
      "name": "prepare_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2898",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:prepare_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277491818,
      "name": "prepare_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 482
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
int prepare_ring(struct xhci_hcd * xhci, struct xhci_ring * ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags)
```

```json
{
  "name": "prepare_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "prepare_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2898",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:prepare_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587193376,
      "name": "prepare_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
    },
    {
      "addr": 18446744071587218301,
      "name": "prepare_ring.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
int prepare_ring(struct xhci_hcd * xhci, struct xhci_ring * ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags)
```

```json
{
  "name": "prepare_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "prepare_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2898",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:prepare_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586952128,
      "name": "prepare_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
    },
    {
      "addr": 18446744071586977053,
      "name": "prepare_ring.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
int prepare_ring(struct xhci_hcd * xhci, struct xhci_ring * ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags)
```

```json
{
  "name": "prepare_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "prepare_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2898",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:prepare_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587441904,
      "name": "prepare_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
    },
    {
      "addr": 18446744071587466829,
      "name": "prepare_ring.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
int prepare_ring(struct xhci_hcd * xhci, struct xhci_ring * ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags)
```

```json
{
  "name": "prepare_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "prepare_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2898",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:prepare_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587548912,
      "name": "prepare_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
    },
    {
      "addr": 18446744071587574445,
      "name": "prepare_ring.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
