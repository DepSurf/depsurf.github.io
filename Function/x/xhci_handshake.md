# Function: <code>xhci_handshake</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int xhci_handshake(void * ptr, u32 mask, u32 done, int usec)
```

```json
{
  "name": "xhci_handshake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585450511,
      "name": "xhci_handshake",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:63",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585451328,
      "name": "xhci_handshake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int xhci_handshake(void * ptr, u32 mask, u32 done, int usec)
```

```json
{
  "name": "xhci_handshake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585851174,
      "name": "xhci_handshake",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:64",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_run"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585846896,
      "name": "xhci_handshake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int xhci_handshake(void * ptr, u32 mask, u32 done, int usec)
```

```json
{
  "name": "xhci_handshake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586040006,
      "name": "xhci_handshake",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:64",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_halt"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586036048,
      "name": "xhci_handshake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int xhci_handshake(void * ptr, u32 mask, u32 done, int usec)
```

```json
{
  "name": "xhci_handshake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586123275,
      "name": "xhci_handshake",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:64",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_start",
        "drivers/usb/host/xhci.c:xhci_halt"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586119680,
      "name": "xhci_handshake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int xhci_handshake(void * ptr, u32 mask, u32 done, int usec)
```

```json
{
  "name": "xhci_handshake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586566115,
      "name": "xhci_handshake",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:54",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_start",
        "drivers/usb/host/xhci.c:xhci_halt"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586562496,
      "name": "xhci_handshake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int xhci_handshake(void * ptr, u32 mask, u32 done, int usec)
```

```json
{
  "name": "xhci_handshake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586830857,
      "name": "xhci_handshake",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:69",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_start",
        "drivers/usb/host/xhci.c:xhci_halt"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586827152,
      "name": "xhci_handshake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int xhci_handshake(void * ptr, u32 mask, u32 done, int usec)
```

```json
{
  "name": "xhci_handshake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586987571,
      "name": "xhci_handshake",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:69",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_start",
        "drivers/usb/host/xhci.c:xhci_halt"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586983792,
      "name": "xhci_handshake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int xhci_handshake(void * ptr, u32 mask, u32 done, int usec)
```

```json
{
  "name": "xhci_handshake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587243840,
      "name": "xhci_handshake",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:69",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_start",
        "drivers/usb/host/xhci.c:xhci_halt",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587243840,
      "name": "xhci_handshake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int xhci_handshake(void * ptr, u32 mask, u32 done, int usec)
```

```json
{
  "name": "xhci_handshake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587444288,
      "name": "xhci_handshake",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:69",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_start",
        "drivers/usb/host/xhci.c:xhci_halt",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587444288,
      "name": "xhci_handshake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int xhci_handshake(void * ptr, u32 mask, u32 done, int usec)
```

```json
{
  "name": "xhci_handshake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588308688,
      "name": "xhci_handshake",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:69",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_start",
        "drivers/usb/host/xhci.c:xhci_halt",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-dbgcap.c:xhci_do_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_do_dbc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588308688,
      "name": "xhci_handshake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int xhci_handshake(void * ptr, u32 mask, u32 done, int usec)
```

```json
{
  "name": "xhci_handshake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588343392,
      "name": "xhci_handshake",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:69",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_start",
        "drivers/usb/host/xhci.c:xhci_halt",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588343392,
      "name": "xhci_handshake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int xhci_handshake(void * ptr, u32 mask, u32 done, int usec)
```

```json
{
  "name": "xhci_handshake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588225952,
      "name": "xhci_handshake",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:68",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_start",
        "drivers/usb/host/xhci.c:xhci_halt",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588225952,
      "name": "xhci_handshake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int xhci_handshake(void * ptr, u32 mask, u32 done, int usec)
```

```json
{
  "name": "xhci_handshake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588869616,
      "name": "xhci_handshake",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:68",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_start",
        "drivers/usb/host/xhci.c:xhci_halt",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588869616,
      "name": "xhci_handshake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int xhci_handshake(void * ptr, u32 mask, u32 done, u64 timeout_us)
```

```json
{
  "name": "xhci_handshake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590296224,
      "name": "xhci_handshake",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:68",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_start",
        "drivers/usb/host/xhci.c:xhci_halt",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590296224,
      "name": "xhci_handshake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int xhci_handshake(void * ptr, u32 mask, u32 done, u64 timeout_us)
```

```json
{
  "name": "xhci_handshake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591919760,
      "name": "xhci_handshake",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:68",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_start",
        "drivers/usb/host/xhci.c:xhci_halt",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591919760,
      "name": "xhci_handshake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int xhci_handshake(void * ptr, u32 mask, u32 done, u64 timeout_us)
```

```json
{
  "name": "xhci_handshake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592341904,
      "name": "xhci_handshake",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:69",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_start",
        "drivers/usb/host/xhci.c:xhci_halt",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592341904,
      "name": "xhci_handshake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int xhci_handshake(void * ptr, u32 mask, u32 done, u64 timeout_us)
```

```json
{
  "name": "xhci_handshake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593083152,
      "name": "xhci_handshake",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:69",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_start",
        "drivers/usb/host/xhci.c:xhci_halt",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593083152,
      "name": "xhci_handshake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int xhci_handshake(void * ptr, u32 mask, u32 done, int usec)
```

```json
{
  "name": "xhci_handshake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500577792,
      "name": "xhci_handshake",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:69",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_start",
        "drivers/usb/host/xhci.c:xhci_halt",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500577792,
      "name": "xhci_handshake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int xhci_handshake(void * ptr, u32 mask, u32 done, int usec)
```

```json
{
  "name": "xhci_handshake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233039720,
      "name": "xhci_handshake",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:69",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_start",
        "drivers/usb/host/xhci.c:xhci_halt",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233039720,
      "name": "xhci_handshake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int xhci_handshake(void * ptr, u32 mask, u32 done, int usec)
```

```json
{
  "name": "xhci_handshake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293979712,
      "name": "xhci_handshake",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:69",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_start",
        "drivers/usb/host/xhci.c:xhci_halt",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293979712,
      "name": "xhci_handshake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
int xhci_handshake(void * ptr, u32 mask, u32 done, int usec)
```

```json
{
  "name": "xhci_handshake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277450172,
      "name": "xhci_handshake",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:69",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_start",
        "drivers/usb/host/xhci.c:xhci_halt",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277450172,
      "name": "xhci_handshake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int xhci_handshake(void * ptr, u32 mask, u32 done, int usec)
```

```json
{
  "name": "xhci_handshake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587150368,
      "name": "xhci_handshake",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:69",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_start",
        "drivers/usb/host/xhci.c:xhci_halt",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587150368,
      "name": "xhci_handshake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int xhci_handshake(void * ptr, u32 mask, u32 done, int usec)
```

```json
{
  "name": "xhci_handshake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586908976,
      "name": "xhci_handshake",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:69",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_start",
        "drivers/usb/host/xhci.c:xhci_halt",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586908976,
      "name": "xhci_handshake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int xhci_handshake(void * ptr, u32 mask, u32 done, int usec)
```

```json
{
  "name": "xhci_handshake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587398848,
      "name": "xhci_handshake",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:69",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_start",
        "drivers/usb/host/xhci.c:xhci_halt",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587398848,
      "name": "xhci_handshake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int xhci_handshake(void * ptr, u32 mask, u32 done, int usec)
```

```json
{
  "name": "xhci_handshake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587505296,
      "name": "xhci_handshake",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:69",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_start",
        "drivers/usb/host/xhci.c:xhci_halt",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587505296,
      "name": "xhci_handshake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 timeout_us</code>
</li>
<li>
<b>Param removed. </b>
<code>int usec</code>
</li>
</ul>
</details>
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
