# Function: <code>dbc_ep_queue</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int dbc_ep_queue(struct dbc_ep * dep, struct dbc_request * req, gfp_t gfp_flags)
```

```json
{
  "name": "dbc_ep_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586659424,
      "name": "dbc_ep_queue",
      "external": true,
      "loc": "drivers/usb/host/xhci-dbgcap.c:328",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_rx",
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586659424,
      "name": "dbc_ep_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 972
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
int dbc_ep_queue(struct dbc_ep * dep, struct dbc_request * req, gfp_t gfp_flags)
```

```json
{
  "name": "dbc_ep_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586923184,
      "name": "dbc_ep_queue",
      "external": true,
      "loc": "drivers/usb/host/xhci-dbgcap.c:329",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_rx",
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586923184,
      "name": "dbc_ep_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 984
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
int dbc_ep_queue(struct dbc_ep * dep, struct dbc_request * req, gfp_t gfp_flags)
```

```json
{
  "name": "dbc_ep_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587080224,
      "name": "dbc_ep_queue",
      "external": true,
      "loc": "drivers/usb/host/xhci-dbgcap.c:329",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_rx",
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587080224,
      "name": "dbc_ep_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 947
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
int dbc_ep_queue(struct dbc_ep * dep, struct dbc_request * req, gfp_t gfp_flags)
```

```json
{
  "name": "dbc_ep_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dbc_ep_queue",
      "external": true,
      "loc": "drivers/usb/host/xhci-dbgcap.c:329",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_rx",
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587346337,
      "name": "dbc_ep_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071587344208,
      "name": "dbc_ep_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 781
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
int dbc_ep_queue(struct dbc_ep * dep, struct dbc_request * req, gfp_t gfp_flags)
```

```json
{
  "name": "dbc_ep_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587546576,
      "name": "dbc_ep_queue",
      "external": true,
      "loc": "drivers/usb/host/xhci-dbgcap.c:328",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_rx",
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587546576,
      "name": "dbc_ep_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int dbc_ep_queue(struct dbc_ep * dep, struct dbc_request * req, gfp_t gfp_flags)
```

```json
{
  "name": "dbc_ep_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588409696,
      "name": "dbc_ep_queue",
      "external": true,
      "loc": "drivers/usb/host/xhci-dbgcap.c:328",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_rx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588409696,
      "name": "dbc_ep_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int dbc_ep_queue(struct dbc_request * req)
```

```json
{
  "name": "dbc_ep_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588440288,
      "name": "dbc_ep_queue",
      "external": true,
      "loc": "drivers/usb/host/xhci-dbgcap.c:332",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_rx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588440288,
      "name": "dbc_ep_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
int dbc_ep_queue(struct dbc_request * req)
```

```json
{
  "name": "dbc_ep_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588323264,
      "name": "dbc_ep_queue",
      "external": true,
      "loc": "drivers/usb/host/xhci-dbgcap.c:332",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_rx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588323264,
      "name": "dbc_ep_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
int dbc_ep_queue(struct dbc_request * req)
```

```json
{
  "name": "dbc_ep_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588980864,
      "name": "dbc_ep_queue",
      "external": true,
      "loc": "drivers/usb/host/xhci-dbgcap.c:332",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_rx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588980864,
      "name": "dbc_ep_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int dbc_ep_queue(struct dbc_request * req)
```

```json
{
  "name": "dbc_ep_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590414624,
      "name": "dbc_ep_queue",
      "external": true,
      "loc": "drivers/usb/host/xhci-dbgcap.c:332",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_rx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590414624,
      "name": "dbc_ep_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int dbc_ep_queue(struct dbc_request * req)
```

```json
{
  "name": "dbc_ep_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592052000,
      "name": "dbc_ep_queue",
      "external": true,
      "loc": "drivers/usb/host/xhci-dbgcap.c:332",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_rx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592052000,
      "name": "dbc_ep_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int dbc_ep_queue(struct dbc_request * req)
```

```json
{
  "name": "dbc_ep_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592474768,
      "name": "dbc_ep_queue",
      "external": true,
      "loc": "drivers/usb/host/xhci-dbgcap.c:332",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_rx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592474768,
      "name": "dbc_ep_queue",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int dbc_ep_queue(struct dbc_request * req)
```

```json
{
  "name": "dbc_ep_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593218832,
      "name": "dbc_ep_queue",
      "external": true,
      "loc": "drivers/usb/host/xhci-dbgcap.c:347",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_rx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593218832,
      "name": "dbc_ep_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int dbc_ep_queue(struct dbc_ep * dep, struct dbc_request * req, gfp_t gfp_flags)
```

```json
{
  "name": "dbc_ep_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500689120,
      "name": "dbc_ep_queue",
      "external": true,
      "loc": "drivers/usb/host/xhci-dbgcap.c:328",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_rx",
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500689120,
      "name": "dbc_ep_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1160
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
int dbc_ep_queue(struct dbc_ep * dep, struct dbc_request * req, gfp_t gfp_flags)
```

```json
{
  "name": "dbc_ep_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233147488,
      "name": "dbc_ep_queue",
      "external": true,
      "loc": "drivers/usb/host/xhci-dbgcap.c:328",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_rx",
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233147488,
      "name": "dbc_ep_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int dbc_ep_queue(struct dbc_ep * dep, struct dbc_request * req, gfp_t gfp_flags)
```

```json
{
  "name": "dbc_ep_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294122048,
      "name": "dbc_ep_queue",
      "external": true,
      "loc": "drivers/usb/host/xhci-dbgcap.c:328",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_rx",
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294122048,
      "name": "dbc_ep_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1304
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
int dbc_ep_queue(struct dbc_ep * dep, struct dbc_request * req, gfp_t gfp_flags)
```

```json
{
  "name": "dbc_ep_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277546636,
      "name": "dbc_ep_queue",
      "external": true,
      "loc": "drivers/usb/host/xhci-dbgcap.c:328",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_rx",
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277546636,
      "name": "dbc_ep_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 888
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int dbc_ep_queue(struct dbc_ep * dep, struct dbc_request * req, gfp_t gfp_flags)
```

```json
{
  "name": "dbc_ep_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587011360,
      "name": "dbc_ep_queue",
      "external": true,
      "loc": "drivers/usb/host/xhci-dbgcap.c:328",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_rx",
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587011360,
      "name": "dbc_ep_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int dbc_ep_queue(struct dbc_ep * dep, struct dbc_request * req, gfp_t gfp_flags)
```

```json
{
  "name": "dbc_ep_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587501136,
      "name": "dbc_ep_queue",
      "external": true,
      "loc": "drivers/usb/host/xhci-dbgcap.c:328",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_rx",
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587501136,
      "name": "dbc_ep_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int dbc_ep_queue(struct dbc_ep * dep, struct dbc_request * req, gfp_t gfp_flags)
```

```json
{
  "name": "dbc_ep_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587608992,
      "name": "dbc_ep_queue",
      "external": true,
      "loc": "drivers/usb/host/xhci-dbgcap.c:328",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_rx",
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587608992,
      "name": "dbc_ep_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int dbc_ep_queue(struct dbc_ep * dep, struct dbc_request * req, gfp_t gfp_flags)
```
</details>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct dbc_ep * dep</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>dep, req, gfp_flags</code> ➡️ <code>req</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
int dbc_ep_queue(struct dbc_ep * dep, struct dbc_request * req, gfp_t gfp_flags)
```
</details>
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
