# Function: <code>dwc2_host_exit_hibernation</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int dwc2_host_exit_hibernation(struct dwc2_hsotg * hsotg, int rem_wakeup, int reset)
```

```json
{
  "name": "dwc2_host_exit_hibernation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586683344,
      "name": "dwc2_host_exit_hibernation",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5605",
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
      "addr": 18446744071586683344,
      "name": "dwc2_host_exit_hibernation",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 711
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
int dwc2_host_exit_hibernation(struct dwc2_hsotg * hsotg, int rem_wakeup, int reset)
```

```json
{
  "name": "dwc2_host_exit_hibernation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586838864,
      "name": "dwc2_host_exit_hibernation",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5624",
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
      "addr": 18446744071586838864,
      "name": "dwc2_host_exit_hibernation",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 942
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
int dwc2_host_exit_hibernation(struct dwc2_hsotg * hsotg, int rem_wakeup, int reset)
```

```json
{
  "name": "dwc2_host_exit_hibernation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_host_exit_hibernation",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5480",
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
      "addr": 18446744071587098144,
      "name": "dwc2_host_exit_hibernation.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071587095600,
      "name": "dwc2_host_exit_hibernation",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int dwc2_host_exit_hibernation(struct dwc2_hsotg * hsotg, int rem_wakeup, int reset)
```

```json
{
  "name": "dwc2_host_exit_hibernation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_host_exit_hibernation",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5480",
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
      "addr": 18446744071587298578,
      "name": "dwc2_host_exit_hibernation.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071587296128,
      "name": "dwc2_host_exit_hibernation",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int dwc2_host_exit_hibernation(struct dwc2_hsotg * hsotg, int rem_wakeup, int reset)
```

```json
{
  "name": "dwc2_host_exit_hibernation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_host_exit_hibernation",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5480",
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
      "addr": 18446744071588153853,
      "name": "dwc2_host_exit_hibernation.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071588151440,
      "name": "dwc2_host_exit_hibernation",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int dwc2_host_exit_hibernation(struct dwc2_hsotg * hsotg, int rem_wakeup, int reset)
```

```json
{
  "name": "dwc2_host_exit_hibernation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_host_exit_hibernation",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5482",
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
      "addr": 18446744071591557748,
      "name": "dwc2_host_exit_hibernation.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071588191984,
      "name": "dwc2_host_exit_hibernation",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int dwc2_host_exit_hibernation(struct dwc2_hsotg * hsotg, int rem_wakeup, int reset)
```

```json
{
  "name": "dwc2_host_exit_hibernation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_host_exit_hibernation",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5599",
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
      "addr": 18446744071591499458,
      "name": "dwc2_host_exit_hibernation.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071588067824,
      "name": "dwc2_host_exit_hibernation",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 886
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
int dwc2_host_exit_hibernation(struct dwc2_hsotg * hsotg, int rem_wakeup, int reset)
```

```json
{
  "name": "dwc2_host_exit_hibernation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_host_exit_hibernation",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5604",
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
      "addr": 18446744071592592369,
      "name": "dwc2_host_exit_hibernation.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
    },
    {
      "addr": 18446744071588696208,
      "name": "dwc2_host_exit_hibernation",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1216
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
int dwc2_host_exit_hibernation(struct dwc2_hsotg * hsotg, int rem_wakeup, int reset)
```

```json
{
  "name": "dwc2_host_exit_hibernation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_host_exit_hibernation",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5600",
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
      "addr": 18446744071594473787,
      "name": "dwc2_host_exit_hibernation.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
    },
    {
      "addr": 18446744071590114464,
      "name": "dwc2_host_exit_hibernation",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1150
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
int dwc2_host_exit_hibernation(struct dwc2_hsotg * hsotg, int rem_wakeup, int reset)
```

```json
{
  "name": "dwc2_host_exit_hibernation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_host_exit_hibernation",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5573",
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
      "addr": 18446744071596290057,
      "name": "dwc2_host_exit_hibernation.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
    },
    {
      "addr": 18446744071591726544,
      "name": "dwc2_host_exit_hibernation",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1209
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
int dwc2_host_exit_hibernation(struct dwc2_hsotg * hsotg, int rem_wakeup, int reset)
```

```json
{
  "name": "dwc2_host_exit_hibernation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_host_exit_hibernation",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5573",
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
      "addr": 18446744071596819901,
      "name": "dwc2_host_exit_hibernation.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
    },
    {
      "addr": 18446744071592149936,
      "name": "dwc2_host_exit_hibernation",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1209
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
int dwc2_host_exit_hibernation(struct dwc2_hsotg * hsotg, int rem_wakeup, int reset)
```

```json
{
  "name": "dwc2_host_exit_hibernation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_host_exit_hibernation",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5573",
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
      "addr": 18446744071597743505,
      "name": "dwc2_host_exit_hibernation.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
    },
    {
      "addr": 18446744071592890560,
      "name": "dwc2_host_exit_hibernation",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1209
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
int dwc2_host_exit_hibernation(struct dwc2_hsotg * hsotg, int rem_wakeup, int reset)
```

```json
{
  "name": "dwc2_host_exit_hibernation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500412704,
      "name": "dwc2_host_exit_hibernation",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5480",
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
      "addr": 18446603336500412704,
      "name": "dwc2_host_exit_hibernation",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1160
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
int dwc2_host_exit_hibernation(struct dwc2_hsotg * hsotg, int rem_wakeup, int reset)
```

```json
{
  "name": "dwc2_host_exit_hibernation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232868432,
      "name": "dwc2_host_exit_hibernation",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5480",
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
      "addr": 3232868432,
      "name": "dwc2_host_exit_hibernation",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1144
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
int dwc2_host_exit_hibernation(struct dwc2_hsotg * hsotg, int rem_wakeup, int reset)
```

```json
{
  "name": "dwc2_host_exit_hibernation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293752368,
      "name": "dwc2_host_exit_hibernation",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5480",
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
      "addr": 13835058055293752368,
      "name": "dwc2_host_exit_hibernation",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1748
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
int dwc2_host_exit_hibernation(struct dwc2_hsotg * hsotg, int rem_wakeup, int reset)
```

```json
{
  "name": "dwc2_host_exit_hibernation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277303190,
      "name": "dwc2_host_exit_hibernation",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5480",
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
      "addr": 18446743936277303190,
      "name": "dwc2_host_exit_hibernation",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1596
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
int dwc2_host_exit_hibernation(struct dwc2_hsotg * hsotg, int rem_wakeup, int reset)
```

```json
{
  "name": "dwc2_host_exit_hibernation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_host_exit_hibernation",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5480",
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
      "addr": 18446744071587004658,
      "name": "dwc2_host_exit_hibernation.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071587002208,
      "name": "dwc2_host_exit_hibernation",
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int dwc2_host_exit_hibernation(struct dwc2_hsotg * hsotg, int rem_wakeup, int reset)
```

```json
{
  "name": "dwc2_host_exit_hibernation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_host_exit_hibernation",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5480",
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
      "addr": 18446744071587253138,
      "name": "dwc2_host_exit_hibernation.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071587250688,
      "name": "dwc2_host_exit_hibernation",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int dwc2_host_exit_hibernation(struct dwc2_hsotg * hsotg, int rem_wakeup, int reset)
```

```json
{
  "name": "dwc2_host_exit_hibernation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_host_exit_hibernation",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:5480",
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
      "addr": 18446744071587359906,
      "name": "dwc2_host_exit_hibernation.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071587357456,
      "name": "dwc2_host_exit_hibernation",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 880
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
int dwc2_host_exit_hibernation(struct dwc2_hsotg * hsotg, int rem_wakeup, int reset)
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
int dwc2_host_exit_hibernation(struct dwc2_hsotg * hsotg, int rem_wakeup, int reset)
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
