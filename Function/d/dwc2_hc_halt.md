# Function: <code>dwc2_hc_halt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void dwc2_hc_halt(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_hc_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585278960,
      "name": "dwc2_hc_halt",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1410",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585278960,
      "name": "dwc2_hc_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 439
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
void dwc2_hc_halt(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_hc_halt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585691808,
      "name": "dwc2_hc_halt",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:928",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_queue_transaction",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585691808,
      "name": "dwc2_hc_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
void dwc2_hc_halt(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_hc_halt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585880784,
      "name": "dwc2_hc_halt",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:958",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_queue_transaction",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585880784,
      "name": "dwc2_hc_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
void dwc2_hc_halt(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_hc_halt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585963488,
      "name": "dwc2_hc_halt",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:975",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_queue_transaction",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585963488,
      "name": "dwc2_hc_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 462
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
void dwc2_hc_halt(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_hc_halt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586407168,
      "name": "dwc2_hc_halt",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:981",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_queue_transaction",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586407168,
      "name": "dwc2_hc_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 474
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
void dwc2_hc_halt(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_hc_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586667712,
      "name": "dwc2_hc_halt",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:998",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_queue_transaction",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586667712,
      "name": "dwc2_hc_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 613
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
void dwc2_hc_halt(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_hc_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586820864,
      "name": "dwc2_hc_halt",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:991",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_queue_transaction",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586820864,
      "name": "dwc2_hc_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 837
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
void dwc2_hc_halt(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_hc_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hc_halt",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:801",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_queue_transaction",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587097248,
      "name": "dwc2_hc_halt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071587079216,
      "name": "dwc2_hc_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 792
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
void dwc2_hc_halt(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_hc_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hc_halt",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:801",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_queue_transaction",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587297739,
      "name": "dwc2_hc_halt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071587279696,
      "name": "dwc2_hc_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 792
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
void dwc2_hc_halt(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_hc_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hc_halt",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:801",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_queue_transaction",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588153040,
      "name": "dwc2_hc_halt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071588135104,
      "name": "dwc2_hc_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 776
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
void dwc2_hc_halt(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_hc_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hc_halt",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:801",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_queue_transaction",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591556935,
      "name": "dwc2_hc_halt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071588175744,
      "name": "dwc2_hc_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 733
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
void dwc2_hc_halt(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_hc_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hc_halt",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:799",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_queue_transaction",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591498969,
      "name": "dwc2_hc_halt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071588053856,
      "name": "dwc2_hc_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 738
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
void dwc2_hc_halt(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_hc_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hc_halt",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:799",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_queue_transaction",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592587551,
      "name": "dwc2_hc_halt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
    },
    {
      "addr": 18446744071588678304,
      "name": "dwc2_hc_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 865
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
void dwc2_hc_halt(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_hc_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hc_halt",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:795",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_queue_transaction",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594468270,
      "name": "dwc2_hc_halt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
    },
    {
      "addr": 18446744071590096512,
      "name": "dwc2_hc_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 935
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void dwc2_hc_halt(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_hc_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hc_halt",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:766",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_queue_transaction",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596285041,
      "name": "dwc2_hc_halt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
    },
    {
      "addr": 18446744071591707488,
      "name": "dwc2_hc_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 951
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void dwc2_hc_halt(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_hc_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hc_halt",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:766",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_queue_transaction",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596814916,
      "name": "dwc2_hc_halt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
    },
    {
      "addr": 18446744071592130896,
      "name": "dwc2_hc_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 949
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void dwc2_hc_halt(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_hc_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hc_halt",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:766",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_queue_transaction",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597738523,
      "name": "dwc2_hc_halt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
    },
    {
      "addr": 18446744071592871424,
      "name": "dwc2_hc_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 949
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
void dwc2_hc_halt(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_hc_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500393832,
      "name": "dwc2_hc_halt",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:801",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_queue_transaction",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500393832,
      "name": "dwc2_hc_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 740
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
void dwc2_hc_halt(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_hc_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232849972,
      "name": "dwc2_hc_halt",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:801",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_queue_transaction",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232849972,
      "name": "dwc2_hc_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 852
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
void dwc2_hc_halt(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_hc_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293722176,
      "name": "dwc2_hc_halt",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:801",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_queue_transaction",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293722176,
      "name": "dwc2_hc_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1724
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
void dwc2_hc_halt(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_hc_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277282328,
      "name": "dwc2_hc_halt",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:801",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_queue_transaction",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277282328,
      "name": "dwc2_hc_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1014
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
void dwc2_hc_halt(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_hc_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hc_halt",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:801",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_queue_transaction",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587003819,
      "name": "dwc2_hc_halt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071586985776,
      "name": "dwc2_hc_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 792
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void dwc2_hc_halt(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_hc_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hc_halt",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:801",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_queue_transaction",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587252299,
      "name": "dwc2_hc_halt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071587234256,
      "name": "dwc2_hc_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 792
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
void dwc2_hc_halt(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_hc_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hc_halt",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:801",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_queue_transaction",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587359067,
      "name": "dwc2_hc_halt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071587341024,
      "name": "dwc2_hc_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 792
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void dwc2_hc_halt(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, enum dwc2_halt_status halt_status)
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
