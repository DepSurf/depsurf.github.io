# Function: <code>xhci_td_cleanup</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int xhci_td_cleanup(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_ring * ep_ring, int * status)
```

```json
{
  "name": "xhci_td_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586161616,
      "name": "xhci_td_cleanup",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1884",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586161616,
      "name": "xhci_td_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
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
int xhci_td_cleanup(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_ring * ep_ring, int * status)
```

```json
{
  "name": "xhci_td_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586606608,
      "name": "xhci_td_cleanup",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1878",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586606608,
      "name": "xhci_td_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
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
int xhci_td_cleanup(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_ring * ep_ring, int * status)
```

```json
{
  "name": "xhci_td_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586872112,
      "name": "xhci_td_cleanup",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1803",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586872112,
      "name": "xhci_td_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
int xhci_td_cleanup(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_ring * ep_ring, int * status)
```

```json
{
  "name": "xhci_td_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587027456,
      "name": "xhci_td_cleanup",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1851",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587027456,
      "name": "xhci_td_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
int xhci_td_cleanup(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_ring * ep_ring, int * status)
```

```json
{
  "name": "xhci_td_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_td_cleanup",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1897",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587289488,
      "name": "xhci_td_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    },
    {
      "addr": 18446744071587311588,
      "name": "xhci_td_cleanup.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int xhci_td_cleanup(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_ring * ep_ring, int * status)
```

```json
{
  "name": "xhci_td_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_td_cleanup",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1897",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587490432,
      "name": "xhci_td_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    },
    {
      "addr": 18446744071587512846,
      "name": "xhci_td_cleanup.cold",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_td_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_td_cleanup",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1923",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588352912,
      "name": "xhci_td_cleanup.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    },
    {
      "addr": 18446744071588375232,
      "name": "xhci_td_cleanup.isra.0.cold",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_td_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_td_cleanup",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1928",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588383472,
      "name": "xhci_td_cleanup.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    },
    {
      "addr": 18446744071591565797,
      "name": "xhci_td_cleanup.isra.0.cold",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_td_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_td_cleanup",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:773",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588265072,
      "name": "xhci_td_cleanup.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    },
    {
      "addr": 18446744071591508793,
      "name": "xhci_td_cleanup.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
  "name": "xhci_td_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_td_cleanup",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:809",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588915952,
      "name": "xhci_td_cleanup.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
    },
    {
      "addr": 18446744071592610253,
      "name": "xhci_td_cleanup.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_td_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_td_cleanup",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:801",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590346608,
      "name": "xhci_td_cleanup.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
    },
    {
      "addr": 18446744071594493254,
      "name": "xhci_td_cleanup.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_td_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591976176,
      "name": "xhci_td_cleanup",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:801",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591976176,
      "name": "xhci_td_cleanup.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 383
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_td_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592397632,
      "name": "xhci_td_cleanup",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:832",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592397632,
      "name": "xhci_td_cleanup.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_td_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593140608,
      "name": "xhci_td_cleanup",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:840",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593140608,
      "name": "xhci_td_cleanup.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
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
int xhci_td_cleanup(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_ring * ep_ring, int * status)
```

```json
{
  "name": "xhci_td_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500628408,
      "name": "xhci_td_cleanup",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1897",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500628408,
      "name": "xhci_td_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
int xhci_td_cleanup(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_ring * ep_ring, int * status)
```

```json
{
  "name": "xhci_td_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233089104,
      "name": "xhci_td_cleanup",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1897",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233089104,
      "name": "xhci_td_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
int xhci_td_cleanup(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_ring * ep_ring, int * status)
```

```json
{
  "name": "xhci_td_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294046400,
      "name": "xhci_td_cleanup",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1897",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:finish_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294046400,
      "name": "xhci_td_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
int xhci_td_cleanup(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_ring * ep_ring, int * status)
```

```json
{
  "name": "xhci_td_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277495978,
      "name": "xhci_td_cleanup",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1897",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277495978,
      "name": "xhci_td_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
int xhci_td_cleanup(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_ring * ep_ring, int * status)
```

```json
{
  "name": "xhci_td_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_td_cleanup",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1897",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587196464,
      "name": "xhci_td_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    },
    {
      "addr": 18446744071587218878,
      "name": "xhci_td_cleanup.cold",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int xhci_td_cleanup(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_ring * ep_ring, int * status)
```

```json
{
  "name": "xhci_td_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_td_cleanup",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1897",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586955216,
      "name": "xhci_td_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    },
    {
      "addr": 18446744071586977630,
      "name": "xhci_td_cleanup.cold",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int xhci_td_cleanup(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_ring * ep_ring, int * status)
```

```json
{
  "name": "xhci_td_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_td_cleanup",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1897",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587444992,
      "name": "xhci_td_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    },
    {
      "addr": 18446744071587467406,
      "name": "xhci_td_cleanup.cold",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int xhci_td_cleanup(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_ring * ep_ring, int * status)
```

```json
{
  "name": "xhci_td_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_td_cleanup",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1897",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587552208,
      "name": "xhci_td_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    },
    {
      "addr": 18446744071587575018,
      "name": "xhci_td_cleanup.cold",
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int xhci_td_cleanup(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_ring * ep_ring, int * status)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int xhci_td_cleanup(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_ring * ep_ring, int * status)
```
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
