# Function: <code>inc_enq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void inc_enq(struct xhci_hcd * xhci, struct xhci_ring * ring, bool more_trbs_coming)
```

```json
{
  "name": "inc_enq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585491936,
      "name": "inc_enq",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:192",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585491936,
      "name": "inc_enq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
void inc_enq(struct xhci_hcd * xhci, struct xhci_ring * ring, bool more_trbs_coming)
```

```json
{
  "name": "inc_enq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585887440,
      "name": "inc_enq",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:180",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585887440,
      "name": "inc_enq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
void inc_enq(struct xhci_hcd * xhci, struct xhci_ring * ring, bool more_trbs_coming)
```

```json
{
  "name": "inc_enq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586076544,
      "name": "inc_enq",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:199",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586076544,
      "name": "inc_enq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void inc_enq(struct xhci_hcd * xhci, struct xhci_ring * ring, bool more_trbs_coming)
```

```json
{
  "name": "inc_enq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586158064,
      "name": "inc_enq",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:215",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586158064,
      "name": "inc_enq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void inc_enq(struct xhci_hcd * xhci, struct xhci_ring * ring, bool more_trbs_coming)
```

```json
{
  "name": "inc_enq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586603216,
      "name": "inc_enq",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:204",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586603216,
      "name": "inc_enq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
void inc_enq(struct xhci_hcd * xhci, struct xhci_ring * ring, bool more_trbs_coming)
```

```json
{
  "name": "inc_enq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586868768,
      "name": "inc_enq",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:204",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586868768,
      "name": "inc_enq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
void inc_enq(struct xhci_hcd * xhci, struct xhci_ring * ring, bool more_trbs_coming)
```

```json
{
  "name": "inc_enq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587024080,
      "name": "inc_enq",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:204",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587024080,
      "name": "inc_enq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
void inc_enq(struct xhci_hcd * xhci, struct xhci_ring * ring, bool more_trbs_coming)
```

```json
{
  "name": "inc_enq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587286144,
      "name": "inc_enq",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:204",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587286144,
      "name": "inc_enq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
void inc_enq(struct xhci_hcd * xhci, struct xhci_ring * ring, bool more_trbs_coming)
```

```json
{
  "name": "inc_enq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587486928,
      "name": "inc_enq",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:204",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587486928,
      "name": "inc_enq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
void inc_enq(struct xhci_hcd * xhci, struct xhci_ring * ring, bool more_trbs_coming)
```

```json
{
  "name": "inc_enq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588353584,
      "name": "inc_enq",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:204",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_trb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588353584,
      "name": "inc_enq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
void inc_enq(struct xhci_hcd * xhci, struct xhci_ring * ring, bool more_trbs_coming)
```

```json
{
  "name": "inc_enq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588384880,
      "name": "inc_enq",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:204",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_trb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588384880,
      "name": "inc_enq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
void inc_enq(struct xhci_hcd * xhci, struct xhci_ring * ring, bool more_trbs_coming)
```

```json
{
  "name": "inc_enq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inc_enq",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:216",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_trb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588265600,
      "name": "inc_enq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
    },
    {
      "addr": 18446744071591509006,
      "name": "inc_enq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void inc_enq(struct xhci_hcd * xhci, struct xhci_ring * ring, bool more_trbs_coming)
```

```json
{
  "name": "inc_enq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inc_enq",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:216",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_trb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588916592,
      "name": "inc_enq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    },
    {
      "addr": 18446744071592610466,
      "name": "inc_enq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void inc_enq(struct xhci_hcd * xhci, struct xhci_ring * ring, bool more_trbs_coming)
```

```json
{
  "name": "inc_enq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inc_enq",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:216",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_trb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590347664,
      "name": "inc_enq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
    },
    {
      "addr": 18446744071594493479,
      "name": "inc_enq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void inc_enq(struct xhci_hcd * xhci, struct xhci_ring * ring, bool more_trbs_coming)
```

```json
{
  "name": "inc_enq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591977568,
      "name": "inc_enq",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:216",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_trb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591977568,
      "name": "inc_enq",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void inc_enq(struct xhci_hcd * xhci, struct xhci_ring * ring, bool more_trbs_coming)
```

```json
{
  "name": "inc_enq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592399024,
      "name": "inc_enq",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:214",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_trb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592399024,
      "name": "inc_enq",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void inc_enq(struct xhci_hcd * xhci, struct xhci_ring * ring, bool more_trbs_coming)
```

```json
{
  "name": "inc_enq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593141664,
      "name": "inc_enq",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:214",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_trb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593141664,
      "name": "inc_enq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
void inc_enq(struct xhci_hcd * xhci, struct xhci_ring * ring, bool more_trbs_coming)
```

```json
{
  "name": "inc_enq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500628800,
      "name": "inc_enq",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:204",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500628800,
      "name": "inc_enq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
void inc_enq(struct xhci_hcd * xhci, struct xhci_ring * ring, bool more_trbs_coming)
```

```json
{
  "name": "inc_enq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233083944,
      "name": "inc_enq",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:204",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233083944,
      "name": "inc_enq",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void inc_enq(struct xhci_hcd * xhci, struct xhci_ring * ring, bool more_trbs_coming)
```

```json
{
  "name": "inc_enq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294040720,
      "name": "inc_enq",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:204",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294040720,
      "name": "inc_enq",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void inc_enq(struct xhci_hcd * xhci, struct xhci_ring * ring, bool more_trbs_coming)
```

```json
{
  "name": "inc_enq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277491536,
      "name": "inc_enq",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:204",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277491536,
      "name": "inc_enq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
void inc_enq(struct xhci_hcd * xhci, struct xhci_ring * ring, bool more_trbs_coming)
```

```json
{
  "name": "inc_enq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587192960,
      "name": "inc_enq",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:204",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587192960,
      "name": "inc_enq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
void inc_enq(struct xhci_hcd * xhci, struct xhci_ring * ring, bool more_trbs_coming)
```

```json
{
  "name": "inc_enq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586951712,
      "name": "inc_enq",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:204",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586951712,
      "name": "inc_enq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
void inc_enq(struct xhci_hcd * xhci, struct xhci_ring * ring, bool more_trbs_coming)
```

```json
{
  "name": "inc_enq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587441488,
      "name": "inc_enq",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:204",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587441488,
      "name": "inc_enq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
void inc_enq(struct xhci_hcd * xhci, struct xhci_ring * ring, bool more_trbs_coming)
```

```json
{
  "name": "inc_enq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587548464,
      "name": "inc_enq",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:204",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587548464,
      "name": "inc_enq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
