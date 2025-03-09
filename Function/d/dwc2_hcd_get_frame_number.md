# Function: <code>dwc2_hcd_get_frame_number</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_get_frame_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585294597,
      "name": "dwc2_hcd_get_frame_number",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:1879",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585306672,
      "name": "dwc2_hcd_get_frame_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
int dwc2_hcd_get_frame_number(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_get_frame_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585680933,
      "name": "dwc2_hcd_get_frame_number",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:3736",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585694912,
      "name": "dwc2_hcd_get_frame_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int dwc2_hcd_get_frame_number(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_get_frame_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585869909,
      "name": "dwc2_hcd_get_frame_number",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:3767",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585883872,
      "name": "dwc2_hcd_get_frame_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int dwc2_hcd_get_frame_number(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_get_frame_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585952565,
      "name": "dwc2_hcd_get_frame_number",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:3795",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585966656,
      "name": "dwc2_hcd_get_frame_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int dwc2_hcd_get_frame_number(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_get_frame_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586396069,
      "name": "dwc2_hcd_get_frame_number",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:3804",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586410384,
      "name": "dwc2_hcd_get_frame_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_get_frame_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586657445,
      "name": "dwc2_hcd_get_frame_number",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:3934",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586672496,
      "name": "dwc2_hcd_get_frame_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_get_frame_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586809789,
      "name": "dwc2_hcd_get_frame_number",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:3934",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586827264,
      "name": "dwc2_hcd_get_frame_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_get_frame_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587068493,
      "name": "dwc2_hcd_get_frame_number",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:3754",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587084240,
      "name": "dwc2_hcd_get_frame_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_get_frame_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587268829,
      "name": "dwc2_hcd_get_frame_number",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:3754",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587284720,
      "name": "dwc2_hcd_get_frame_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int dwc2_hcd_get_frame_number(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_get_frame_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588124173,
      "name": "dwc2_hcd_get_frame_number",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:3754",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588140208,
      "name": "dwc2_hcd_get_frame_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int dwc2_hcd_get_frame_number(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_get_frame_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588164957,
      "name": "dwc2_hcd_get_frame_number",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:3755",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588180736,
      "name": "dwc2_hcd_get_frame_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int dwc2_hcd_get_frame_number(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_get_frame_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588046893,
      "name": "dwc2_hcd_get_frame_number",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:3806",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588057584,
      "name": "dwc2_hcd_get_frame_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int dwc2_hcd_get_frame_number(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_get_frame_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588671363,
      "name": "dwc2_hcd_get_frame_number",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:3806",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592588785,
      "name": "dwc2_hcd_get_frame_number.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071588683248,
      "name": "dwc2_hcd_get_frame_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int dwc2_hcd_get_frame_number(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_get_frame_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590089699,
      "name": "dwc2_hcd_get_frame_number",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:3802",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594469685,
      "name": "dwc2_hcd_get_frame_number.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071590101600,
      "name": "dwc2_hcd_get_frame_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int dwc2_hcd_get_frame_number(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_get_frame_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591700307,
      "name": "dwc2_hcd_get_frame_number",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:3773",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596286307,
      "name": "dwc2_hcd_get_frame_number.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071591712896,
      "name": "dwc2_hcd_get_frame_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int dwc2_hcd_get_frame_number(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_get_frame_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592123683,
      "name": "dwc2_hcd_get_frame_number",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:3773",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596816169,
      "name": "dwc2_hcd_get_frame_number.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071592136272,
      "name": "dwc2_hcd_get_frame_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int dwc2_hcd_get_frame_number(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_get_frame_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592864211,
      "name": "dwc2_hcd_get_frame_number",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:3773",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597739776,
      "name": "dwc2_hcd_get_frame_number.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071592876800,
      "name": "dwc2_hcd_get_frame_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_get_frame_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500382228,
      "name": "dwc2_hcd_get_frame_number",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:3754",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500399856,
      "name": "dwc2_hcd_get_frame_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int dwc2_hcd_get_frame_number(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_get_frame_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232836248,
      "name": "dwc2_hcd_get_frame_number",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:3754",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_calc_starting_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232855812,
      "name": "dwc2_hcd_get_frame_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_get_frame_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293703412,
      "name": "dwc2_hcd_get_frame_number",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:3754",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293731760,
      "name": "dwc2_hcd_get_frame_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_get_frame_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277268364,
      "name": "dwc2_hcd_get_frame_number",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:3754",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277288856,
      "name": "dwc2_hcd_get_frame_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_get_frame_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586974909,
      "name": "dwc2_hcd_get_frame_number",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:3754",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586990800,
      "name": "dwc2_hcd_get_frame_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_get_frame_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587223389,
      "name": "dwc2_hcd_get_frame_number",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:3754",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587239280,
      "name": "dwc2_hcd_get_frame_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_get_frame_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587330157,
      "name": "dwc2_hcd_get_frame_number",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:3754",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587346048,
      "name": "dwc2_hcd_get_frame_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int dwc2_hcd_get_frame_number(struct dwc2_hsotg * hsotg)
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
