# Function: <code>dwc2_hsotg_wait_bit_clear</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_clear",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586646336,
      "name": "dwc2_hsotg_wait_bit_clear",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1008",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586646336,
      "name": "dwc2_hsotg_wait_bit_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586796192,
      "name": "dwc2_hsotg_wait_bit_clear",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1009",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586796192,
      "name": "dwc2_hsotg_wait_bit_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587052320,
      "name": "dwc2_hsotg_wait_bit_clear",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1009",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587052320,
      "name": "dwc2_hsotg_wait_bit_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587252720,
      "name": "dwc2_hsotg_wait_bit_clear",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1009",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587252720,
      "name": "dwc2_hsotg_wait_bit_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_clear",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588107427,
      "name": "dwc2_hsotg_wait_bit_clear",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1024",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588108000,
      "name": "dwc2_hsotg_wait_bit_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_clear",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588149187,
      "name": "dwc2_hsotg_wait_bit_clear",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1024",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588149760,
      "name": "dwc2_hsotg_wait_bit_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_clear",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588030790,
      "name": "dwc2_hsotg_wait_bit_clear",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:968",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588031376,
      "name": "dwc2_hsotg_wait_bit_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_clear",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hsotg_wait_bit_clear",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:968",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592576957,
      "name": "dwc2_hsotg_wait_bit_clear.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588650128,
      "name": "dwc2_hsotg_wait_bit_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_clear",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hsotg_wait_bit_clear",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:968",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594456998,
      "name": "dwc2_hsotg_wait_bit_clear.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071590067024,
      "name": "dwc2_hsotg_wait_bit_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_clear",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hsotg_wait_bit_clear",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:938",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596275974,
      "name": "dwc2_hsotg_wait_bit_clear.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071591674800,
      "name": "dwc2_hsotg_wait_bit_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_clear",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hsotg_wait_bit_clear",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:938",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596805820,
      "name": "dwc2_hsotg_wait_bit_clear.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071592097712,
      "name": "dwc2_hsotg_wait_bit_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_clear",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hsotg_wait_bit_clear",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:938",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597729427,
      "name": "dwc2_hsotg_wait_bit_clear.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071592838144,
      "name": "dwc2_hsotg_wait_bit_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500361960,
      "name": "dwc2_hsotg_wait_bit_clear",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1009",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500361960,
      "name": "dwc2_hsotg_wait_bit_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_clear",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232820740,
      "name": "dwc2_hsotg_wait_bit_clear",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1009",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232820740,
      "name": "dwc2_hsotg_wait_bit_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293673440,
      "name": "dwc2_hsotg_wait_bit_clear",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1009",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293673440,
      "name": "dwc2_hsotg_wait_bit_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277246406,
      "name": "dwc2_hsotg_wait_bit_clear",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1009",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277246406,
      "name": "dwc2_hsotg_wait_bit_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586958800,
      "name": "dwc2_hsotg_wait_bit_clear",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1009",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586958800,
      "name": "dwc2_hsotg_wait_bit_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587207280,
      "name": "dwc2_hsotg_wait_bit_clear",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1009",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587207280,
      "name": "dwc2_hsotg_wait_bit_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587314352,
      "name": "dwc2_hsotg_wait_bit_clear",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1009",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587314352,
      "name": "dwc2_hsotg_wait_bit_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
