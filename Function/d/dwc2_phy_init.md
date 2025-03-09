# Function: <code>dwc2_phy_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_phy_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585276569,
      "name": "dwc2_phy_init",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:647",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_core_init"
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
  "name": "dwc2_phy_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585684657,
      "name": "dwc2_phy_init",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:228",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
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
  "name": "dwc2_phy_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585873666,
      "name": "dwc2_phy_init",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:228",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
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
  "name": "dwc2_phy_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585956532,
      "name": "dwc2_phy_init",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:244",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
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
  "name": "dwc2_phy_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586400132,
      "name": "dwc2_phy_init",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:250",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_phy_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586670006,
      "name": "dwc2_phy_init",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:253",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_phy_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586824254,
      "name": "dwc2_phy_init",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:253",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int dwc2_phy_init(struct dwc2_hsotg * hsotg, bool select_phy)
```

```json
{
  "name": "dwc2_phy_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_phy_init",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1185",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587054548,
      "name": "dwc2_phy_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071587053152,
      "name": "dwc2_phy_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 946
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
int dwc2_phy_init(struct dwc2_hsotg * hsotg, bool select_phy)
```

```json
{
  "name": "dwc2_phy_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_phy_init",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1185",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587254910,
      "name": "dwc2_phy_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071587253552,
      "name": "dwc2_phy_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 946
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
int dwc2_phy_init(struct dwc2_hsotg * hsotg, bool select_phy)
```

```json
{
  "name": "dwc2_phy_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588108800,
      "name": "dwc2_phy_init",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1200",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588108800,
      "name": "dwc2_phy_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int dwc2_phy_init(struct dwc2_hsotg * hsotg, bool select_phy)
```

```json
{
  "name": "dwc2_phy_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588150560,
      "name": "dwc2_phy_init",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1200",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588150560,
      "name": "dwc2_phy_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int dwc2_phy_init(struct dwc2_hsotg * hsotg, bool select_phy)
```

```json
{
  "name": "dwc2_phy_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588032192,
      "name": "dwc2_phy_init",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1153",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588032192,
      "name": "dwc2_phy_init",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int dwc2_phy_init(struct dwc2_hsotg * hsotg, bool select_phy)
```

```json
{
  "name": "dwc2_phy_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_phy_init",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1153",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592577412,
      "name": "dwc2_phy_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071588651360,
      "name": "dwc2_phy_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 569
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
int dwc2_phy_init(struct dwc2_hsotg * hsotg, bool select_phy)
```

```json
{
  "name": "dwc2_phy_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_phy_init",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1153",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594457561,
      "name": "dwc2_phy_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    },
    {
      "addr": 18446744071590068192,
      "name": "dwc2_phy_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 593
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
int dwc2_phy_init(struct dwc2_hsotg * hsotg, bool select_phy)
```

```json
{
  "name": "dwc2_phy_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_phy_init",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1123",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596276504,
      "name": "dwc2_phy_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    },
    {
      "addr": 18446744071591676048,
      "name": "dwc2_phy_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 593
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
int dwc2_phy_init(struct dwc2_hsotg * hsotg, bool select_phy)
```

```json
{
  "name": "dwc2_phy_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_phy_init",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1123",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596806350,
      "name": "dwc2_phy_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    },
    {
      "addr": 18446744071592098960,
      "name": "dwc2_phy_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 593
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
int dwc2_phy_init(struct dwc2_hsotg * hsotg, bool select_phy)
```

```json
{
  "name": "dwc2_phy_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_phy_init",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1123",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597729957,
      "name": "dwc2_phy_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    },
    {
      "addr": 18446744071592839392,
      "name": "dwc2_phy_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 593
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
int dwc2_phy_init(struct dwc2_hsotg * hsotg, bool select_phy)
```

```json
{
  "name": "dwc2_phy_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500363208,
      "name": "dwc2_phy_init",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1185",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500363208,
      "name": "dwc2_phy_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1444
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
int dwc2_phy_init(struct dwc2_hsotg * hsotg, bool select_phy)
```

```json
{
  "name": "dwc2_phy_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232821088,
      "name": "dwc2_phy_init",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1185",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232821088,
      "name": "dwc2_phy_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1320
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
int dwc2_phy_init(struct dwc2_hsotg * hsotg, bool select_phy)
```

```json
{
  "name": "dwc2_phy_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293675536,
      "name": "dwc2_phy_init",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1185",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293675536,
      "name": "dwc2_phy_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2428
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
int dwc2_phy_init(struct dwc2_hsotg * hsotg, bool select_phy)
```

```json
{
  "name": "dwc2_phy_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277247816,
      "name": "dwc2_phy_init",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1185",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277247816,
      "name": "dwc2_phy_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1980
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
int dwc2_phy_init(struct dwc2_hsotg * hsotg, bool select_phy)
```

```json
{
  "name": "dwc2_phy_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_phy_init",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1185",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586960990,
      "name": "dwc2_phy_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071586959632,
      "name": "dwc2_phy_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 946
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
int dwc2_phy_init(struct dwc2_hsotg * hsotg, bool select_phy)
```

```json
{
  "name": "dwc2_phy_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_phy_init",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1185",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587209470,
      "name": "dwc2_phy_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071587208112,
      "name": "dwc2_phy_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 946
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
int dwc2_phy_init(struct dwc2_hsotg * hsotg, bool select_phy)
```

```json
{
  "name": "dwc2_phy_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_phy_init",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1185",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587316542,
      "name": "dwc2_phy_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071587315184,
      "name": "dwc2_phy_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 946
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int dwc2_phy_init(struct dwc2_hsotg * hsotg, bool select_phy)
```
</details>
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
int dwc2_phy_init(struct dwc2_hsotg * hsotg, bool select_phy)
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
