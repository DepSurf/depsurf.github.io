# Function: <code>dwc2_update_urb_state_abn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void dwc2_update_urb_state_abn(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_hcd_urb * urb, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_update_urb_state_abn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585314320,
      "name": "dwc2_update_urb_state_abn",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:1157",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585314320,
      "name": "dwc2_update_urb_state_abn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_update_urb_state_abn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585707568,
      "name": "dwc2_update_urb_state_abn",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:1140",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585707568,
      "name": "dwc2_update_urb_state_abn.isra.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
  "name": "dwc2_update_urb_state_abn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585896240,
      "name": "dwc2_update_urb_state_abn",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:1145",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585896240,
      "name": "dwc2_update_urb_state_abn.isra.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
  "name": "dwc2_update_urb_state_abn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585978928,
      "name": "dwc2_update_urb_state_abn",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:1145",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585978928,
      "name": "dwc2_update_urb_state_abn.isra.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
  "name": "dwc2_update_urb_state_abn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586422848,
      "name": "dwc2_update_urb_state_abn",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:1146",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586422848,
      "name": "dwc2_update_urb_state_abn.isra.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
  "name": "dwc2_update_urb_state_abn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586686576,
      "name": "dwc2_update_urb_state_abn",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:1171",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586686576,
      "name": "dwc2_update_urb_state_abn.isra.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
  "name": "dwc2_update_urb_state_abn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586841248,
      "name": "dwc2_update_urb_state_abn",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:1171",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586841248,
      "name": "dwc2_update_urb_state_abn.isra.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
  "name": "dwc2_update_urb_state_abn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_update_urb_state_abn",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:1171",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587099616,
      "name": "dwc2_update_urb_state_abn.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071587108439,
      "name": "dwc2_update_urb_state_abn.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
  "name": "dwc2_update_urb_state_abn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_update_urb_state_abn",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:1171",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587300048,
      "name": "dwc2_update_urb_state_abn.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071587308871,
      "name": "dwc2_update_urb_state_abn.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
void dwc2_update_urb_state_abn(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_hcd_urb * urb, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_update_urb_state_abn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_update_urb_state_abn",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:1171",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588156784,
      "name": "dwc2_update_urb_state_abn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071588165046,
      "name": "dwc2_update_urb_state_abn.cold",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void dwc2_update_urb_state_abn(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_hcd_urb * urb, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_update_urb_state_abn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_update_urb_state_abn",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:1171",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588195536,
      "name": "dwc2_update_urb_state_abn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071591557870,
      "name": "dwc2_update_urb_state_abn.cold",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void dwc2_update_urb_state_abn(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_hcd_urb * urb, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_update_urb_state_abn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_update_urb_state_abn",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:1171",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588079136,
      "name": "dwc2_update_urb_state_abn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071591500477,
      "name": "dwc2_update_urb_state_abn.cold",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void dwc2_update_urb_state_abn(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_hcd_urb * urb, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_update_urb_state_abn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_update_urb_state_abn",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:1171",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588707984,
      "name": "dwc2_update_urb_state_abn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071592596059,
      "name": "dwc2_update_urb_state_abn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void dwc2_update_urb_state_abn(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_hcd_urb * urb, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_update_urb_state_abn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_update_urb_state_abn",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:1171",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590125584,
      "name": "dwc2_update_urb_state_abn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446744071594478253,
      "name": "dwc2_update_urb_state_abn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void dwc2_update_urb_state_abn(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_hcd_urb * urb, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_update_urb_state_abn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_update_urb_state_abn",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:1141",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591738608,
      "name": "dwc2_update_urb_state_abn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446744071596293789,
      "name": "dwc2_update_urb_state_abn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void dwc2_update_urb_state_abn(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_hcd_urb * urb, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_update_urb_state_abn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_update_urb_state_abn",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:1141",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592162144,
      "name": "dwc2_update_urb_state_abn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446744071596823642,
      "name": "dwc2_update_urb_state_abn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void dwc2_update_urb_state_abn(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_hcd_urb * urb, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_update_urb_state_abn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_update_urb_state_abn",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:1141",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592902800,
      "name": "dwc2_update_urb_state_abn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446744071597747246,
      "name": "dwc2_update_urb_state_abn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
  "name": "dwc2_update_urb_state_abn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500415480,
      "name": "dwc2_update_urb_state_abn",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:1171",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500415480,
      "name": "dwc2_update_urb_state_abn.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
void dwc2_update_urb_state_abn(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_hcd_urb * urb, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_update_urb_state_abn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232870340,
      "name": "dwc2_update_urb_state_abn",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:1171",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232870340,
      "name": "dwc2_update_urb_state_abn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
  "name": "dwc2_update_urb_state_abn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293755760,
      "name": "dwc2_update_urb_state_abn",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:1171",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293755760,
      "name": "dwc2_update_urb_state_abn.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
  "name": "dwc2_update_urb_state_abn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277305810,
      "name": "dwc2_update_urb_state_abn",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:1171",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277305810,
      "name": "dwc2_update_urb_state_abn.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
  "name": "dwc2_update_urb_state_abn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_update_urb_state_abn",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:1171",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587006128,
      "name": "dwc2_update_urb_state_abn.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071587014951,
      "name": "dwc2_update_urb_state_abn.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_update_urb_state_abn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_update_urb_state_abn",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:1171",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587254608,
      "name": "dwc2_update_urb_state_abn.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071587263431,
      "name": "dwc2_update_urb_state_abn.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
  "name": "dwc2_update_urb_state_abn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_update_urb_state_abn",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:1171",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587361376,
      "name": "dwc2_update_urb_state_abn.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071587370195,
      "name": "dwc2_update_urb_state_abn.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void dwc2_update_urb_state_abn(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_hcd_urb * urb, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void dwc2_update_urb_state_abn(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_hcd_urb * urb, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void dwc2_update_urb_state_abn(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_hcd_urb * urb, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```
</details>
</li>
</ul>
