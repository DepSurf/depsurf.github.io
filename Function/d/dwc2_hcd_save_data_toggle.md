# Function: <code>dwc2_hcd_save_data_toggle</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dwc2_hcd_save_data_toggle(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd)
```

```json
{
  "name": "dwc2_hcd_save_data_toggle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585314974,
      "name": "dwc2_hcd_save_data_toggle",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_intr.c:513",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585318320,
      "name": "dwc2_hcd_save_data_toggle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void dwc2_hcd_save_data_toggle(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd)
```

```json
{
  "name": "dwc2_hcd_save_data_toggle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585708608,
      "name": "dwc2_hcd_save_data_toggle",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_intr.c:528",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585708608,
      "name": "dwc2_hcd_save_data_toggle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void dwc2_hcd_save_data_toggle(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd)
```

```json
{
  "name": "dwc2_hcd_save_data_toggle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585897280,
      "name": "dwc2_hcd_save_data_toggle",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_intr.c:528",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585897280,
      "name": "dwc2_hcd_save_data_toggle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void dwc2_hcd_save_data_toggle(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd)
```

```json
{
  "name": "dwc2_hcd_save_data_toggle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585979920,
      "name": "dwc2_hcd_save_data_toggle",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_intr.c:527",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585979920,
      "name": "dwc2_hcd_save_data_toggle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void dwc2_hcd_save_data_toggle(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd)
```

```json
{
  "name": "dwc2_hcd_save_data_toggle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586423856,
      "name": "dwc2_hcd_save_data_toggle",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_intr.c:528",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586423856,
      "name": "dwc2_hcd_save_data_toggle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void dwc2_hcd_save_data_toggle(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd)
```

```json
{
  "name": "dwc2_hcd_save_data_toggle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586687584,
      "name": "dwc2_hcd_save_data_toggle",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_intr.c:540",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586687584,
      "name": "dwc2_hcd_save_data_toggle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void dwc2_hcd_save_data_toggle(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd)
```

```json
{
  "name": "dwc2_hcd_save_data_toggle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586843680,
      "name": "dwc2_hcd_save_data_toggle",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_intr.c:540",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586843680,
      "name": "dwc2_hcd_save_data_toggle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void dwc2_hcd_save_data_toggle(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd)
```

```json
{
  "name": "dwc2_hcd_save_data_toggle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587101616,
      "name": "dwc2_hcd_save_data_toggle",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_intr.c:540",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587101616,
      "name": "dwc2_hcd_save_data_toggle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void dwc2_hcd_save_data_toggle(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd)
```

```json
{
  "name": "dwc2_hcd_save_data_toggle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587302048,
      "name": "dwc2_hcd_save_data_toggle",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_intr.c:540",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587302048,
      "name": "dwc2_hcd_save_data_toggle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void dwc2_hcd_save_data_toggle(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd)
```

```json
{
  "name": "dwc2_hcd_save_data_toggle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588159408,
      "name": "dwc2_hcd_save_data_toggle",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_intr.c:540",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588159408,
      "name": "dwc2_hcd_save_data_toggle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void dwc2_hcd_save_data_toggle(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd)
```

```json
{
  "name": "dwc2_hcd_save_data_toggle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588198416,
      "name": "dwc2_hcd_save_data_toggle",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_intr.c:540",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588198416,
      "name": "dwc2_hcd_save_data_toggle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void dwc2_hcd_save_data_toggle(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd)
```

```json
{
  "name": "dwc2_hcd_save_data_toggle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588081568,
      "name": "dwc2_hcd_save_data_toggle",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_intr.c:540",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588081568,
      "name": "dwc2_hcd_save_data_toggle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void dwc2_hcd_save_data_toggle(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd)
```

```json
{
  "name": "dwc2_hcd_save_data_toggle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hcd_save_data_toggle",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_intr.c:540",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592597559,
      "name": "dwc2_hcd_save_data_toggle.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071588713024,
      "name": "dwc2_hcd_save_data_toggle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void dwc2_hcd_save_data_toggle(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd)
```

```json
{
  "name": "dwc2_hcd_save_data_toggle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hcd_save_data_toggle",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_intr.c:540",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594480000,
      "name": "dwc2_hcd_save_data_toggle.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071590130752,
      "name": "dwc2_hcd_save_data_toggle",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void dwc2_hcd_save_data_toggle(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd)
```

```json
{
  "name": "dwc2_hcd_save_data_toggle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hcd_save_data_toggle",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_intr.c:510",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596295301,
      "name": "dwc2_hcd_save_data_toggle.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071591744368,
      "name": "dwc2_hcd_save_data_toggle",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void dwc2_hcd_save_data_toggle(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd)
```

```json
{
  "name": "dwc2_hcd_save_data_toggle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hcd_save_data_toggle",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_intr.c:510",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596825154,
      "name": "dwc2_hcd_save_data_toggle.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071592167904,
      "name": "dwc2_hcd_save_data_toggle",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void dwc2_hcd_save_data_toggle(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd)
```

```json
{
  "name": "dwc2_hcd_save_data_toggle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hcd_save_data_toggle",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_intr.c:510",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597748758,
      "name": "dwc2_hcd_save_data_toggle.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071592908560,
      "name": "dwc2_hcd_save_data_toggle",
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
void dwc2_hcd_save_data_toggle(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd)
```

```json
{
  "name": "dwc2_hcd_save_data_toggle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500419600,
      "name": "dwc2_hcd_save_data_toggle",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_intr.c:540",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500419600,
      "name": "dwc2_hcd_save_data_toggle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void dwc2_hcd_save_data_toggle(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd)
```

```json
{
  "name": "dwc2_hcd_save_data_toggle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232874172,
      "name": "dwc2_hcd_save_data_toggle",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_intr.c:540",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232874172,
      "name": "dwc2_hcd_save_data_toggle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void dwc2_hcd_save_data_toggle(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd)
```

```json
{
  "name": "dwc2_hcd_save_data_toggle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293761888,
      "name": "dwc2_hcd_save_data_toggle",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_intr.c:540",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293761888,
      "name": "dwc2_hcd_save_data_toggle",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void dwc2_hcd_save_data_toggle(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd)
```

```json
{
  "name": "dwc2_hcd_save_data_toggle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277309894,
      "name": "dwc2_hcd_save_data_toggle",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_intr.c:540",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277309894,
      "name": "dwc2_hcd_save_data_toggle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void dwc2_hcd_save_data_toggle(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd)
```

```json
{
  "name": "dwc2_hcd_save_data_toggle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587008128,
      "name": "dwc2_hcd_save_data_toggle",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_intr.c:540",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587008128,
      "name": "dwc2_hcd_save_data_toggle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void dwc2_hcd_save_data_toggle(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd)
```

```json
{
  "name": "dwc2_hcd_save_data_toggle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587256608,
      "name": "dwc2_hcd_save_data_toggle",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_intr.c:540",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587256608,
      "name": "dwc2_hcd_save_data_toggle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void dwc2_hcd_save_data_toggle(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd)
```

```json
{
  "name": "dwc2_hcd_save_data_toggle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587363376,
      "name": "dwc2_hcd_save_data_toggle",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_intr.c:540",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587363376,
      "name": "dwc2_hcd_save_data_toggle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void dwc2_hcd_save_data_toggle(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, int chnum, struct dwc2_qtd * qtd)
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
