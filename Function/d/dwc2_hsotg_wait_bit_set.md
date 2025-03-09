# Function: <code>dwc2_hsotg_wait_bit_set</code>

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
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586645829,
      "name": "dwc2_hsotg_wait_bit_set",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:985",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586646208,
      "name": "dwc2_hsotg_wait_bit_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586795040,
      "name": "dwc2_hsotg_wait_bit_set",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:986",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586795040,
      "name": "dwc2_hsotg_wait_bit_set",
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
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587051152,
      "name": "dwc2_hsotg_wait_bit_set",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:986",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587051152,
      "name": "dwc2_hsotg_wait_bit_set",
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
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587251552,
      "name": "dwc2_hsotg_wait_bit_set",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:986",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587251552,
      "name": "dwc2_hsotg_wait_bit_set",
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
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588107317,
      "name": "dwc2_hsotg_wait_bit_set",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1001",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588107872,
      "name": "dwc2_hsotg_wait_bit_set",
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
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588149093,
      "name": "dwc2_hsotg_wait_bit_set",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1001",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588149632,
      "name": "dwc2_hsotg_wait_bit_set",
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
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588030693,
      "name": "dwc2_hsotg_wait_bit_set",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:945",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588031248,
      "name": "dwc2_hsotg_wait_bit_set",
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
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588649081,
      "name": "dwc2_hsotg_wait_bit_set",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:945",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592576936,
      "name": "dwc2_hsotg_wait_bit_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588649968,
      "name": "dwc2_hsotg_wait_bit_set",
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
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590065913,
      "name": "dwc2_hsotg_wait_bit_set",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:945",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594456977,
      "name": "dwc2_hsotg_wait_bit_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071590066848,
      "name": "dwc2_hsotg_wait_bit_set",
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
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591673545,
      "name": "dwc2_hsotg_wait_bit_set",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:915",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596275953,
      "name": "dwc2_hsotg_wait_bit_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071591674608,
      "name": "dwc2_hsotg_wait_bit_set",
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
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592096457,
      "name": "dwc2_hsotg_wait_bit_set",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:915",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596805799,
      "name": "dwc2_hsotg_wait_bit_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071592097520,
      "name": "dwc2_hsotg_wait_bit_set",
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
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592836889,
      "name": "dwc2_hsotg_wait_bit_set",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:915",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597729406,
      "name": "dwc2_hsotg_wait_bit_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071592837952,
      "name": "dwc2_hsotg_wait_bit_set",
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
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500360168,
      "name": "dwc2_hsotg_wait_bit_set",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:986",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500360168,
      "name": "dwc2_hsotg_wait_bit_set",
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
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232819836,
      "name": "dwc2_hsotg_wait_bit_set",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:986",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232820600,
      "name": "dwc2_hsotg_wait_bit_set",
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
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293670768,
      "name": "dwc2_hsotg_wait_bit_set",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:986",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293670768,
      "name": "dwc2_hsotg_wait_bit_set",
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
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277244052,
      "name": "dwc2_hsotg_wait_bit_set",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:986",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277244052,
      "name": "dwc2_hsotg_wait_bit_set",
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
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586957632,
      "name": "dwc2_hsotg_wait_bit_set",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:986",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586957632,
      "name": "dwc2_hsotg_wait_bit_set",
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
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587206112,
      "name": "dwc2_hsotg_wait_bit_set",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:986",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587206112,
      "name": "dwc2_hsotg_wait_bit_set",
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
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
```

```json
{
  "name": "dwc2_hsotg_wait_bit_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587313184,
      "name": "dwc2_hsotg_wait_bit_set",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:986",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587313184,
      "name": "dwc2_hsotg_wait_bit_set",
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
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
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
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg * hsotg, u32 offset, u32 mask, u32 timeout)
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
