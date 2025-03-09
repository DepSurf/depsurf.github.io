# Function: <code>dwc2_hc_n_intr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_hc_n_intr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585318743,
      "name": "dwc2_hc_n_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:1971",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr"
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
void dwc2_hc_n_intr(struct dwc2_hsotg * hsotg, int chnum)
```

```json
{
  "name": "dwc2_hc_n_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585711040,
      "name": "dwc2_hc_n_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:1977",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585711040,
      "name": "dwc2_hc_n_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2559
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
void dwc2_hc_n_intr(struct dwc2_hsotg * hsotg, int chnum)
```

```json
{
  "name": "dwc2_hc_n_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585899712,
      "name": "dwc2_hc_n_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:1982",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585899712,
      "name": "dwc2_hc_n_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2537
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
void dwc2_hc_n_intr(struct dwc2_hsotg * hsotg, int chnum)
```

```json
{
  "name": "dwc2_hc_n_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585982304,
      "name": "dwc2_hc_n_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:1986",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585982304,
      "name": "dwc2_hc_n_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2279
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
void dwc2_hc_n_intr(struct dwc2_hsotg * hsotg, int chnum)
```

```json
{
  "name": "dwc2_hc_n_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586426256,
      "name": "dwc2_hc_n_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:1987",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586426256,
      "name": "dwc2_hc_n_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2303
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
void dwc2_hc_n_intr(struct dwc2_hsotg * hsotg, int chnum)
```

```json
{
  "name": "dwc2_hc_n_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586690208,
      "name": "dwc2_hc_n_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:2031",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586690208,
      "name": "dwc2_hc_n_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2490
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
void dwc2_hc_n_intr(struct dwc2_hsotg * hsotg, int chnum)
```

```json
{
  "name": "dwc2_hc_n_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586846560,
      "name": "dwc2_hc_n_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:2031",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586846560,
      "name": "dwc2_hc_n_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2664
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
void dwc2_hc_n_intr(struct dwc2_hsotg * hsotg, int chnum)
```

```json
{
  "name": "dwc2_hc_n_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hc_n_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:2032",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587105088,
      "name": "dwc2_hc_n_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1450
    },
    {
      "addr": 18446744071587109094,
      "name": "dwc2_hc_n_intr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
void dwc2_hc_n_intr(struct dwc2_hsotg * hsotg, int chnum)
```

```json
{
  "name": "dwc2_hc_n_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hc_n_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:2032",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587305520,
      "name": "dwc2_hc_n_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1454
    },
    {
      "addr": 18446744071587309526,
      "name": "dwc2_hc_n_intr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void dwc2_hc_n_intr(struct dwc2_hsotg * hsotg, int chnum)
```

```json
{
  "name": "dwc2_hc_n_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hc_n_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:2032",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588162784,
      "name": "dwc2_hc_n_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1453
    },
    {
      "addr": 18446744071588165703,
      "name": "dwc2_hc_n_intr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void dwc2_hc_n_intr(struct dwc2_hsotg * hsotg, int chnum)
```

```json
{
  "name": "dwc2_hc_n_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hc_n_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:2044",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588201792,
      "name": "dwc2_hc_n_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1453
    },
    {
      "addr": 18446744071591558544,
      "name": "dwc2_hc_n_intr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void dwc2_hc_n_intr(struct dwc2_hsotg * hsotg, int chnum)
```

```json
{
  "name": "dwc2_hc_n_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hc_n_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:2044",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588084896,
      "name": "dwc2_hc_n_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1453
    },
    {
      "addr": 18446744071591501135,
      "name": "dwc2_hc_n_intr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void dwc2_hc_n_intr(struct dwc2_hsotg * hsotg, int chnum)
```

```json
{
  "name": "dwc2_hc_n_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hc_n_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:2044",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588716976,
      "name": "dwc2_hc_n_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1638
    },
    {
      "addr": 18446744071592598548,
      "name": "dwc2_hc_n_intr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
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
void dwc2_hc_n_intr(struct dwc2_hsotg * hsotg, int chnum)
```

```json
{
  "name": "dwc2_hc_n_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hc_n_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:2044",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590134912,
      "name": "dwc2_hc_n_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1797
    },
    {
      "addr": 18446744071594481092,
      "name": "dwc2_hc_n_intr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
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
void dwc2_hc_n_intr(struct dwc2_hsotg * hsotg, int chnum)
```

```json
{
  "name": "dwc2_hc_n_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hc_n_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:2014",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591748768,
      "name": "dwc2_hc_n_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1807
    },
    {
      "addr": 18446744071596296229,
      "name": "dwc2_hc_n_intr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 531
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
void dwc2_hc_n_intr(struct dwc2_hsotg * hsotg, int chnum)
```

```json
{
  "name": "dwc2_hc_n_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hc_n_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:2014",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592172288,
      "name": "dwc2_hc_n_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1663
    },
    {
      "addr": 18446744071596826082,
      "name": "dwc2_hc_n_intr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
void dwc2_hc_n_intr(struct dwc2_hsotg * hsotg, int chnum)
```

```json
{
  "name": "dwc2_hc_n_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hc_n_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:2014",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592912944,
      "name": "dwc2_hc_n_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1693
    },
    {
      "addr": 18446744071597749686,
      "name": "dwc2_hc_n_intr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
void dwc2_hc_n_intr(struct dwc2_hsotg * hsotg, int chnum)
```

```json
{
  "name": "dwc2_hc_n_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500423528,
      "name": "dwc2_hc_n_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:2032",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500423528,
      "name": "dwc2_hc_n_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1424
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
void dwc2_hc_n_intr(struct dwc2_hsotg * hsotg, int chnum)
```

```json
{
  "name": "dwc2_hc_n_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232878116,
      "name": "dwc2_hc_n_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:2032",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232878116,
      "name": "dwc2_hc_n_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1468
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
void dwc2_hc_n_intr(struct dwc2_hsotg * hsotg, int chnum)
```

```json
{
  "name": "dwc2_hc_n_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293767936,
      "name": "dwc2_hc_n_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:2032",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293767936,
      "name": "dwc2_hc_n_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2156
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
void dwc2_hc_n_intr(struct dwc2_hsotg * hsotg, int chnum)
```

```json
{
  "name": "dwc2_hc_n_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277313662,
      "name": "dwc2_hc_n_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:2032",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277313662,
      "name": "dwc2_hc_n_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1418
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
void dwc2_hc_n_intr(struct dwc2_hsotg * hsotg, int chnum)
```

```json
{
  "name": "dwc2_hc_n_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hc_n_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:2032",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587011600,
      "name": "dwc2_hc_n_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1454
    },
    {
      "addr": 18446744071587015606,
      "name": "dwc2_hc_n_intr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void dwc2_hc_n_intr(struct dwc2_hsotg * hsotg, int chnum)
```

```json
{
  "name": "dwc2_hc_n_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hc_n_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:2032",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587260080,
      "name": "dwc2_hc_n_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1454
    },
    {
      "addr": 18446744071587264086,
      "name": "dwc2_hc_n_intr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void dwc2_hc_n_intr(struct dwc2_hsotg * hsotg, int chnum)
```

```json
{
  "name": "dwc2_hc_n_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hc_n_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_intr.c:2032",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587366848,
      "name": "dwc2_hc_n_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1454
    },
    {
      "addr": 18446744071587370850,
      "name": "dwc2_hc_n_intr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void dwc2_hc_n_intr(struct dwc2_hsotg * hsotg, int chnum)
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
void dwc2_hc_n_intr(struct dwc2_hsotg * hsotg, int chnum)
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
