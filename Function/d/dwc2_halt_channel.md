# Function: <code>dwc2_halt_channel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dwc2_halt_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_halt_channel",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585311904,
      "name": "dwc2_halt_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:794",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585311904,
      "name": "dwc2_halt_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void dwc2_halt_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_halt_channel",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585705536,
      "name": "dwc2_halt_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:785",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585705536,
      "name": "dwc2_halt_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
void dwc2_halt_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_halt_channel",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585894240,
      "name": "dwc2_halt_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:785",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585894240,
      "name": "dwc2_halt_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void dwc2_halt_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_halt_channel",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585976960,
      "name": "dwc2_halt_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:784",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585976960,
      "name": "dwc2_halt_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void dwc2_halt_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_halt_channel",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586420848,
      "name": "dwc2_halt_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:785",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586420848,
      "name": "dwc2_halt_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void dwc2_halt_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_halt_channel",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586684544,
      "name": "dwc2_halt_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:803",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586684544,
      "name": "dwc2_halt_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void dwc2_halt_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_halt_channel",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586841360,
      "name": "dwc2_halt_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:803",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586841360,
      "name": "dwc2_halt_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
void dwc2_halt_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_halt_channel",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587099712,
      "name": "dwc2_halt_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:803",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
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
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587099712,
      "name": "dwc2_halt_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
void dwc2_halt_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_halt_channel",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587300144,
      "name": "dwc2_halt_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:803",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
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
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587300144,
      "name": "dwc2_halt_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
void dwc2_halt_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_halt_channel",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588162308,
      "name": "dwc2_halt_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:803",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588156160,
      "name": "dwc2_halt_channel.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071588156336,
      "name": "dwc2_halt_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void dwc2_halt_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_halt_channel",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588201316,
      "name": "dwc2_halt_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:803",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588195152,
      "name": "dwc2_halt_channel.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071588195328,
      "name": "dwc2_halt_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void dwc2_halt_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_halt_channel",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588077712,
      "name": "dwc2_halt_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:803",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
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
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588077712,
      "name": "dwc2_halt_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
void dwc2_halt_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_halt_channel",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588710232,
      "name": "dwc2_halt_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:803",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
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
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588710176,
      "name": "dwc2_halt_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
    },
    {
      "addr": 18446744071592596751,
      "name": "dwc2_halt_channel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void dwc2_halt_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_halt_channel",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590127957,
      "name": "dwc2_halt_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:803",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
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
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590127888,
      "name": "dwc2_halt_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
    },
    {
      "addr": 18446744071594478996,
      "name": "dwc2_halt_channel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
void dwc2_halt_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_halt_channel",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591741461,
      "name": "dwc2_halt_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:773",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
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
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591741392,
      "name": "dwc2_halt_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
    },
    {
      "addr": 18446744071596294297,
      "name": "dwc2_halt_channel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
void dwc2_halt_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_halt_channel",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592164997,
      "name": "dwc2_halt_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:773",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
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
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592164928,
      "name": "dwc2_halt_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
    },
    {
      "addr": 18446744071596824150,
      "name": "dwc2_halt_channel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
void dwc2_halt_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_halt_channel",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592905653,
      "name": "dwc2_halt_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:773",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
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
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592905584,
      "name": "dwc2_halt_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
    },
    {
      "addr": 18446744071597747754,
      "name": "dwc2_halt_channel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
void dwc2_halt_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_halt_channel",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500416704,
      "name": "dwc2_halt_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:803",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
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
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500416704,
      "name": "dwc2_halt_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
void dwc2_halt_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_halt_channel",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232871584,
      "name": "dwc2_halt_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:803",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
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
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232871584,
      "name": "dwc2_halt_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
void dwc2_halt_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_halt_channel",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293758752,
      "name": "dwc2_halt_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:803",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
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
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293758752,
      "name": "dwc2_halt_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
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
void dwc2_halt_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_halt_channel",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277307672,
      "name": "dwc2_halt_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:803",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
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
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277307672,
      "name": "dwc2_halt_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
void dwc2_halt_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_halt_channel",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587006224,
      "name": "dwc2_halt_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:803",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
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
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587006224,
      "name": "dwc2_halt_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
void dwc2_halt_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_halt_channel",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587254704,
      "name": "dwc2_halt_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:803",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
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
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587254704,
      "name": "dwc2_halt_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
void dwc2_halt_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
```

```json
{
  "name": "dwc2_halt_channel",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587361472,
      "name": "dwc2_halt_channel",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:803",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
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
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587361472,
      "name": "dwc2_halt_channel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
void dwc2_halt_channel(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan, struct dwc2_qtd * qtd, enum dwc2_halt_status halt_status)
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
