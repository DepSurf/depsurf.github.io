# Function: <code>dwc2_host_exit_clock_gating</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void dwc2_host_exit_clock_gating(struct dwc2_hsotg * hsotg, int rem_wakeup)
```

```json
{
  "name": "dwc2_host_exit_clock_gating",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588071120,
      "name": "dwc2_host_exit_clock_gating",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5939",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_port_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588071120,
      "name": "dwc2_host_exit_clock_gating",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void dwc2_host_exit_clock_gating(struct dwc2_hsotg * hsotg, int rem_wakeup)
```

```json
{
  "name": "dwc2_host_exit_clock_gating",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_host_exit_clock_gating",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5944",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_port_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592594286,
      "name": "dwc2_host_exit_clock_gating.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
    },
    {
      "addr": 18446744071588700768,
      "name": "dwc2_host_exit_clock_gating",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 655
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
void dwc2_host_exit_clock_gating(struct dwc2_hsotg * hsotg, int rem_wakeup)
```

```json
{
  "name": "dwc2_host_exit_clock_gating",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_host_exit_clock_gating",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5940",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_port_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594476230,
      "name": "dwc2_host_exit_clock_gating.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
    },
    {
      "addr": 18446744071590118496,
      "name": "dwc2_host_exit_clock_gating",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
void dwc2_host_exit_clock_gating(struct dwc2_hsotg * hsotg, int rem_wakeup)
```

```json
{
  "name": "dwc2_host_exit_clock_gating",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_host_exit_clock_gating",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5913",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_port_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596292199,
      "name": "dwc2_host_exit_clock_gating.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
    },
    {
      "addr": 18446744071591730960,
      "name": "dwc2_host_exit_clock_gating",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
void dwc2_host_exit_clock_gating(struct dwc2_hsotg * hsotg, int rem_wakeup)
```

```json
{
  "name": "dwc2_host_exit_clock_gating",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_host_exit_clock_gating",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5913",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_port_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596822043,
      "name": "dwc2_host_exit_clock_gating.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
    },
    {
      "addr": 18446744071592154384,
      "name": "dwc2_host_exit_clock_gating",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
void dwc2_host_exit_clock_gating(struct dwc2_hsotg * hsotg, int rem_wakeup)
```

```json
{
  "name": "dwc2_host_exit_clock_gating",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_host_exit_clock_gating",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5913",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_port_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597745647,
      "name": "dwc2_host_exit_clock_gating.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
    },
    {
      "addr": 18446744071592895008,
      "name": "dwc2_host_exit_clock_gating",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void dwc2_host_exit_clock_gating(struct dwc2_hsotg * hsotg, int rem_wakeup)
```
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
