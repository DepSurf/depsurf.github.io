# Function: <code>dwc2_hcd_qh_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int dwc2_hcd_qh_add(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_hcd_qh_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585323056,
      "name": "dwc2_hcd_qh_add",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_queue.c:577",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qtd_add",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585323056,
      "name": "dwc2_hcd_qh_add",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dwc2_hcd_qh_add(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_hcd_qh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585717584,
      "name": "dwc2_hcd_qh_add",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_queue.c:1649",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qtd_add",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585717584,
      "name": "dwc2_hcd_qh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2436
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dwc2_hcd_qh_add(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_hcd_qh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585906208,
      "name": "dwc2_hcd_qh_add",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_queue.c:1652",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qtd_add",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585906208,
      "name": "dwc2_hcd_qh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2430
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dwc2_hcd_qh_add(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_hcd_qh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585988464,
      "name": "dwc2_hcd_qh_add",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_queue.c:1648",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qtd_add",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585988464,
      "name": "dwc2_hcd_qh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2203
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dwc2_hcd_qh_add(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_hcd_qh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586432432,
      "name": "dwc2_hcd_qh_add",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_queue.c:1648",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qtd_add",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586432432,
      "name": "dwc2_hcd_qh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2212
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
int dwc2_hcd_qh_add(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_hcd_qh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586696928,
      "name": "dwc2_hcd_qh_add",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_queue.c:1715",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qtd_add",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586696928,
      "name": "dwc2_hcd_qh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2313
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dwc2_hcd_qh_add(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_hcd_qh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586853984,
      "name": "dwc2_hcd_qh_add",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_queue.c:1719",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qtd_add",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586853984,
      "name": "dwc2_hcd_qh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2366
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int dwc2_hcd_qh_add(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_hcd_qh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587114267,
      "name": "dwc2_hcd_qh_add",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_queue.c:1721",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qtd_add",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587115997,
      "name": "dwc2_hcd_qh_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071587114128,
      "name": "dwc2_hcd_qh_add",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int dwc2_hcd_qh_add(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_hcd_qh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587314699,
      "name": "dwc2_hcd_qh_add",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_queue.c:1721",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qtd_add",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587316194,
      "name": "dwc2_hcd_qh_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071587314560,
      "name": "dwc2_hcd_qh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
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
int dwc2_hcd_qh_add(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_hcd_qh_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588171072,
      "name": "dwc2_hcd_qh_add",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_queue.c:1721",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qtd_add",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588171072,
      "name": "dwc2_hcd_qh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int dwc2_hcd_qh_add(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_hcd_qh_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588209168,
      "name": "dwc2_hcd_qh_add",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_queue.c:1721",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qtd_add",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588209168,
      "name": "dwc2_hcd_qh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int dwc2_hcd_qh_add(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_hcd_qh_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hcd_qh_add",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_queue.c:1721",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qtd_add",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591501333,
      "name": "dwc2_hcd_qh_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071588092144,
      "name": "dwc2_hcd_qh_add",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int dwc2_hcd_qh_add(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_hcd_qh_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hcd_qh_add",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_queue.c:1721",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qtd_add",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592599815,
      "name": "dwc2_hcd_qh_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071588725376,
      "name": "dwc2_hcd_qh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 647
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
int dwc2_hcd_qh_add(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_hcd_qh_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hcd_qh_add",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_queue.c:1721",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qtd_add",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594482490,
      "name": "dwc2_hcd_qh_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    },
    {
      "addr": 18446744071590143792,
      "name": "dwc2_hcd_qh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 609
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
int dwc2_hcd_qh_add(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_hcd_qh_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hcd_qh_add",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_queue.c:1691",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qtd_add",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596297468,
      "name": "dwc2_hcd_qh_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071591757984,
      "name": "dwc2_hcd_qh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 672
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
int dwc2_hcd_qh_add(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_hcd_qh_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hcd_qh_add",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_queue.c:1691",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qtd_add",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596827184,
      "name": "dwc2_hcd_qh_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071592181280,
      "name": "dwc2_hcd_qh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 672
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
int dwc2_hcd_qh_add(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_hcd_qh_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hcd_qh_add",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_queue.c:1691",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qtd_add",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597750841,
      "name": "dwc2_hcd_qh_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071592922000,
      "name": "dwc2_hcd_qh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 672
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int dwc2_hcd_qh_add(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_hcd_qh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500432280,
      "name": "dwc2_hcd_qh_add",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_queue.c:1721",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qtd_add",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500432280,
      "name": "dwc2_hcd_qh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int dwc2_hcd_qh_add(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_hcd_qh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232886588,
      "name": "dwc2_hcd_qh_add",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_queue.c:1721",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qtd_add",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232886588,
      "name": "dwc2_hcd_qh_add",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int dwc2_hcd_qh_add(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_hcd_qh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293780224,
      "name": "dwc2_hcd_qh_add",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_queue.c:1721",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qtd_add",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293780224,
      "name": "dwc2_hcd_qh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 784
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int dwc2_hcd_qh_add(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_hcd_qh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277321762,
      "name": "dwc2_hcd_qh_add",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_queue.c:1721",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qtd_add",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277321762,
      "name": "dwc2_hcd_qh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 618
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int dwc2_hcd_qh_add(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_hcd_qh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587020779,
      "name": "dwc2_hcd_qh_add",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_queue.c:1721",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qtd_add",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587022274,
      "name": "dwc2_hcd_qh_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071587020640,
      "name": "dwc2_hcd_qh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int dwc2_hcd_qh_add(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_hcd_qh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587269259,
      "name": "dwc2_hcd_qh_add",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_queue.c:1721",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qtd_add",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587270754,
      "name": "dwc2_hcd_qh_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071587269120,
      "name": "dwc2_hcd_qh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int dwc2_hcd_qh_add(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_hcd_qh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587376027,
      "name": "dwc2_hcd_qh_add",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd_queue.c:1721",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qtd_add",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587377522,
      "name": "dwc2_hcd_qh_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071587375888,
      "name": "dwc2_hcd_qh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
int dwc2_hcd_qh_add(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
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
