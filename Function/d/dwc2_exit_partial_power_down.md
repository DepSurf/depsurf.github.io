# Function: <code>dwc2_exit_partial_power_down</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int dwc2_exit_partial_power_down(struct dwc2_hsotg * hsotg, bool restore)
```

```json
{
  "name": "dwc2_exit_partial_power_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586643648,
      "name": "dwc2_exit_partial_power_down",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:136",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586643648,
      "name": "dwc2_exit_partial_power_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int dwc2_exit_partial_power_down(struct dwc2_hsotg * hsotg, bool restore)
```

```json
{
  "name": "dwc2_exit_partial_power_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586793168,
      "name": "dwc2_exit_partial_power_down",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:136",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586793168,
      "name": "dwc2_exit_partial_power_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
int dwc2_exit_partial_power_down(struct dwc2_hsotg * hsotg, bool restore)
```

```json
{
  "name": "dwc2_exit_partial_power_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_exit_partial_power_down",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:136",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587054178,
      "name": "dwc2_exit_partial_power_down.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071587049392,
      "name": "dwc2_exit_partial_power_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int dwc2_exit_partial_power_down(struct dwc2_hsotg * hsotg, bool restore)
```

```json
{
  "name": "dwc2_exit_partial_power_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_exit_partial_power_down",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:136",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587254578,
      "name": "dwc2_exit_partial_power_down.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071587249792,
      "name": "dwc2_exit_partial_power_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int dwc2_exit_partial_power_down(struct dwc2_hsotg * hsotg, bool restore)
```

```json
{
  "name": "dwc2_exit_partial_power_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_exit_partial_power_down",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:136",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_session_req_intr",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588109080,
      "name": "dwc2_exit_partial_power_down.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071588104480,
      "name": "dwc2_exit_partial_power_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int dwc2_exit_partial_power_down(struct dwc2_hsotg * hsotg, bool restore)
```

```json
{
  "name": "dwc2_exit_partial_power_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_exit_partial_power_down",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:136",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_session_req_intr",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591554074,
      "name": "dwc2_exit_partial_power_down.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071588146240,
      "name": "dwc2_exit_partial_power_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int dwc2_exit_partial_power_down(struct dwc2_hsotg * hsotg, int rem_wakeup, bool restore)
```

```json
{
  "name": "dwc2_exit_partial_power_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588028192,
      "name": "dwc2_exit_partial_power_down",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:137",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_port_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588028192,
      "name": "dwc2_exit_partial_power_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int dwc2_exit_partial_power_down(struct dwc2_hsotg * hsotg, int rem_wakeup, bool restore)
```

```json
{
  "name": "dwc2_exit_partial_power_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588645504,
      "name": "dwc2_exit_partial_power_down",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:137",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_port_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588645504,
      "name": "dwc2_exit_partial_power_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int dwc2_exit_partial_power_down(struct dwc2_hsotg * hsotg, int rem_wakeup, bool restore)
```

```json
{
  "name": "dwc2_exit_partial_power_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590062368,
      "name": "dwc2_exit_partial_power_down",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:137",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_port_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590062368,
      "name": "dwc2_exit_partial_power_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int dwc2_exit_partial_power_down(struct dwc2_hsotg * hsotg, int rem_wakeup, bool restore)
```

```json
{
  "name": "dwc2_exit_partial_power_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591669776,
      "name": "dwc2_exit_partial_power_down",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:107",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_port_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591669776,
      "name": "dwc2_exit_partial_power_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int dwc2_exit_partial_power_down(struct dwc2_hsotg * hsotg, int rem_wakeup, bool restore)
```

```json
{
  "name": "dwc2_exit_partial_power_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592092608,
      "name": "dwc2_exit_partial_power_down",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:107",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_port_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592092608,
      "name": "dwc2_exit_partial_power_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int dwc2_exit_partial_power_down(struct dwc2_hsotg * hsotg, int rem_wakeup, bool restore)
```

```json
{
  "name": "dwc2_exit_partial_power_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592833040,
      "name": "dwc2_exit_partial_power_down",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:107",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_port_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592833040,
      "name": "dwc2_exit_partial_power_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int dwc2_exit_partial_power_down(struct dwc2_hsotg * hsotg, bool restore)
```

```json
{
  "name": "dwc2_exit_partial_power_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500357312,
      "name": "dwc2_exit_partial_power_down",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:136",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500357312,
      "name": "dwc2_exit_partial_power_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
int dwc2_exit_partial_power_down(struct dwc2_hsotg * hsotg, bool restore)
```

```json
{
  "name": "dwc2_exit_partial_power_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232815840,
      "name": "dwc2_exit_partial_power_down",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:136",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232815840,
      "name": "dwc2_exit_partial_power_down",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int dwc2_exit_partial_power_down(struct dwc2_hsotg * hsotg, bool restore)
```

```json
{
  "name": "dwc2_exit_partial_power_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293665504,
      "name": "dwc2_exit_partial_power_down",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:136",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293665504,
      "name": "dwc2_exit_partial_power_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 928
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
int dwc2_exit_partial_power_down(struct dwc2_hsotg * hsotg, bool restore)
```

```json
{
  "name": "dwc2_exit_partial_power_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277240432,
      "name": "dwc2_exit_partial_power_down",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:136",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277240432,
      "name": "dwc2_exit_partial_power_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 668
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
int dwc2_exit_partial_power_down(struct dwc2_hsotg * hsotg, bool restore)
```

```json
{
  "name": "dwc2_exit_partial_power_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_exit_partial_power_down",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:136",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586960658,
      "name": "dwc2_exit_partial_power_down.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071586955872,
      "name": "dwc2_exit_partial_power_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int dwc2_exit_partial_power_down(struct dwc2_hsotg * hsotg, bool restore)
```

```json
{
  "name": "dwc2_exit_partial_power_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_exit_partial_power_down",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:136",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587209138,
      "name": "dwc2_exit_partial_power_down.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071587204352,
      "name": "dwc2_exit_partial_power_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int dwc2_exit_partial_power_down(struct dwc2_hsotg * hsotg, bool restore)
```

```json
{
  "name": "dwc2_exit_partial_power_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_exit_partial_power_down",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:136",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587316210,
      "name": "dwc2_exit_partial_power_down.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071587311424,
      "name": "dwc2_exit_partial_power_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int dwc2_exit_partial_power_down(struct dwc2_hsotg * hsotg, bool restore)
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int rem_wakeup</code>
</li>
<li>
<b>Param reordered. </b>
<code>hsotg, restore</code> ➡️ <code>hsotg, rem_wakeup, restore</code>
</li>
</ul>
</details>
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
int dwc2_exit_partial_power_down(struct dwc2_hsotg * hsotg, bool restore)
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
