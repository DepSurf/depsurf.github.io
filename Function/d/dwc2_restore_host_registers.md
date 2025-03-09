# Function: <code>dwc2_restore_host_registers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_restore_host_registers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585275306,
      "name": "dwc2_restore_host_registers",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:95",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_exit_hibernation"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int dwc2_restore_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585704800,
      "name": "dwc2_restore_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5270",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_exit_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585704800,
      "name": "dwc2_restore_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
int dwc2_restore_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585893504,
      "name": "dwc2_restore_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5269",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_exit_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585893504,
      "name": "dwc2_restore_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
int dwc2_restore_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585976256,
      "name": "dwc2_restore_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5362",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_exit_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585976256,
      "name": "dwc2_restore_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
int dwc2_restore_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586420144,
      "name": "dwc2_restore_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5376",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_exit_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586420144,
      "name": "dwc2_restore_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
int dwc2_restore_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586682496,
      "name": "dwc2_restore_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5460",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586682496,
      "name": "dwc2_restore_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
int dwc2_restore_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586837632,
      "name": "dwc2_restore_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5479",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586837632,
      "name": "dwc2_restore_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
int dwc2_restore_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_restore_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5335",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587098038,
      "name": "dwc2_restore_host_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587094512,
      "name": "dwc2_restore_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
int dwc2_restore_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_restore_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5335",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587298472,
      "name": "dwc2_restore_host_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587295040,
      "name": "dwc2_restore_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
int dwc2_restore_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_restore_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5335",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588153747,
      "name": "dwc2_restore_host_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588150336,
      "name": "dwc2_restore_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
int dwc2_restore_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_restore_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5337",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591557642,
      "name": "dwc2_restore_host_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588190880,
      "name": "dwc2_restore_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
int dwc2_restore_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_restore_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5454",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591499352,
      "name": "dwc2_restore_host_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588066704,
      "name": "dwc2_restore_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
int dwc2_restore_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_restore_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5459",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592591335,
      "name": "dwc2_restore_host_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    },
    {
      "addr": 18446744071588694352,
      "name": "dwc2_restore_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
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
int dwc2_restore_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_restore_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5455",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594472490,
      "name": "dwc2_restore_host_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    },
    {
      "addr": 18446744071590112864,
      "name": "dwc2_restore_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 550
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
int dwc2_restore_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_restore_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5428",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596288887,
      "name": "dwc2_restore_host_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071591724784,
      "name": "dwc2_restore_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 586
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
int dwc2_restore_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_restore_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5428",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596818737,
      "name": "dwc2_restore_host_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071592148176,
      "name": "dwc2_restore_host_registers",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int dwc2_restore_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_restore_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5428",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597742341,
      "name": "dwc2_restore_host_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071592888800,
      "name": "dwc2_restore_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
int dwc2_restore_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500411056,
      "name": "dwc2_restore_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5335",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500411056,
      "name": "dwc2_restore_host_registers",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int dwc2_restore_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232866792,
      "name": "dwc2_restore_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5335",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232866792,
      "name": "dwc2_restore_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
int dwc2_restore_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293749520,
      "name": "dwc2_restore_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5335",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293749520,
      "name": "dwc2_restore_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 732
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
int dwc2_restore_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277300668,
      "name": "dwc2_restore_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5335",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277300668,
      "name": "dwc2_restore_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 782
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
int dwc2_restore_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_restore_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5335",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587004552,
      "name": "dwc2_restore_host_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587001120,
      "name": "dwc2_restore_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
int dwc2_restore_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_restore_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5335",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587253032,
      "name": "dwc2_restore_host_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587249600,
      "name": "dwc2_restore_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
int dwc2_restore_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_restore_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5335",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587359800,
      "name": "dwc2_restore_host_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587356368,
      "name": "dwc2_restore_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int dwc2_restore_host_registers(struct dwc2_hsotg * hsotg)
```
</details>
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
int dwc2_restore_host_registers(struct dwc2_hsotg * hsotg)
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
