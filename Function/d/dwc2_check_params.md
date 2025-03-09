# Function: <code>dwc2_check_params</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_check_params",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585950637,
      "name": "dwc2_check_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:502",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
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
  "name": "dwc2_check_params",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586394017,
      "name": "dwc2_check_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:516",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
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
void dwc2_check_params(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_check_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586653232,
      "name": "dwc2_check_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:575",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/params.c:dwc2_init_params",
        "drivers/usb/dwc2/params.c:dwc2_init_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586653232,
      "name": "dwc2_check_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2560
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
void dwc2_check_params(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_check_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586805088,
      "name": "dwc2_check_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:584",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/params.c:dwc2_init_params",
        "drivers/usb/dwc2/params.c:dwc2_init_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586805088,
      "name": "dwc2_check_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2626
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
void dwc2_check_params(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_check_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_check_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:619",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/params.c:dwc2_init_params",
        "drivers/usb/dwc2/params.c:dwc2_init_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587063360,
      "name": "dwc2_check_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1428
    },
    {
      "addr": 18446744071587066493,
      "name": "dwc2_check_params.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1571
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
void dwc2_check_params(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_check_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_check_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:616",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/params.c:dwc2_init_params",
        "drivers/usb/dwc2/params.c:dwc2_init_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587263696,
      "name": "dwc2_check_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1428
    },
    {
      "addr": 18446744071587266829,
      "name": "dwc2_check_params.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1571
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
void dwc2_check_params(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_check_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_check_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:649",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/params.c:dwc2_init_params",
        "drivers/usb/dwc2/params.c:dwc2_init_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588118816,
      "name": "dwc2_check_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1300
    },
    {
      "addr": 18446744071588121699,
      "name": "dwc2_check_params.cold",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void dwc2_check_params(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_check_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_check_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:650",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/params.c:dwc2_init_params",
        "drivers/usb/dwc2/params.c:dwc2_init_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588161056,
      "name": "dwc2_check_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1300
    },
    {
      "addr": 18446744071591554815,
      "name": "dwc2_check_params.cold",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void dwc2_check_params(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_check_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_check_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:665",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588043136,
      "name": "dwc2_check_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1241
    },
    {
      "addr": 18446744071591497127,
      "name": "dwc2_check_params.cold",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void dwc2_check_params(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_check_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_check_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:665",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588665600,
      "name": "dwc2_check_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1531
    },
    {
      "addr": 18446744071592582018,
      "name": "dwc2_check_params.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2702
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
void dwc2_check_params(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_check_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_check_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:732",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590083408,
      "name": "dwc2_check_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1751
    },
    {
      "addr": 18446744071594462293,
      "name": "dwc2_check_params.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2784
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
void dwc2_check_params(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_check_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_check_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:706",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591692176,
      "name": "dwc2_check_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3289
    },
    {
      "addr": 18446744071596280902,
      "name": "dwc2_check_params.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1368
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
void dwc2_check_params(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_check_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_check_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:726",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592115552,
      "name": "dwc2_check_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3281
    },
    {
      "addr": 18446744071596810777,
      "name": "dwc2_check_params.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1368
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
void dwc2_check_params(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_check_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_check_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:757",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592856048,
      "name": "dwc2_check_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3281
    },
    {
      "addr": 18446744071597734384,
      "name": "dwc2_check_params.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1368
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
void dwc2_check_params(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_check_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500375016,
      "name": "dwc2_check_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:616",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500375016,
      "name": "dwc2_check_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2648
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
void dwc2_check_params(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_check_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232831808,
      "name": "dwc2_check_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:616",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232831808,
      "name": "dwc2_check_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2808
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
void dwc2_check_params(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_check_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293693536,
      "name": "dwc2_check_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:616",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293693536,
      "name": "dwc2_check_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3700
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
void dwc2_check_params(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_check_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277261222,
      "name": "dwc2_check_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:616",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277261222,
      "name": "dwc2_check_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2374
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
void dwc2_check_params(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_check_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_check_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:616",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/params.c:dwc2_init_params",
        "drivers/usb/dwc2/params.c:dwc2_init_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586969776,
      "name": "dwc2_check_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1428
    },
    {
      "addr": 18446744071586972909,
      "name": "dwc2_check_params.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1571
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
void dwc2_check_params(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_check_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_check_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:616",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/params.c:dwc2_init_params",
        "drivers/usb/dwc2/params.c:dwc2_init_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587218256,
      "name": "dwc2_check_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1428
    },
    {
      "addr": 18446744071587221389,
      "name": "dwc2_check_params.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1571
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
void dwc2_check_params(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_check_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_check_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:616",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/params.c:dwc2_init_params",
        "drivers/usb/dwc2/params.c:dwc2_init_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587325024,
      "name": "dwc2_check_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1428
    },
    {
      "addr": 18446744071587328157,
      "name": "dwc2_check_params.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1571
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
void dwc2_check_params(struct dwc2_hsotg * hsotg)
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
void dwc2_check_params(struct dwc2_hsotg * hsotg)
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
