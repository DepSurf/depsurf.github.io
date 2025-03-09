# Function: <code>queue_command</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int queue_command(struct xhci_hcd * xhci, struct xhci_command * cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed)
```

```json
{
  "name": "queue_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585493552,
      "name": "queue_command",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3994",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_slot_control",
        "drivers/usb/host/xhci-ring.c:xhci_queue_address_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context",
        "drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585493552,
      "name": "queue_command",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int queue_command(struct xhci_hcd * xhci, struct xhci_command * cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed)
```

```json
{
  "name": "queue_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585888656,
      "name": "queue_command",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3892",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context",
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_address_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_slot_control",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585888656,
      "name": "queue_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
int queue_command(struct xhci_hcd * xhci, struct xhci_command * cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed)
```

```json
{
  "name": "queue_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586077760,
      "name": "queue_command",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3792",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context",
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_address_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_slot_control",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586077760,
      "name": "queue_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
int queue_command(struct xhci_hcd * xhci, struct xhci_command * cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed)
```

```json
{
  "name": "queue_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586161984,
      "name": "queue_command",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3892",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context",
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_address_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_slot_control",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586161984,
      "name": "queue_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
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
int queue_command(struct xhci_hcd * xhci, struct xhci_command * cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed)
```

```json
{
  "name": "queue_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586606976,
      "name": "queue_command",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3896",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context",
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_address_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_slot_control",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586606976,
      "name": "queue_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 565
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
int queue_command(struct xhci_hcd * xhci, struct xhci_command * cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed)
```

```json
{
  "name": "queue_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586872480,
      "name": "queue_command",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3815",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context",
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_address_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_slot_control",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586872480,
      "name": "queue_command",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int queue_command(struct xhci_hcd * xhci, struct xhci_command * cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed)
```

```json
{
  "name": "queue_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587027824,
      "name": "queue_command",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3879",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context",
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_address_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_slot_control",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587027824,
      "name": "queue_command",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int queue_command(struct xhci_hcd * xhci, struct xhci_command * cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed)
```

```json
{
  "name": "queue_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "queue_command",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3945",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context",
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_address_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_slot_control",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587291760,
      "name": "queue_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
    },
    {
      "addr": 18446744071587311754,
      "name": "queue_command.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
int queue_command(struct xhci_hcd * xhci, struct xhci_command * cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed)
```

```json
{
  "name": "queue_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "queue_command",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3974",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context",
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_address_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_slot_control",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587492704,
      "name": "queue_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
    },
    {
      "addr": 18446744071587513012,
      "name": "queue_command.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
int queue_command(struct xhci_hcd * xhci, struct xhci_command * cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed)
```

```json
{
  "name": "queue_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "queue_command",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:4020",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context",
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_address_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_slot_control",
        "drivers/usb/host/xhci-ring.c:xhci_cleanup_halted_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_cleanup_halted_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588353984,
      "name": "queue_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    },
    {
      "addr": 18446744071588375824,
      "name": "queue_command.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
int queue_command(struct xhci_hcd * xhci, struct xhci_command * cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed)
```

```json
{
  "name": "queue_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "queue_command",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:4049",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context",
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_address_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_slot_control",
        "drivers/usb/host/xhci-ring.c:xhci_cleanup_halted_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_cleanup_halted_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588385232,
      "name": "queue_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    },
    {
      "addr": 18446744071591566418,
      "name": "queue_command.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
int queue_command(struct xhci_hcd * xhci, struct xhci_command * cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed)
```

```json
{
  "name": "queue_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "queue_command",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:4243",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context",
        "drivers/usb/host/xhci-ring.c:xhci_queue_configure_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_address_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_slot_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588266016,
      "name": "queue_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    },
    {
      "addr": 18446744071591509059,
      "name": "queue_command.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
int queue_command(struct xhci_hcd * xhci, struct xhci_command * cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed)
```

```json
{
  "name": "queue_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "queue_command",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:4313",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context",
        "drivers/usb/host/xhci-ring.c:xhci_queue_configure_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_address_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_slot_control",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588917008,
      "name": "queue_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    },
    {
      "addr": 18446744071592610519,
      "name": "queue_command.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
int queue_command(struct xhci_hcd * xhci, struct xhci_command * cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed)
```

```json
{
  "name": "queue_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "queue_command",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:4248",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context",
        "drivers/usb/host/xhci-ring.c:xhci_queue_configure_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_address_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_slot_control",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590348128,
      "name": "queue_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
    },
    {
      "addr": 18446744071594493532,
      "name": "queue_command.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int queue_command(struct xhci_hcd * xhci, struct xhci_command * cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed)
```

```json
{
  "name": "queue_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591978112,
      "name": "queue_command",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:4255",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context",
        "drivers/usb/host/xhci-ring.c:xhci_queue_configure_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_address_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_slot_control",
        "drivers/usb/host/xhci-ring.c:xhci_handle_halted_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591978112,
      "name": "queue_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
int queue_command(struct xhci_hcd * xhci, struct xhci_command * cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed)
```

```json
{
  "name": "queue_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592399536,
      "name": "queue_command",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:4273",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context",
        "drivers/usb/host/xhci-ring.c:xhci_queue_configure_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_address_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_slot_control",
        "drivers/usb/host/xhci-ring.c:xhci_handle_halted_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592399536,
      "name": "queue_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
int queue_command(struct xhci_hcd * xhci, struct xhci_command * cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed)
```

```json
{
  "name": "queue_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593144432,
      "name": "queue_command",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:4316",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context",
        "drivers/usb/host/xhci-ring.c:xhci_queue_configure_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_address_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_slot_control",
        "drivers/usb/host/xhci-ring.c:xhci_handle_halted_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593144432,
      "name": "queue_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
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
int queue_command(struct xhci_hcd * xhci, struct xhci_command * cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed)
```

```json
{
  "name": "queue_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500629176,
      "name": "queue_command",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3974",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context",
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_address_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_slot_control",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500629176,
      "name": "queue_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
int queue_command(struct xhci_hcd * xhci, struct xhci_command * cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed)
```

```json
{
  "name": "queue_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233091752,
      "name": "queue_command",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3974",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context",
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_address_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_slot_control",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233091752,
      "name": "queue_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
int queue_command(struct xhci_hcd * xhci, struct xhci_command * cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed)
```

```json
{
  "name": "queue_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294048128,
      "name": "queue_command",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3974",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context",
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_address_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_slot_control",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294048128,
      "name": "queue_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 636
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
int queue_command(struct xhci_hcd * xhci, struct xhci_command * cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed)
```

```json
{
  "name": "queue_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277498372,
      "name": "queue_command",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3974",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context",
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_address_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_slot_control",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277498372,
      "name": "queue_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
int queue_command(struct xhci_hcd * xhci, struct xhci_command * cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed)
```

```json
{
  "name": "queue_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "queue_command",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3974",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context",
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_address_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_slot_control",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587198736,
      "name": "queue_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
    },
    {
      "addr": 18446744071587219044,
      "name": "queue_command.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int queue_command(struct xhci_hcd * xhci, struct xhci_command * cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed)
```

```json
{
  "name": "queue_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "queue_command",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3974",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context",
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_address_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_slot_control",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586957488,
      "name": "queue_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
    },
    {
      "addr": 18446744071586977796,
      "name": "queue_command.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int queue_command(struct xhci_hcd * xhci, struct xhci_command * cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed)
```

```json
{
  "name": "queue_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "queue_command",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3974",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context",
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_address_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_slot_control",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587447264,
      "name": "queue_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
    },
    {
      "addr": 18446744071587467572,
      "name": "queue_command.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
int queue_command(struct xhci_hcd * xhci, struct xhci_command * cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed)
```

```json
{
  "name": "queue_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "queue_command",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3974",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context",
        "drivers/usb/host/xhci-ring.c:xhci_queue_reset_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_address_device",
        "drivers/usb/host/xhci-ring.c:xhci_queue_slot_control",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587554512,
      "name": "queue_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
    },
    {
      "addr": 18446744071587575175,
      "name": "queue_command.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
