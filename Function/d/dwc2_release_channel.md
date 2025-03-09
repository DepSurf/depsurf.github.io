# Function: <code>dwc2_release_channel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void dwc2_release_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_release_channel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585311360,
      "name": "dwc2_release_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:695",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585311360,
      "name": "dwc2_release_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 538
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
void dwc2_release_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_release_channel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585705040,
      "name": "dwc2_release_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:686",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585705040,
      "name": "dwc2_release_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 490
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
void dwc2_release_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_release_channel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585893744,
      "name": "dwc2_release_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:686",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585893744,
      "name": "dwc2_release_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 489
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
void dwc2_release_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_release_channel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585976496,
      "name": "dwc2_release_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:685",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585976496,
      "name": "dwc2_release_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
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
void dwc2_release_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_release_channel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586420384,
      "name": "dwc2_release_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:686",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586420384,
      "name": "dwc2_release_channel",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void dwc2_release_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_release_channel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586684064,
      "name": "dwc2_release_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:704",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586684064,
      "name": "dwc2_release_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
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
void dwc2_release_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_release_channel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586839808,
      "name": "dwc2_release_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:704",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586839808,
      "name": "dwc2_release_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
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
void dwc2_release_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_release_channel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587098208,
      "name": "dwc2_release_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:704",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587098208,
      "name": "dwc2_release_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 611
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
void dwc2_release_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_release_channel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587298640,
      "name": "dwc2_release_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:704",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587298640,
      "name": "dwc2_release_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 611
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
void dwc2_release_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_release_channel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588155552,
      "name": "dwc2_release_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:704",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588155552,
      "name": "dwc2_release_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
void dwc2_release_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_release_channel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588194544,
      "name": "dwc2_release_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:704",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588194544,
      "name": "dwc2_release_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
void dwc2_release_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_release_channel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588077104,
      "name": "dwc2_release_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:704",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588077104,
      "name": "dwc2_release_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
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
void dwc2_release_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_release_channel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_release_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:704",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588708544,
      "name": "dwc2_release_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 658
    },
    {
      "addr": 18446744071592596202,
      "name": "dwc2_release_channel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
void dwc2_release_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_release_channel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_release_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:704",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590126160,
      "name": "dwc2_release_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 697
    },
    {
      "addr": 18446744071594478396,
      "name": "dwc2_release_channel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
void dwc2_release_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_release_channel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_release_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:674",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591739248,
      "name": "dwc2_release_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 697
    },
    {
      "addr": 18446744071596293891,
      "name": "dwc2_release_channel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
void dwc2_release_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_release_channel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_release_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:674",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592162784,
      "name": "dwc2_release_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 698
    },
    {
      "addr": 18446744071596823744,
      "name": "dwc2_release_channel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
void dwc2_release_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_release_channel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_release_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:674",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592903440,
      "name": "dwc2_release_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 698
    },
    {
      "addr": 18446744071597747348,
      "name": "dwc2_release_channel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
void dwc2_release_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_release_channel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500416032,
      "name": "dwc2_release_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:704",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500416032,
      "name": "dwc2_release_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 672
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
void dwc2_release_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_release_channel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232871000,
      "name": "dwc2_release_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:704",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232871000,
      "name": "dwc2_release_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
void dwc2_release_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_release_channel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293757744,
      "name": "dwc2_release_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:704",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293757744,
      "name": "dwc2_release_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 996
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
void dwc2_release_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_release_channel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277306230,
      "name": "dwc2_release_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:704",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277306230,
      "name": "dwc2_release_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 636
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
void dwc2_release_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_release_channel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587004720,
      "name": "dwc2_release_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:704",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587004720,
      "name": "dwc2_release_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 611
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
void dwc2_release_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_release_channel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587253200,
      "name": "dwc2_release_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:704",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587253200,
      "name": "dwc2_release_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 611
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
void dwc2_release_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_release_channel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587359968,
      "name": "dwc2_release_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:704",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587359968,
      "name": "dwc2_release_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 611
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
void dwc2_release_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
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
