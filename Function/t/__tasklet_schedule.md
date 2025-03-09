# Function: <code>__tasklet_schedule</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __tasklet_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579391328,
      "name": "__tasklet_schedule",
      "external": true,
      "loc": "kernel/softirq.c:449",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:setledstate",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "net/core/flow.c:flow_cache_flush_per_cpu",
        "net/ipv4/tcp_output.c:tcp_wfree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579391328,
      "name": "__tasklet_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void __tasklet_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579403840,
      "name": "__tasklet_schedule",
      "external": true,
      "loc": "kernel/softirq.c:449",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:setledstate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "net/core/flow.c:flow_cache_flush_per_cpu",
        "net/ipv4/tcp_output.c:tcp_wfree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579403840,
      "name": "__tasklet_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void __tasklet_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579423936,
      "name": "__tasklet_schedule",
      "external": true,
      "loc": "kernel/softirq.c:463",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:setledstate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "net/core/flow.c:flow_cache_flush_per_cpu",
        "net/ipv4/tcp_output.c:tcp_wfree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579423936,
      "name": "__tasklet_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
void __tasklet_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579411936,
      "name": "__tasklet_schedule",
      "external": true,
      "loc": "kernel/softirq.c:463",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:setledstate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "net/core/flow.c:flow_cache_flush_per_cpu",
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_wfree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579411936,
      "name": "__tasklet_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
