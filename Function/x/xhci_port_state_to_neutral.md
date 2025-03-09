# Function: <code>xhci_port_state_to_neutral</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 xhci_port_state_to_neutral(u32 state)
```

```json
{
  "name": "xhci_port_state_to_neutral",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585518400,
      "name": "xhci_port_state_to_neutral",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:341",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585518400,
      "name": "xhci_port_state_to_neutral",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
u32 xhci_port_state_to_neutral(u32 state)
```

```json
{
  "name": "xhci_port_state_to_neutral",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585922188,
      "name": "xhci_port_state_to_neutral",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:341",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585913504,
      "name": "xhci_port_state_to_neutral",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
u32 xhci_port_state_to_neutral(u32 state)
```

```json
{
  "name": "xhci_port_state_to_neutral",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586110427,
      "name": "xhci_port_state_to_neutral",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:341",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586101584,
      "name": "xhci_port_state_to_neutral",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
u32 xhci_port_state_to_neutral(u32 state)
```

```json
{
  "name": "xhci_port_state_to_neutral",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586194793,
      "name": "xhci_port_state_to_neutral",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:350",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586185120,
      "name": "xhci_port_state_to_neutral",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
u32 xhci_port_state_to_neutral(u32 state)
```

```json
{
  "name": "xhci_port_state_to_neutral",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586640571,
      "name": "xhci_port_state_to_neutral",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:338",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586630720,
      "name": "xhci_port_state_to_neutral",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
u32 xhci_port_state_to_neutral(u32 state)
```

```json
{
  "name": "xhci_port_state_to_neutral",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586906775,
      "name": "xhci_port_state_to_neutral",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:341",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586896160,
      "name": "xhci_port_state_to_neutral",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
u32 xhci_port_state_to_neutral(u32 state)
```

```json
{
  "name": "xhci_port_state_to_neutral",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587063779,
      "name": "xhci_port_state_to_neutral",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:341",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587052528,
      "name": "xhci_port_state_to_neutral",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
u32 xhci_port_state_to_neutral(u32 state)
```

```json
{
  "name": "xhci_port_state_to_neutral",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587327101,
      "name": "xhci_port_state_to_neutral",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:341",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587315552,
      "name": "xhci_port_state_to_neutral",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
u32 xhci_port_state_to_neutral(u32 state)
```

```json
{
  "name": "xhci_port_state_to_neutral",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587528621,
      "name": "xhci_port_state_to_neutral",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:350",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587516704,
      "name": "xhci_port_state_to_neutral",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 xhci_port_state_to_neutral(u32 state)
```

```json
{
  "name": "xhci_port_state_to_neutral",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588390590,
      "name": "xhci_port_state_to_neutral",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:350",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_disable_port_wake_on_bits",
        "drivers/usb/host/xhci.c:xhci_disable_port_wake_on_bits",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588381424,
      "name": "xhci_port_state_to_neutral",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 xhci_port_state_to_neutral(u32 state)
```

```json
{
  "name": "xhci_port_state_to_neutral",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588417563,
      "name": "xhci_port_state_to_neutral",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:350",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_disable_hub_port_wake",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588408336,
      "name": "xhci_port_state_to_neutral",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
u32 xhci_port_state_to_neutral(u32 state)
```

```json
{
  "name": "xhci_port_state_to_neutral",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588300682,
      "name": "xhci_port_state_to_neutral",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:436",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_disable_hub_port_wake",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588291376,
      "name": "xhci_port_state_to_neutral",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 xhci_port_state_to_neutral(u32 state)
```

```json
{
  "name": "xhci_port_state_to_neutral",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588957847,
      "name": "xhci_port_state_to_neutral",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:437",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_disable_hub_port_wake",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588945200,
      "name": "xhci_port_state_to_neutral",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 xhci_port_state_to_neutral(u32 state)
```

```json
{
  "name": "xhci_port_state_to_neutral",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590389906,
      "name": "xhci_port_state_to_neutral",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:437",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_disable_hub_port_wake",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590376480,
      "name": "xhci_port_state_to_neutral",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 xhci_port_state_to_neutral(u32 state)
```

```json
{
  "name": "xhci_port_state_to_neutral",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592024242,
      "name": "xhci_port_state_to_neutral",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:444",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_disable_hub_port_wake",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592007104,
      "name": "xhci_port_state_to_neutral",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 xhci_port_state_to_neutral(u32 state)
```

```json
{
  "name": "xhci_port_state_to_neutral",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592443850,
      "name": "xhci_port_state_to_neutral",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:444",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_handle_usb2_port_link_resume",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_disable_hub_port_wake",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592427824,
      "name": "xhci_port_state_to_neutral",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 xhci_port_state_to_neutral(u32 state)
```

```json
{
  "name": "xhci_port_state_to_neutral",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593187578,
      "name": "xhci_port_state_to_neutral",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:444",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_handle_usb2_port_link_resume",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_disable_hub_port_wake",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593171568,
      "name": "xhci_port_state_to_neutral",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
u32 xhci_port_state_to_neutral(u32 state)
```

```json
{
  "name": "xhci_port_state_to_neutral",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500668460,
      "name": "xhci_port_state_to_neutral",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:350",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_test_and_clear_bit",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500657056,
      "name": "xhci_port_state_to_neutral",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
u32 xhci_port_state_to_neutral(u32 state)
```

```json
{
  "name": "xhci_port_state_to_neutral",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233128288,
      "name": "xhci_port_state_to_neutral",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:350",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233116480,
      "name": "xhci_port_state_to_neutral",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
u32 xhci_port_state_to_neutral(u32 state)
```

```json
{
  "name": "xhci_port_state_to_neutral",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294093916,
      "name": "xhci_port_state_to_neutral",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:350",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_test_and_clear_bit",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294080656,
      "name": "xhci_port_state_to_neutral",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
u32 xhci_port_state_to_neutral(u32 state)
```

```json
{
  "name": "xhci_port_state_to_neutral",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277530584,
      "name": "xhci_port_state_to_neutral",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:350",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277519350,
      "name": "xhci_port_state_to_neutral",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
u32 xhci_port_state_to_neutral(u32 state)
```

```json
{
  "name": "xhci_port_state_to_neutral",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587234653,
      "name": "xhci_port_state_to_neutral",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:350",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587222736,
      "name": "xhci_port_state_to_neutral",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
u32 xhci_port_state_to_neutral(u32 state)
```

```json
{
  "name": "xhci_port_state_to_neutral",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586993405,
      "name": "xhci_port_state_to_neutral",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:350",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586981488,
      "name": "xhci_port_state_to_neutral",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
u32 xhci_port_state_to_neutral(u32 state)
```

```json
{
  "name": "xhci_port_state_to_neutral",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587483181,
      "name": "xhci_port_state_to_neutral",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:350",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587471264,
      "name": "xhci_port_state_to_neutral",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
u32 xhci_port_state_to_neutral(u32 state)
```

```json
{
  "name": "xhci_port_state_to_neutral",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587590909,
      "name": "xhci_port_state_to_neutral",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:350",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587578928,
      "name": "xhci_port_state_to_neutral",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
