# Function: <code>dwc2_hcd_select_transactions</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
enum dwc2_transaction_type dwc2_hcd_select_transactions(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_select_transactions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585303712,
      "name": "dwc2_hcd_select_transactions",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:902",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585303712,
      "name": "dwc2_hcd_select_transactions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 490
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
enum dwc2_transaction_type dwc2_hcd_select_transactions(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_select_transactions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585694416,
      "name": "dwc2_hcd_select_transactions",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2738",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585694416,
      "name": "dwc2_hcd_select_transactions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
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
enum dwc2_transaction_type dwc2_hcd_select_transactions(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_select_transactions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585883392,
      "name": "dwc2_hcd_select_transactions",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2769",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585883392,
      "name": "dwc2_hcd_select_transactions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
enum dwc2_transaction_type dwc2_hcd_select_transactions(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_select_transactions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585966176,
      "name": "dwc2_hcd_select_transactions",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2782",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585966176,
      "name": "dwc2_hcd_select_transactions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 477
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
enum dwc2_transaction_type dwc2_hcd_select_transactions(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_select_transactions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586409904,
      "name": "dwc2_hcd_select_transactions",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2788",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586409904,
      "name": "dwc2_hcd_select_transactions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
enum dwc2_transaction_type dwc2_hcd_select_transactions(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_select_transactions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586672000,
      "name": "dwc2_hcd_select_transactions",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2905",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586672000,
      "name": "dwc2_hcd_select_transactions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
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
enum dwc2_transaction_type dwc2_hcd_select_transactions(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_select_transactions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586826768,
      "name": "dwc2_hcd_select_transactions",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2895",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586826768,
      "name": "dwc2_hcd_select_transactions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
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
enum dwc2_transaction_type dwc2_hcd_select_transactions(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_select_transactions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587083760,
      "name": "dwc2_hcd_select_transactions",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2715",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587083760,
      "name": "dwc2_hcd_select_transactions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
enum dwc2_transaction_type dwc2_hcd_select_transactions(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_select_transactions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587284240,
      "name": "dwc2_hcd_select_transactions",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2715",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587284240,
      "name": "dwc2_hcd_select_transactions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
enum dwc2_transaction_type dwc2_hcd_select_transactions(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_select_transactions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588139744,
      "name": "dwc2_hcd_select_transactions",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2715",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588139744,
      "name": "dwc2_hcd_select_transactions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
enum dwc2_transaction_type dwc2_hcd_select_transactions(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_select_transactions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588180272,
      "name": "dwc2_hcd_select_transactions",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2716",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588180272,
      "name": "dwc2_hcd_select_transactions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
enum dwc2_transaction_type dwc2_hcd_select_transactions(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_select_transactions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588057120,
      "name": "dwc2_hcd_select_transactions",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2714",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588057120,
      "name": "dwc2_hcd_select_transactions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
enum dwc2_transaction_type dwc2_hcd_select_transactions(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_select_transactions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hcd_select_transactions",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2714",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592588667,
      "name": "dwc2_hcd_select_transactions.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071588682768,
      "name": "dwc2_hcd_select_transactions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
enum dwc2_transaction_type dwc2_hcd_select_transactions(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_select_transactions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hcd_select_transactions",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2710",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594469567,
      "name": "dwc2_hcd_select_transactions.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071590101088,
      "name": "dwc2_hcd_select_transactions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
enum dwc2_transaction_type dwc2_hcd_select_transactions(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_select_transactions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hcd_select_transactions",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2681",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596286189,
      "name": "dwc2_hcd_select_transactions.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071591712368,
      "name": "dwc2_hcd_select_transactions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
enum dwc2_transaction_type dwc2_hcd_select_transactions(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_select_transactions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hcd_select_transactions",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2681",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596816051,
      "name": "dwc2_hcd_select_transactions.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071592135760,
      "name": "dwc2_hcd_select_transactions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 490
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
enum dwc2_transaction_type dwc2_hcd_select_transactions(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_select_transactions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hcd_select_transactions",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2681",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597739658,
      "name": "dwc2_hcd_select_transactions.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071592876288,
      "name": "dwc2_hcd_select_transactions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 490
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
enum dwc2_transaction_type dwc2_hcd_select_transactions(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_select_transactions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500399448,
      "name": "dwc2_hcd_select_transactions",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2715",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500399448,
      "name": "dwc2_hcd_select_transactions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
enum dwc2_transaction_type dwc2_hcd_select_transactions(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_select_transactions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232855384,
      "name": "dwc2_hcd_select_transactions",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2715",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232855384,
      "name": "dwc2_hcd_select_transactions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
enum dwc2_transaction_type dwc2_hcd_select_transactions(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_select_transactions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293731248,
      "name": "dwc2_hcd_select_transactions",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2715",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293731248,
      "name": "dwc2_hcd_select_transactions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
enum dwc2_transaction_type dwc2_hcd_select_transactions(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_select_transactions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277288512,
      "name": "dwc2_hcd_select_transactions",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2715",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277288512,
      "name": "dwc2_hcd_select_transactions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
enum dwc2_transaction_type dwc2_hcd_select_transactions(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_select_transactions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586990320,
      "name": "dwc2_hcd_select_transactions",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2715",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586990320,
      "name": "dwc2_hcd_select_transactions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
enum dwc2_transaction_type dwc2_hcd_select_transactions(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_select_transactions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587238800,
      "name": "dwc2_hcd_select_transactions",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2715",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587238800,
      "name": "dwc2_hcd_select_transactions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
enum dwc2_transaction_type dwc2_hcd_select_transactions(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_select_transactions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587345568,
      "name": "dwc2_hcd_select_transactions",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2715",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587345568,
      "name": "dwc2_hcd_select_transactions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
enum dwc2_transaction_type dwc2_hcd_select_transactions(struct dwc2_hsotg * hsotg)
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
