# Function: <code>dwc2_backup_host_registers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_backup_host_registers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585276124,
      "name": "dwc2_backup_host_registers",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int dwc2_backup_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585704608,
      "name": "dwc2_backup_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5242",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585704608,
      "name": "dwc2_backup_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int dwc2_backup_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585893312,
      "name": "dwc2_backup_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5241",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585893312,
      "name": "dwc2_backup_host_registers",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int dwc2_backup_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585976064,
      "name": "dwc2_backup_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5334",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585976064,
      "name": "dwc2_backup_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int dwc2_backup_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586419952,
      "name": "dwc2_backup_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5348",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_enter_hibernation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586419952,
      "name": "dwc2_backup_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int dwc2_backup_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586682288,
      "name": "dwc2_backup_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5431",
      "file": "drivers/usb/dwc2/hcd.c",
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
      "addr": 18446744071586682288,
      "name": "dwc2_backup_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int dwc2_backup_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586837360,
      "name": "dwc2_backup_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5450",
      "file": "drivers/usb/dwc2/hcd.c",
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
      "addr": 18446744071586837360,
      "name": "dwc2_backup_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int dwc2_backup_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587094240,
      "name": "dwc2_backup_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5306",
      "file": "drivers/usb/dwc2/hcd.c",
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
      "addr": 18446744071587094240,
      "name": "dwc2_backup_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int dwc2_backup_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587294768,
      "name": "dwc2_backup_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5306",
      "file": "drivers/usb/dwc2/hcd.c",
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
      "addr": 18446744071587294768,
      "name": "dwc2_backup_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int dwc2_backup_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588150064,
      "name": "dwc2_backup_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5306",
      "file": "drivers/usb/dwc2/hcd.c",
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
      "addr": 18446744071588150064,
      "name": "dwc2_backup_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
int dwc2_backup_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588190608,
      "name": "dwc2_backup_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5308",
      "file": "drivers/usb/dwc2/hcd.c",
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
      "addr": 18446744071588190608,
      "name": "dwc2_backup_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
int dwc2_backup_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588066416,
      "name": "dwc2_backup_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5425",
      "file": "drivers/usb/dwc2/hcd.c",
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
      "addr": 18446744071588066416,
      "name": "dwc2_backup_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
int dwc2_backup_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_backup_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5430",
      "file": "drivers/usb/dwc2/hcd.c",
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
      "addr": 18446744071592591209,
      "name": "dwc2_backup_host_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071588693904,
      "name": "dwc2_backup_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 445
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
int dwc2_backup_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_backup_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5426",
      "file": "drivers/usb/dwc2/hcd.c",
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
      "addr": 18446744071594472364,
      "name": "dwc2_backup_host_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071590112400,
      "name": "dwc2_backup_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 457
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
int dwc2_backup_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_backup_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5399",
      "file": "drivers/usb/dwc2/hcd.c",
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
      "addr": 18446744071596288761,
      "name": "dwc2_backup_host_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071591724304,
      "name": "dwc2_backup_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 457
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
int dwc2_backup_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_backup_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5399",
      "file": "drivers/usb/dwc2/hcd.c",
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
      "addr": 18446744071596818617,
      "name": "dwc2_backup_host_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071592147680,
      "name": "dwc2_backup_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
int dwc2_backup_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_backup_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5399",
      "file": "drivers/usb/dwc2/hcd.c",
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
      "addr": 18446744071597742221,
      "name": "dwc2_backup_host_registers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071592888304,
      "name": "dwc2_backup_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
int dwc2_backup_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500410616,
      "name": "dwc2_backup_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5306",
      "file": "drivers/usb/dwc2/hcd.c",
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
      "addr": 18446603336500410616,
      "name": "dwc2_backup_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int dwc2_backup_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232866472,
      "name": "dwc2_backup_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5306",
      "file": "drivers/usb/dwc2/hcd.c",
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
      "addr": 3232866472,
      "name": "dwc2_backup_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int dwc2_backup_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293748576,
      "name": "dwc2_backup_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5306",
      "file": "drivers/usb/dwc2/hcd.c",
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
      "addr": 13835058055293748576,
      "name": "dwc2_backup_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 936
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
int dwc2_backup_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277300138,
      "name": "dwc2_backup_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5306",
      "file": "drivers/usb/dwc2/hcd.c",
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
      "addr": 18446743936277300138,
      "name": "dwc2_backup_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 530
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
int dwc2_backup_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587000848,
      "name": "dwc2_backup_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5306",
      "file": "drivers/usb/dwc2/hcd.c",
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
      "addr": 18446744071587000848,
      "name": "dwc2_backup_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int dwc2_backup_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587249328,
      "name": "dwc2_backup_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5306",
      "file": "drivers/usb/dwc2/hcd.c",
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
      "addr": 18446744071587249328,
      "name": "dwc2_backup_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int dwc2_backup_host_registers(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_backup_host_registers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587356096,
      "name": "dwc2_backup_host_registers",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5306",
      "file": "drivers/usb/dwc2/hcd.c",
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
      "addr": 18446744071587356096,
      "name": "dwc2_backup_host_registers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int dwc2_backup_host_registers(struct dwc2_hsotg * hsotg)
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
int dwc2_backup_host_registers(struct dwc2_hsotg * hsotg)
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