void __tasklet_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579439472,
      "name": "__tasklet_schedule",
      "external": true,
      "loc": "kernel/softirq.c:463",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:setledstate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete",
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579439472,
      "name": "__tasklet_schedule",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __tasklet_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579454704,
      "name": "__tasklet_schedule",
      "external": true,
      "loc": "kernel/softirq.c:486",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:setledstate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579454704,
      "name": "__tasklet_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void __tasklet_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579488512,
      "name": "__tasklet_schedule",
      "external": true,
      "loc": "kernel/softirq.c:487",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:setledstate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579488512,
      "name": "__tasklet_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void __tasklet_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579506656,
      "name": "__tasklet_schedule",
      "external": true,
      "loc": "kernel/softirq.c:487",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:setledstate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579506656,
      "name": "__tasklet_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void __tasklet_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579532704,
      "name": "__tasklet_schedule",
      "external": true,
      "loc": "kernel/softirq.c:487",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:setledstate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579532704,
      "name": "__tasklet_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void __tasklet_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579562928,
      "name": "__tasklet_schedule",
      "external": true,
      "loc": "kernel/softirq.c:514",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/resend.c:check_irq_resend",
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:vt_set_led_state",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579562928,
      "name": "__tasklet_schedule",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __tasklet_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579544416,
      "name": "__tasklet_schedule",
      "external": true,
      "loc": "kernel/softirq.c:518",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/resend.c:check_irq_resend",
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:vt_set_led_state",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579544416,
      "name": "__tasklet_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void __tasklet_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579549424,
      "name": "__tasklet_schedule",
      "external": true,
      "loc": "kernel/softirq.c:735",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/resend.c:check_irq_resend",
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:vt_set_led_state",
        "drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579549424,
      "name": "__tasklet_schedule",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void __tasklet_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579622576,
      "name": "__tasklet_schedule",
      "external": true,
      "loc": "kernel/softirq.c:734",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/resend.c:check_irq_resend",
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:vt_set_led_state",
        "drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579622576,
      "name": "__tasklet_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void __tasklet_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579716848,
      "name": "__tasklet_schedule",
      "external": true,
      "loc": "kernel/softirq.c:748",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/resend.c:check_irq_resend",
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:vt_set_led_state",
        "drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_giveback_urb_bh",
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579716848,
      "name": "__tasklet_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void __tasklet_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579843872,
      "name": "__tasklet_schedule",
      "external": true,
      "loc": "kernel/softirq.c:748",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/resend.c:check_irq_resend",
        "drivers/dma/hsu/hsu.c:hsu_dma_do_irq",
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_init",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:vt_set_led_state",
        "drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_giveback_urb_bh",
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete",
        "net/ipv4/tcp_output.c:tcp_wfree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579843872,
      "name": "__tasklet_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void __tasklet_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579894096,
      "name": "__tasklet_schedule",
      "external": true,
      "loc": "kernel/softirq.c:730",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/resend.c:check_irq_resend",
        "drivers/dma/hsu/hsu.c:hsu_dma_do_irq",
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_init",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:vt_set_led_state",
        "drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_giveback_urb_bh",
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete",
        "net/ipv4/tcp_output.c:tcp_wfree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579894096,
      "name": "__tasklet_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void __tasklet_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579932784,
      "name": "__tasklet_schedule",
      "external": true,
      "loc": "kernel/softirq.c:730",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/resend.c:check_irq_resend",
        "drivers/dma/hsu/hsu.c:hsu_dma_do_irq",
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_init",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:vt_set_led_state",
        "drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_giveback_urb_bh",
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete",
        "net/ipv4/tcp_output.c:tcp_wfree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579932784,
      "name": "__tasklet_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void __tasklet_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490677792,
      "name": "__tasklet_schedule",
      "external": true,
      "loc": "kernel/softirq.c:487",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/resend.c:check_irq_resend",
        "drivers/dma/amba-pl08x.c:pl08x_irq",
        "drivers/dma/amba-pl08x.c:pl08x_irq",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_callback",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_callback",
        "drivers/dma/mv_xor.c:mv_xor_interrupt_handler",
        "drivers/dma/mv_xor.c:mv_xor_prep_dma_xor",
        "drivers/dma/mv_xor.c:mv_chan_slot_cleanup",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_prep_sw_desc",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_interrupt_handler",
        "drivers/dma/mxs-dma.c:mxs_dma_int_handler",
        "drivers/dma/ipu/ipu_idmac.c:idmac_free_chan_resources",
        "drivers/dma/ipu/ipu_idmac.c:idmac_prep_slave_sg",
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:setledstate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490677792,
      "name": "__tasklet_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __tasklet_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224748624,
      "name": "__tasklet_schedule",
      "external": true,
      "loc": "kernel/softirq.c:487",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/resend.c:check_irq_resend",
        "drivers/dma/amba-pl08x.c:pl08x_irq",
        "drivers/dma/amba-pl08x.c:pl08x_irq",
        "drivers/dma/mv_xor.c:mv_xor_interrupt_handler",
        "drivers/dma/mv_xor.c:mv_xor_prep_dma_xor",
        "drivers/dma/mv_xor.c:mv_chan_slot_cleanup",
        "drivers/dma/mxs-dma.c:mxs_dma_int_handler",
        "drivers/dma/ipu/ipu_idmac.c:idmac_free_chan_resources",
        "drivers/dma/ipu/ipu_idmac.c:idmac_prep_slave_sg",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_isr",
        "drivers/dma/ti/edma.c:dma_irq_handler",
        "drivers/dma/ti/edma.c:dma_irq_handler",
        "drivers/dma/ti/omap-dma.c:omap_dma_callback",
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:setledstate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224748624,
      "name": "__tasklet_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void __tasklet_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283501568,
      "name": "__tasklet_schedule",
      "external": true,
      "loc": "kernel/softirq.c:487",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/resend.c:check_irq_resend",
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:setledstate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283501568,
      "name": "__tasklet_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void __tasklet_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271414350,
      "name": "__tasklet_schedule",
      "external": true,
      "loc": "kernel/softirq.c:487",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_init",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:setledstate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271414350,
      "name": "__tasklet_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void __tasklet_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579506368,
      "name": "__tasklet_schedule",
      "external": true,
      "loc": "kernel/softirq.c:487",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:setledstate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579506368,
      "name": "__tasklet_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void __tasklet_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579435168,
      "name": "__tasklet_schedule",
      "external": true,
      "loc": "kernel/softirq.c:487",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:setledstate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete",
        "drivers/hv/vmbus_drv.c:vmbus_isr",
        "drivers/hv/vmbus_drv.c:vmbus_isr",
        "drivers/hv/connection.c:vmbus_on_event",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579435168,
      "name": "__tasklet_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void __tasklet_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579506288,
      "name": "__tasklet_schedule",
      "external": true,
      "loc": "kernel/softirq.c:487",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:setledstate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579506288,
      "name": "__tasklet_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void __tasklet_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579538992,
      "name": "__tasklet_schedule",
      "external": true,
      "loc": "kernel/softirq.c:487",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:setledstate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579538992,
      "name": "__tasklet_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
