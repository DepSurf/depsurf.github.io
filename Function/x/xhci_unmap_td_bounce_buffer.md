# Function: <code>xhci_unmap_td_bounce_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void xhci_unmap_td_bounce_buffer(struct xhci_hcd * xhci, struct xhci_ring * ring, struct xhci_td * td)
```

```json
{
  "name": "xhci_unmap_td_bounce_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585891936,
      "name": "xhci_unmap_td_bounce_buffer",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:608",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585891936,
      "name": "xhci_unmap_td_bounce_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
  "name": "xhci_unmap_td_bounce_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586079888,
      "name": "xhci_unmap_td_bounce_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:663",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586079888,
      "name": "xhci_unmap_td_bounce_buffer.isra.41",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
  "name": "xhci_unmap_td_bounce_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586161152,
      "name": "xhci_unmap_td_bounce_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:664",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_td_cleanup",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586161152,
      "name": "xhci_unmap_td_bounce_buffer.isra.43",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_unmap_td_bounce_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586606144,
      "name": "xhci_unmap_td_bounce_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:653",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_td_cleanup",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586606144,
      "name": "xhci_unmap_td_bounce_buffer.isra.38",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_unmap_td_bounce_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586871408,
      "name": "xhci_unmap_td_bounce_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:653",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_td_cleanup",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586871408,
      "name": "xhci_unmap_td_bounce_buffer.isra.39",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_unmap_td_bounce_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587026960,
      "name": "xhci_unmap_td_bounce_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:653",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_td_cleanup",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587026960,
      "name": "xhci_unmap_td_bounce_buffer.isra.42",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_unmap_td_bounce_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_unmap_td_bounce_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:660",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_td_cleanup",
        "drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587289232,
      "name": "xhci_unmap_td_bounce_buffer.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    },
    {
      "addr": 18446744071587311387,
      "name": "xhci_unmap_td_bounce_buffer.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_unmap_td_bounce_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_unmap_td_bounce_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:660",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_td_cleanup",
        "drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587490176,
      "name": "xhci_unmap_td_bounce_buffer.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    },
    {
      "addr": 18446744071587512645,
      "name": "xhci_unmap_td_bounce_buffer.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
  "name": "xhci_unmap_td_bounce_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_unmap_td_bounce_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:682",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588351600,
      "name": "xhci_unmap_td_bounce_buffer.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    },
    {
      "addr": 18446744071588375205,
      "name": "xhci_unmap_td_bounce_buffer.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
  "name": "xhci_unmap_td_bounce_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_unmap_td_bounce_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:682",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588382224,
      "name": "xhci_unmap_td_bounce_buffer.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    },
    {
      "addr": 18446744071591565770,
      "name": "xhci_unmap_td_bounce_buffer.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
  "name": "xhci_unmap_td_bounce_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_unmap_td_bounce_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:739",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588264240,
      "name": "xhci_unmap_td_bounce_buffer.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071591508766,
      "name": "xhci_unmap_td_bounce_buffer.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
  "name": "xhci_unmap_td_bounce_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_unmap_td_bounce_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:775",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588915120,
      "name": "xhci_unmap_td_bounce_buffer.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071592610226,
      "name": "xhci_unmap_td_bounce_buffer.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
  "name": "xhci_unmap_td_bounce_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_unmap_td_bounce_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:767",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590344880,
      "name": "xhci_unmap_td_bounce_buffer.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
    },
    {
      "addr": 18446744071594493227,
      "name": "xhci_unmap_td_bounce_buffer.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
  "name": "xhci_unmap_td_bounce_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591974256,
      "name": "xhci_unmap_td_bounce_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:767",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591974256,
      "name": "xhci_unmap_td_bounce_buffer.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
  "name": "xhci_unmap_td_bounce_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592394720,
      "name": "xhci_unmap_td_bounce_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:798",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592394720,
      "name": "xhci_unmap_td_bounce_buffer.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
  "name": "xhci_unmap_td_bounce_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593137664,
      "name": "xhci_unmap_td_bounce_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:806",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593137664,
      "name": "xhci_unmap_td_bounce_buffer.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_unmap_td_bounce_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500626472,
      "name": "xhci_unmap_td_bounce_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:660",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_td_cleanup",
        "drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500626472,
      "name": "xhci_unmap_td_bounce_buffer.isra.0",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void xhci_unmap_td_bounce_buffer(struct xhci_hcd * xhci, struct xhci_ring * ring, struct xhci_td * td)
```

```json
{
  "name": "xhci_unmap_td_bounce_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233088796,
      "name": "xhci_unmap_td_bounce_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:660",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_td_cleanup",
        "drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233088796,
      "name": "xhci_unmap_td_bounce_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "xhci_unmap_td_bounce_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294045936,
      "name": "xhci_unmap_td_bounce_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:660",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_td_cleanup",
        "drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294045936,
      "name": "xhci_unmap_td_bounce_buffer.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
  "name": "xhci_unmap_td_bounce_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277495752,
      "name": "xhci_unmap_td_bounce_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:660",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_td_cleanup",
        "drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277495752,
      "name": "xhci_unmap_td_bounce_buffer.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_unmap_td_bounce_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_unmap_td_bounce_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:660",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_td_cleanup",
        "drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587196208,
      "name": "xhci_unmap_td_bounce_buffer.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    },
    {
      "addr": 18446744071587218677,
      "name": "xhci_unmap_td_bounce_buffer.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_unmap_td_bounce_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_unmap_td_bounce_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:660",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_td_cleanup",
        "drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586954960,
      "name": "xhci_unmap_td_bounce_buffer.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    },
    {
      "addr": 18446744071586977429,
      "name": "xhci_unmap_td_bounce_buffer.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_unmap_td_bounce_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_unmap_td_bounce_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:660",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_td_cleanup",
        "drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587444736,
      "name": "xhci_unmap_td_bounce_buffer.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    },
    {
      "addr": 18446744071587467205,
      "name": "xhci_unmap_td_bounce_buffer.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_unmap_td_bounce_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_unmap_td_bounce_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:660",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_td_cleanup",
        "drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587551952,
      "name": "xhci_unmap_td_bounce_buffer.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    },
    {
      "addr": 18446744071587574817,
      "name": "xhci_unmap_td_bounce_buffer.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void xhci_unmap_td_bounce_buffer(struct xhci_hcd * xhci, struct xhci_ring * ring, struct xhci_td * td)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
void xhci_unmap_td_bounce_buffer(struct xhci_hcd * xhci, struct xhci_ring * ring, struct xhci_td * td)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void xhci_unmap_td_bounce_buffer(struct xhci_hcd * xhci, struct xhci_ring * ring, struct xhci_td * td)
```
</details>
</li>
</ul>
