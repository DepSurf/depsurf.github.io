# Function: <code>dwc2_enable_common_interrupts</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_enable_common_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585274432,
      "name": "dwc2_enable_common_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:430",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_core_init",
        "drivers/usb/dwc2/core.c:dwc2_enable_host_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585274432,
      "name": "dwc2_enable_common_interrupts.isra.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_enable_common_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585682227,
      "name": "dwc2_enable_common_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:69",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
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
  "name": "dwc2_enable_common_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585871194,
      "name": "dwc2_enable_common_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:69",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
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
  "name": "dwc2_enable_common_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585954076,
      "name": "dwc2_enable_common_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:72",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
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
  "name": "dwc2_enable_common_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586397598,
      "name": "dwc2_enable_common_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:73",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void dwc2_enable_common_interrupts(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_enable_common_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586657328,
      "name": "dwc2_enable_common_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:73",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586657328,
      "name": "dwc2_enable_common_interrupts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void dwc2_enable_common_interrupts(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_enable_common_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586809408,
      "name": "dwc2_enable_common_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:73",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586809408,
      "name": "dwc2_enable_common_interrupts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void dwc2_enable_common_interrupts(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_enable_common_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587068096,
      "name": "dwc2_enable_common_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:73",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587068096,
      "name": "dwc2_enable_common_interrupts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
void dwc2_enable_common_interrupts(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_enable_common_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587268432,
      "name": "dwc2_enable_common_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:73",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587268432,
      "name": "dwc2_enable_common_interrupts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
void dwc2_enable_common_interrupts(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_enable_common_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588123760,
      "name": "dwc2_enable_common_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:73",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_init",
        "drivers/usb/dwc2/hcd.c:dwc2_enable_host_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588123760,
      "name": "dwc2_enable_common_interrupts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
void dwc2_enable_common_interrupts(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_enable_common_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588164544,
      "name": "dwc2_enable_common_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:73",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_init",
        "drivers/usb/dwc2/hcd.c:dwc2_enable_host_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588164544,
      "name": "dwc2_enable_common_interrupts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
void dwc2_enable_common_interrupts(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_enable_common_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588046480,
      "name": "dwc2_enable_common_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:71",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588046480,
      "name": "dwc2_enable_common_interrupts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void dwc2_enable_common_interrupts(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_enable_common_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_enable_common_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:71",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588672112,
      "name": "dwc2_enable_common_interrupts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    },
    {
      "addr": 18446744071592585549,
      "name": "dwc2_enable_common_interrupts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
void dwc2_enable_common_interrupts(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_enable_common_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_enable_common_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:71",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590090464,
      "name": "dwc2_enable_common_interrupts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
    },
    {
      "addr": 18446744071594465985,
      "name": "dwc2_enable_common_interrupts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
void dwc2_enable_common_interrupts(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_enable_common_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_enable_common_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:42",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591701136,
      "name": "dwc2_enable_common_interrupts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
    },
    {
      "addr": 18446744071596282911,
      "name": "dwc2_enable_common_interrupts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
void dwc2_enable_common_interrupts(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_enable_common_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_enable_common_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:42",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592124512,
      "name": "dwc2_enable_common_interrupts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
    },
    {
      "addr": 18446744071596812786,
      "name": "dwc2_enable_common_interrupts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
void dwc2_enable_common_interrupts(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_enable_common_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_enable_common_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:42",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592865040,
      "name": "dwc2_enable_common_interrupts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
    },
    {
      "addr": 18446744071597736393,
      "name": "dwc2_enable_common_interrupts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
void dwc2_enable_common_interrupts(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_enable_common_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500382432,
      "name": "dwc2_enable_common_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:73",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500382432,
      "name": "dwc2_enable_common_interrupts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
void dwc2_enable_common_interrupts(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_enable_common_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232838828,
      "name": "dwc2_enable_common_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:73",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232838828,
      "name": "dwc2_enable_common_interrupts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
void dwc2_enable_common_interrupts(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_enable_common_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293704160,
      "name": "dwc2_enable_common_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:73",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293704160,
      "name": "dwc2_enable_common_interrupts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
void dwc2_enable_common_interrupts(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_enable_common_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277268922,
      "name": "dwc2_enable_common_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:73",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277268922,
      "name": "dwc2_enable_common_interrupts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
void dwc2_enable_common_interrupts(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_enable_common_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586974512,
      "name": "dwc2_enable_common_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:73",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586974512,
      "name": "dwc2_enable_common_interrupts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
void dwc2_enable_common_interrupts(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_enable_common_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587222992,
      "name": "dwc2_enable_common_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:73",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587222992,
      "name": "dwc2_enable_common_interrupts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
void dwc2_enable_common_interrupts(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_enable_common_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587329760,
      "name": "dwc2_enable_common_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:73",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587329760,
      "name": "dwc2_enable_common_interrupts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
void dwc2_enable_common_interrupts(struct dwc2_hsotg * hsotg)
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
void dwc2_enable_common_interrupts(struct dwc2_hsotg * hsotg)
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
