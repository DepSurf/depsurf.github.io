# Function: <code>dwc2_host_complete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void dwc2_host_complete(struct dwc2_hsotg * hsotg, struct dwc2_qtd * qtd, int status)
```

```json
{
  "name": "dwc2_host_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585306944,
      "name": "dwc2_host_complete",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2205",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585306944,
      "name": "dwc2_host_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
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
void dwc2_host_complete(struct dwc2_hsotg * hsotg, struct dwc2_qtd * qtd, int status)
```

```json
{
  "name": "dwc2_host_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585699776,
      "name": "dwc2_host_complete",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:4175",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_update_isoc_urb_state",
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
      "addr": 18446744071585699776,
      "name": "dwc2_host_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
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
void dwc2_host_complete(struct dwc2_hsotg * hsotg, struct dwc2_qtd * qtd, int status)
```

```json
{
  "name": "dwc2_host_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585888560,
      "name": "dwc2_host_complete",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:4177",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_update_isoc_urb_state",
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
      "addr": 18446744071585888560,
      "name": "dwc2_host_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
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
void dwc2_host_complete(struct dwc2_hsotg * hsotg, struct dwc2_qtd * qtd, int status)
```

```json
{
  "name": "dwc2_host_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585971232,
      "name": "dwc2_host_complete",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:4205",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_update_isoc_urb_state",
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
      "addr": 18446744071585971232,
      "name": "dwc2_host_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 526
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
void dwc2_host_complete(struct dwc2_hsotg * hsotg, struct dwc2_qtd * qtd, int status)
```

```json
{
  "name": "dwc2_host_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586414992,
      "name": "dwc2_host_complete",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:4214",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_update_isoc_urb_state",
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
      "addr": 18446744071586414992,
      "name": "dwc2_host_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 526
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
void dwc2_host_complete(struct dwc2_hsotg * hsotg, struct dwc2_qtd * qtd, int status)
```

```json
{
  "name": "dwc2_host_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586677104,
      "name": "dwc2_host_complete",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:4273",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_update_isoc_urb_state",
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
      "addr": 18446744071586677104,
      "name": "dwc2_host_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
void dwc2_host_complete(struct dwc2_hsotg * hsotg, struct dwc2_qtd * qtd, int status)
```

```json
{
  "name": "dwc2_host_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586832384,
      "name": "dwc2_host_complete",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:4273",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_update_isoc_urb_state",
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
      "addr": 18446744071586832384,
      "name": "dwc2_host_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
void dwc2_host_complete(struct dwc2_hsotg * hsotg, struct dwc2_qtd * qtd, int status)
```

```json
{
  "name": "dwc2_host_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_host_complete",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:4094",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_update_isoc_urb_state",
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
      "addr": 18446744071587097832,
      "name": "dwc2_host_complete.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071587089456,
      "name": "dwc2_host_complete",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void dwc2_host_complete(struct dwc2_hsotg * hsotg, struct dwc2_qtd * qtd, int status)
```

```json
{
  "name": "dwc2_host_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587289952,
      "name": "dwc2_host_complete",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:4094",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_update_isoc_urb_state",
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
      "addr": 18446744071587289952,
      "name": "dwc2_host_complete",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void dwc2_host_complete(struct dwc2_hsotg * hsotg, struct dwc2_qtd * qtd, int status)
```

```json
{
  "name": "dwc2_host_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588145552,
      "name": "dwc2_host_complete",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:4094",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588145552,
      "name": "dwc2_host_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
void dwc2_host_complete(struct dwc2_hsotg * hsotg, struct dwc2_qtd * qtd, int status)
```

```json
{
  "name": "dwc2_host_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588186096,
      "name": "dwc2_host_complete",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:4095",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588186096,
      "name": "dwc2_host_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
void dwc2_host_complete(struct dwc2_hsotg * hsotg, struct dwc2_qtd * qtd, int status)
```

```json
{
  "name": "dwc2_host_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588061440,
      "name": "dwc2_host_complete",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:4146",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588061440,
      "name": "dwc2_host_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void dwc2_host_complete(struct dwc2_hsotg * hsotg, struct dwc2_qtd * qtd, int status)
```

```json
{
  "name": "dwc2_host_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588688192,
      "name": "dwc2_host_complete",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:4146",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588688192,
      "name": "dwc2_host_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void dwc2_host_complete(struct dwc2_hsotg * hsotg, struct dwc2_qtd * qtd, int status)
```

```json
{
  "name": "dwc2_host_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590106688,
      "name": "dwc2_host_complete",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:4142",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590106688,
      "name": "dwc2_host_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void dwc2_host_complete(struct dwc2_hsotg * hsotg, struct dwc2_qtd * qtd, int status)
```

```json
{
  "name": "dwc2_host_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591718256,
      "name": "dwc2_host_complete",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:4113",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591718256,
      "name": "dwc2_host_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 558
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void dwc2_host_complete(struct dwc2_hsotg * hsotg, struct dwc2_qtd * qtd, int status)
```

```json
{
  "name": "dwc2_host_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592141616,
      "name": "dwc2_host_complete",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:4113",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592141616,
      "name": "dwc2_host_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void dwc2_host_complete(struct dwc2_hsotg * hsotg, struct dwc2_qtd * qtd, int status)
```

```json
{
  "name": "dwc2_host_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592882144,
      "name": "dwc2_host_complete",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:4113",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592882144,
      "name": "dwc2_host_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
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
void dwc2_host_complete(struct dwc2_hsotg * hsotg, struct dwc2_qtd * qtd, int status)
```

```json
{
  "name": "dwc2_host_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500405640,
      "name": "dwc2_host_complete",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:4094",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_update_isoc_urb_state",
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
      "addr": 18446603336500405640,
      "name": "dwc2_host_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
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
void dwc2_host_complete(struct dwc2_hsotg * hsotg, struct dwc2_qtd * qtd, int status)
```

```json
{
  "name": "dwc2_host_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232861436,
      "name": "dwc2_host_complete",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:4094",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_update_isoc_urb_state",
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
      "addr": 3232861436,
      "name": "dwc2_host_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void dwc2_host_complete(struct dwc2_hsotg * hsotg, struct dwc2_qtd * qtd, int status)
```

```json
{
  "name": "dwc2_host_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293741264,
      "name": "dwc2_host_complete",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:4094",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_update_isoc_urb_state",
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
      "addr": 13835058055293741264,
      "name": "dwc2_host_complete",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void dwc2_host_complete(struct dwc2_hsotg * hsotg, struct dwc2_qtd * qtd, int status)
```

```json
{
  "name": "dwc2_host_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277294912,
      "name": "dwc2_host_complete",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:4094",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_update_isoc_urb_state",
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
      "addr": 18446743936277294912,
      "name": "dwc2_host_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
void dwc2_host_complete(struct dwc2_hsotg * hsotg, struct dwc2_qtd * qtd, int status)
```

```json
{
  "name": "dwc2_host_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586996032,
      "name": "dwc2_host_complete",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:4094",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_update_isoc_urb_state",
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
      "addr": 18446744071586996032,
      "name": "dwc2_host_complete",
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void dwc2_host_complete(struct dwc2_hsotg * hsotg, struct dwc2_qtd * qtd, int status)
```

```json
{
  "name": "dwc2_host_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587244512,
      "name": "dwc2_host_complete",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:4094",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_update_isoc_urb_state",
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
      "addr": 18446744071587244512,
      "name": "dwc2_host_complete",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void dwc2_host_complete(struct dwc2_hsotg * hsotg, struct dwc2_qtd * qtd, int status)
```

```json
{
  "name": "dwc2_host_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587351280,
      "name": "dwc2_host_complete",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:4094",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_update_isoc_urb_state",
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
      "addr": 18446744071587351280,
      "name": "dwc2_host_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
void dwc2_host_complete(struct dwc2_hsotg * hsotg, struct dwc2_qtd * qtd, int status)
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
