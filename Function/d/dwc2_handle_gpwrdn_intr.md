# Function: <code>dwc2_handle_gpwrdn_intr</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_handle_gpwrdn_intr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586648446,
      "name": "dwc2_handle_gpwrdn_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:651",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
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
  "name": "dwc2_handle_gpwrdn_intr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586799088,
      "name": "dwc2_handle_gpwrdn_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:651",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void dwc2_handle_gpwrdn_intr(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_handle_gpwrdn_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587054640,
      "name": "dwc2_handle_gpwrdn_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:663",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587054640,
      "name": "dwc2_handle_gpwrdn_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1109
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
void dwc2_handle_gpwrdn_intr(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_handle_gpwrdn_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587255008,
      "name": "dwc2_handle_gpwrdn_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:663",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587255008,
      "name": "dwc2_handle_gpwrdn_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1109
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
void dwc2_handle_gpwrdn_intr(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_handle_gpwrdn_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588109488,
      "name": "dwc2_handle_gpwrdn_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:661",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588109488,
      "name": "dwc2_handle_gpwrdn_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1109
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
void dwc2_handle_gpwrdn_intr(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_handle_gpwrdn_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588150928,
      "name": "dwc2_handle_gpwrdn_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:661",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588150928,
      "name": "dwc2_handle_gpwrdn_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_handle_gpwrdn_intr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_handle_gpwrdn_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:753",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588033456,
      "name": "dwc2_handle_gpwrdn_intr.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
    },
    {
      "addr": 18446744071591496498,
      "name": "dwc2_handle_gpwrdn_intr.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_handle_gpwrdn_intr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_handle_gpwrdn_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:753",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588652912,
      "name": "dwc2_handle_gpwrdn_intr.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
    },
    {
      "addr": 18446744071592578134,
      "name": "dwc2_handle_gpwrdn_intr.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_handle_gpwrdn_intr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_handle_gpwrdn_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:753",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590069632,
      "name": "dwc2_handle_gpwrdn_intr.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
    },
    {
      "addr": 18446744071594458596,
      "name": "dwc2_handle_gpwrdn_intr.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_handle_gpwrdn_intr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_handle_gpwrdn_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:723",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591677344,
      "name": "dwc2_handle_gpwrdn_intr.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 588
    },
    {
      "addr": 18446744071596277492,
      "name": "dwc2_handle_gpwrdn_intr.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_handle_gpwrdn_intr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_handle_gpwrdn_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:723",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592100256,
      "name": "dwc2_handle_gpwrdn_intr.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
    },
    {
      "addr": 18446744071596807338,
      "name": "dwc2_handle_gpwrdn_intr.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_handle_gpwrdn_intr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_handle_gpwrdn_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:723",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592840688,
      "name": "dwc2_handle_gpwrdn_intr.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
    },
    {
      "addr": 18446744071597730945,
      "name": "dwc2_handle_gpwrdn_intr.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void dwc2_handle_gpwrdn_intr(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_handle_gpwrdn_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500364656,
      "name": "dwc2_handle_gpwrdn_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:663",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500364656,
      "name": "dwc2_handle_gpwrdn_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1256
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
void dwc2_handle_gpwrdn_intr(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_handle_gpwrdn_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232823368,
      "name": "dwc2_handle_gpwrdn_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:663",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232823368,
      "name": "dwc2_handle_gpwrdn_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1208
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
void dwc2_handle_gpwrdn_intr(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_handle_gpwrdn_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293677968,
      "name": "dwc2_handle_gpwrdn_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:663",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293677968,
      "name": "dwc2_handle_gpwrdn_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1932
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
void dwc2_handle_gpwrdn_intr(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_handle_gpwrdn_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277249796,
      "name": "dwc2_handle_gpwrdn_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:663",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277249796,
      "name": "dwc2_handle_gpwrdn_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1722
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
void dwc2_handle_gpwrdn_intr(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_handle_gpwrdn_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586961088,
      "name": "dwc2_handle_gpwrdn_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:663",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586961088,
      "name": "dwc2_handle_gpwrdn_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1109
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
void dwc2_handle_gpwrdn_intr(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_handle_gpwrdn_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587209568,
      "name": "dwc2_handle_gpwrdn_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:663",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587209568,
      "name": "dwc2_handle_gpwrdn_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1109
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
void dwc2_handle_gpwrdn_intr(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_handle_gpwrdn_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587316640,
      "name": "dwc2_handle_gpwrdn_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:663",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587316640,
      "name": "dwc2_handle_gpwrdn_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1109
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
void dwc2_handle_gpwrdn_intr(struct dwc2_hsotg * hsotg)
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void dwc2_handle_gpwrdn_intr(struct dwc2_hsotg * hsotg)
```
</details>
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
void dwc2_handle_gpwrdn_intr(struct dwc2_hsotg * hsotg)
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
