# Function: <code>dwc2_backup_global_registers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_backup_global_registers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585275926,
      "name": "dwc2_backup_global_registers",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:249",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_enter_hibernation"
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
  "name": "dwc2_backup_global_registers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585668724,
      "name": "dwc2_backup_global_registers",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:66",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_enter_hibernation"
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
  "name": "dwc2_backup_global_registers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585856675,
      "name": "dwc2_backup_global_registers",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:66",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_enter_hibernation"
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
  "name": "dwc2_backup_global_registers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585943130,
      "name": "dwc2_backup_global_registers",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:66",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_enter_hibernation"
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
  "name": "dwc2_backup_global_registers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586386234,
      "name": "dwc2_backup_global_registers",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:67",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_enter_hibernation"
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
int dwc2_backup_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586643152,
      "name": "dwc2_backup_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:67",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586643152,
      "name": "dwc2_backup_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int dwc2_backup_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586792320,
      "name": "dwc2_backup_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:67",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586792320,
      "name": "dwc2_backup_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
int dwc2_backup_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587048560,
      "name": "dwc2_backup_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:67",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587048560,
      "name": "dwc2_backup_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
int dwc2_backup_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587248960,
      "name": "dwc2_backup_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:67",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587248960,
      "name": "dwc2_backup_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
int dwc2_backup_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588103648,
      "name": "dwc2_backup_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:67",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588103648,
      "name": "dwc2_backup_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int dwc2_backup_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588145408,
      "name": "dwc2_backup_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:67",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588145408,
      "name": "dwc2_backup_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int dwc2_backup_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588027312,
      "name": "dwc2_backup_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:67",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588027312,
      "name": "dwc2_backup_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int dwc2_backup_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_backup_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:67",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592574774,
      "name": "dwc2_backup_global_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    },
    {
      "addr": 18446744071588644160,
      "name": "dwc2_backup_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
int dwc2_backup_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_backup_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:67",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594454493,
      "name": "dwc2_backup_global_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    },
    {
      "addr": 18446744071590061008,
      "name": "dwc2_backup_global_registers",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int dwc2_backup_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_backup_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:37",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596273598,
      "name": "dwc2_backup_global_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    },
    {
      "addr": 18446744071591668352,
      "name": "dwc2_backup_global_registers",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int dwc2_backup_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_backup_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:37",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596803438,
      "name": "dwc2_backup_global_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    },
    {
      "addr": 18446744071592091184,
      "name": "dwc2_backup_global_registers",
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
int dwc2_backup_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_backup_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:37",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597727045,
      "name": "dwc2_backup_global_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    },
    {
      "addr": 18446744071592831616,
      "name": "dwc2_backup_global_registers",
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
int dwc2_backup_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500355880,
      "name": "dwc2_backup_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:67",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500355880,
      "name": "dwc2_backup_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
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
int dwc2_backup_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232814560,
      "name": "dwc2_backup_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:67",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232814560,
      "name": "dwc2_backup_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
int dwc2_backup_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293662672,
      "name": "dwc2_backup_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:67",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293662672,
      "name": "dwc2_backup_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1704
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
int dwc2_backup_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277238376,
      "name": "dwc2_backup_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:67",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277238376,
      "name": "dwc2_backup_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 810
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
int dwc2_backup_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586955040,
      "name": "dwc2_backup_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:67",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586955040,
      "name": "dwc2_backup_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
int dwc2_backup_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587203520,
      "name": "dwc2_backup_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:67",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587203520,
      "name": "dwc2_backup_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
int dwc2_backup_global_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_global_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587310592,
      "name": "dwc2_backup_global_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:67",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587310592,
      "name": "dwc2_backup_global_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
int dwc2_backup_global_registers(struct dwc2_hsotg * hsotg)
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
int dwc2_backup_global_registers(struct dwc2_hsotg * hsotg)
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
