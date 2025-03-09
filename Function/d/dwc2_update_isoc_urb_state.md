# Function: <code>dwc2_update_isoc_urb_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_update_isoc_urb_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585313823,
      "name": "dwc2_update_isoc_urb_state",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:543",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_update_isoc_urb_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585707696,
      "name": "dwc2_update_isoc_urb_state",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:566",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585707696,
      "name": "dwc2_update_isoc_urb_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
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
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_update_isoc_urb_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585896368,
      "name": "dwc2_update_isoc_urb_state",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:566",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585896368,
      "name": "dwc2_update_isoc_urb_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
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
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_update_isoc_urb_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585979056,
      "name": "dwc2_update_isoc_urb_state",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:565",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585979056,
      "name": "dwc2_update_isoc_urb_state",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_update_isoc_urb_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586422976,
      "name": "dwc2_update_isoc_urb_state",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:566",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586422976,
      "name": "dwc2_update_isoc_urb_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 415
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
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_update_isoc_urb_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586686704,
      "name": "dwc2_update_isoc_urb_state",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:584",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586686704,
      "name": "dwc2_update_isoc_urb_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 415
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
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_update_isoc_urb_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586840832,
      "name": "dwc2_update_isoc_urb_state",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:584",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586840832,
      "name": "dwc2_update_isoc_urb_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
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
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_update_isoc_urb_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_update_isoc_urb_state",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:584",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587099200,
      "name": "dwc2_update_isoc_urb_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
    },
    {
      "addr": 18446744071587108415,
      "name": "dwc2_update_isoc_urb_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_update_isoc_urb_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_update_isoc_urb_state",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:584",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587299632,
      "name": "dwc2_update_isoc_urb_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
    },
    {
      "addr": 18446744071587308847,
      "name": "dwc2_update_isoc_urb_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_update_isoc_urb_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588158436,
      "name": "dwc2_update_isoc_urb_state",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:584",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588155152,
      "name": "dwc2_update_isoc_urb_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
    },
    {
      "addr": 18446744071588164979,
      "name": "dwc2_update_isoc_urb_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_update_isoc_urb_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588197444,
      "name": "dwc2_update_isoc_urb_state",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:584",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588194144,
      "name": "dwc2_update_isoc_urb_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
    },
    {
      "addr": 18446744071591557847,
      "name": "dwc2_update_isoc_urb_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
  "name": "dwc2_update_isoc_urb_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588081138,
      "name": "dwc2_update_isoc_urb_state",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:584",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_update_isoc_urb_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588711384,
      "name": "dwc2_update_isoc_urb_state",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:584",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_update_isoc_urb_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590129088,
      "name": "dwc2_update_isoc_urb_state",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:584",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_update_isoc_urb_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591742640,
      "name": "dwc2_update_isoc_urb_state",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:554",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_update_isoc_urb_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592166181,
      "name": "dwc2_update_isoc_urb_state",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:554",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_update_isoc_urb_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592906837,
      "name": "dwc2_update_isoc_urb_state",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:554",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_update_isoc_urb_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500415016,
      "name": "dwc2_update_isoc_urb_state",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:584",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500415016,
      "name": "dwc2_update_isoc_urb_state",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_update_isoc_urb_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232870484,
      "name": "dwc2_update_isoc_urb_state",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:584",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232870484,
      "name": "dwc2_update_isoc_urb_state",
      "section": ".text",
      "bind": "STB_LOCAL",
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
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_update_isoc_urb_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293755120,
      "name": "dwc2_update_isoc_urb_state",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:584",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293755120,
      "name": "dwc2_update_isoc_urb_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
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
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_update_isoc_urb_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277305426,
      "name": "dwc2_update_isoc_urb_state",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:584",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277305426,
      "name": "dwc2_update_isoc_urb_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_update_isoc_urb_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_update_isoc_urb_state",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:584",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587005712,
      "name": "dwc2_update_isoc_urb_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
    },
    {
      "addr": 18446744071587014927,
      "name": "dwc2_update_isoc_urb_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_update_isoc_urb_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_update_isoc_urb_state",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:584",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587254192,
      "name": "dwc2_update_isoc_urb_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
    },
    {
      "addr": 18446744071587263407,
      "name": "dwc2_update_isoc_urb_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_update_isoc_urb_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_update_isoc_urb_state",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:584",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587360960,
      "name": "dwc2_update_isoc_urb_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
    },
    {
      "addr": 18446744071587370171,
      "name": "dwc2_update_isoc_urb_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```
</details>
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
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
