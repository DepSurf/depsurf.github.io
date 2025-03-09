# Function: <code>dwc2_restore_global_registers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_restore_global_registers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585275314,
      "name": "dwc2_restore_global_registers",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:279",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_restore_global_registers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585668358,
      "name": "dwc2_restore_global_registers",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:96",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_restore_global_registers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585856309,
      "name": "dwc2_restore_global_registers",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:96",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_restore_global_registers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585942751,
      "name": "dwc2_restore_global_registers",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:96",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_restore_global_registers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586385855,
      "name": "dwc2_restore_global_registers",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:97",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int dwc2_restore_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586643376,
      "name": "dwc2_restore_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:99",
      "file": "drivers/usb/dwc2/core.c",
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
      "addr": 18446744071586643376,
      "name": "dwc2_restore_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
int dwc2_restore_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586792656,
      "name": "dwc2_restore_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:99",
      "file": "drivers/usb/dwc2/core.c",
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
      "addr": 18446744071586792656,
      "name": "dwc2_restore_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 509
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
int dwc2_restore_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_restore_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:99",
      "file": "drivers/usb/dwc2/core.c",
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
      "addr": 18446744071587054146,
      "name": "dwc2_restore_global_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587048896,
      "name": "dwc2_restore_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 491
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
int dwc2_restore_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_restore_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:99",
      "file": "drivers/usb/dwc2/core.c",
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
      "addr": 18446744071587254546,
      "name": "dwc2_restore_global_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587249296,
      "name": "dwc2_restore_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 491
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
int dwc2_restore_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_restore_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:99",
      "file": "drivers/usb/dwc2/core.c",
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
      "addr": 18446744071588109048,
      "name": "dwc2_restore_global_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588103984,
      "name": "dwc2_restore_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 483
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
int dwc2_restore_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_restore_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:99",
      "file": "drivers/usb/dwc2/core.c",
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
      "addr": 18446744071591554042,
      "name": "dwc2_restore_global_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588145744,
      "name": "dwc2_restore_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 483
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
int dwc2_restore_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_restore_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:99",
      "file": "drivers/usb/dwc2/core.c",
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
      "addr": 18446744071591496331,
      "name": "dwc2_restore_global_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588027680,
      "name": "dwc2_restore_global_registers",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int dwc2_restore_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_restore_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:99",
      "file": "drivers/usb/dwc2/core.c",
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
      "addr": 18446744071592575005,
      "name": "dwc2_restore_global_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    },
    {
      "addr": 18446744071588644736,
      "name": "dwc2_restore_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 753
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
int dwc2_restore_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_restore_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:99",
      "file": "drivers/usb/dwc2/core.c",
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
      "addr": 18446744071594454724,
      "name": "dwc2_restore_global_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    },
    {
      "addr": 18446744071590061600,
      "name": "dwc2_restore_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 755
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
int dwc2_restore_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_restore_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:69",
      "file": "drivers/usb/dwc2/core.c",
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
      "addr": 18446744071596273829,
      "name": "dwc2_restore_global_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
    },
    {
      "addr": 18446744071591668960,
      "name": "dwc2_restore_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 790
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
int dwc2_restore_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_restore_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:69",
      "file": "drivers/usb/dwc2/core.c",
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
      "addr": 18446744071596803669,
      "name": "dwc2_restore_global_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
    },
    {
      "addr": 18446744071592091792,
      "name": "dwc2_restore_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 790
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
int dwc2_restore_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_restore_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:69",
      "file": "drivers/usb/dwc2/core.c",
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
      "addr": 18446744071597727276,
      "name": "dwc2_restore_global_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
    },
    {
      "addr": 18446744071592832224,
      "name": "dwc2_restore_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 790
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
int dwc2_restore_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500356504,
      "name": "dwc2_restore_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:99",
      "file": "drivers/usb/dwc2/core.c",
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
      "addr": 18446603336500356504,
      "name": "dwc2_restore_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 808
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
int dwc2_restore_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232814960,
      "name": "dwc2_restore_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:99",
      "file": "drivers/usb/dwc2/core.c",
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
      "addr": 3232814960,
      "name": "dwc2_restore_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 880
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
int dwc2_restore_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293664384,
      "name": "dwc2_restore_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:99",
      "file": "drivers/usb/dwc2/core.c",
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
      "addr": 13835058055293664384,
      "name": "dwc2_restore_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1116
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
int dwc2_restore_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277239186,
      "name": "dwc2_restore_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:99",
      "file": "drivers/usb/dwc2/core.c",
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
      "addr": 18446743936277239186,
      "name": "dwc2_restore_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1246
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
int dwc2_restore_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_restore_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:99",
      "file": "drivers/usb/dwc2/core.c",
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
      "addr": 18446744071586960626,
      "name": "dwc2_restore_global_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071586955376,
      "name": "dwc2_restore_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 491
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
int dwc2_restore_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_restore_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:99",
      "file": "drivers/usb/dwc2/core.c",
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
      "addr": 18446744071587209106,
      "name": "dwc2_restore_global_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587203856,
      "name": "dwc2_restore_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 491
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
int dwc2_restore_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_restore_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_restore_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:99",
      "file": "drivers/usb/dwc2/core.c",
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
      "addr": 18446744071587316178,
      "name": "dwc2_restore_global_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587310928,
      "name": "dwc2_restore_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 491
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
int dwc2_restore_global_registers(struct dwc2_hsotg * hsotg)
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
int dwc2_restore_global_registers(struct dwc2_hsotg * hsotg)
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
