# Function: <code>xhci_halt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int xhci_halt(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_halt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585451488,
      "name": "xhci_halt",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:107",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585451488,
      "name": "xhci_halt",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int xhci_halt(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_halt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585847056,
      "name": "xhci_halt",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:108",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585847056,
      "name": "xhci_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int xhci_halt(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586036208,
      "name": "xhci_halt",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:108",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586036208,
      "name": "xhci_halt",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int xhci_halt(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586119840,
      "name": "xhci_halt",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:108",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586119840,
      "name": "xhci_halt",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int xhci_halt(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586562656,
      "name": "xhci_halt",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:98",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586562656,
      "name": "xhci_halt",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int xhci_halt(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586827312,
      "name": "xhci_halt",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:113",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586827312,
      "name": "xhci_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int xhci_halt(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586983952,
      "name": "xhci_halt",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:113",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586983952,
      "name": "xhci_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int xhci_halt(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_halt",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:111",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587265758,
      "name": "xhci_halt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071587245328,
      "name": "xhci_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int xhci_halt(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_halt",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:111",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587466125,
      "name": "xhci_halt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071587445776,
      "name": "xhci_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int xhci_halt(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_halt",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:111",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_enter_test_mode",
        "drivers/usb/host/xhci-hub.c:xhci_enter_test_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588328568,
      "name": "xhci_halt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071588309728,
      "name": "xhci_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int xhci_halt(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_halt",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:111",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_enter_test_mode",
        "drivers/usb/host/xhci-hub.c:xhci_enter_test_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591562917,
      "name": "xhci_halt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071588344448,
      "name": "xhci_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int xhci_halt(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_halt",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:110",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_enter_test_mode",
        "drivers/usb/host/xhci-hub.c:xhci_enter_test_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591505642,
      "name": "xhci_halt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071588227152,
      "name": "xhci_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int xhci_halt(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_halt",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:110",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_enter_test_mode",
        "drivers/usb/host/xhci-hub.c:xhci_enter_test_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592606828,
      "name": "xhci_halt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071588870848,
      "name": "xhci_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int xhci_halt(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_halt",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:110",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run_finished",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_enter_test_mode",
        "drivers/usb/host/xhci-hub.c:xhci_enter_test_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594489901,
      "name": "xhci_halt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071590297632,
      "name": "xhci_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int xhci_halt(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591921600,
      "name": "xhci_halt",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:110",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run_finished",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_enter_test_mode",
        "drivers/usb/host/xhci-hub.c:xhci_enter_test_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591921600,
      "name": "xhci_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
int xhci_halt(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592343616,
      "name": "xhci_halt",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:111",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run_finished",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_enter_test_mode",
        "drivers/usb/host/xhci-hub.c:xhci_enter_test_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592343616,
      "name": "xhci_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
int xhci_halt(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593085184,
      "name": "xhci_halt",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:134",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run_finished",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_enter_test_mode",
        "drivers/usb/host/xhci-hub.c:xhci_enter_test_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593085184,
      "name": "xhci_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
int xhci_halt(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500580408,
      "name": "xhci_halt",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:111",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500580408,
      "name": "xhci_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int xhci_halt(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233042000,
      "name": "xhci_halt",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:111",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233042000,
      "name": "xhci_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int xhci_halt(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293984064,
      "name": "xhci_halt",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:111",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293984064,
      "name": "xhci_halt",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int xhci_halt(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277452464,
      "name": "xhci_halt",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:111",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277452464,
      "name": "xhci_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int xhci_halt(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_halt",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:111",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587172157,
      "name": "xhci_halt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071587151840,
      "name": "xhci_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int xhci_halt(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_halt",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:111",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586930899,
      "name": "xhci_halt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071586910448,
      "name": "xhci_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int xhci_halt(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_halt",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:111",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587420685,
      "name": "xhci_halt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071587400336,
      "name": "xhci_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int xhci_halt(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_halt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_halt",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:111",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587527414,
      "name": "xhci_halt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071587506768,
      "name": "xhci_halt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
