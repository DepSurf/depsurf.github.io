# Function: <code>dwc2_core_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int dwc2_core_init(struct dwc2_hsotg * hsotg, bool select_phy, int irq)
```

```json
{
  "name": "dwc2_core_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585276448,
      "name": "dwc2_core_init",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:772",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585276448,
      "name": "dwc2_core_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1674
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int dwc2_core_init(struct dwc2_hsotg * hsotg, bool initial_setup)
```

```json
{
  "name": "dwc2_core_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585684544,
      "name": "dwc2_core_init",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:2177",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585684544,
      "name": "dwc2_core_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1598
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
int dwc2_core_init(struct dwc2_hsotg * hsotg, bool initial_setup)
```

```json
{
  "name": "dwc2_core_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585873552,
      "name": "dwc2_core_init",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:2207",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585873552,
      "name": "dwc2_core_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1569
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
int dwc2_core_init(struct dwc2_hsotg * hsotg, bool initial_setup)
```

```json
{
  "name": "dwc2_core_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585956432,
      "name": "dwc2_core_init",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:2224",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585956432,
      "name": "dwc2_core_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1524
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
int dwc2_core_init(struct dwc2_hsotg * hsotg, bool initial_setup)
```

```json
{
  "name": "dwc2_core_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586400032,
      "name": "dwc2_core_init",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:2230",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586400032,
      "name": "dwc2_core_init",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int dwc2_core_init(struct dwc2_hsotg * hsotg, bool initial_setup)
```

```json
{
  "name": "dwc2_core_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586669904,
      "name": "dwc2_core_init",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2275",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586669904,
      "name": "dwc2_core_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1337
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
int dwc2_core_init(struct dwc2_hsotg * hsotg, bool initial_setup)
```

```json
{
  "name": "dwc2_core_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586824128,
      "name": "dwc2_core_init",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2265",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586824128,
      "name": "dwc2_core_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1818
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
int dwc2_core_init(struct dwc2_hsotg * hsotg, bool initial_setup)
```

```json
{
  "name": "dwc2_core_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_core_init",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2075",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587097345,
      "name": "dwc2_core_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071587082368,
      "name": "dwc2_core_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 799
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
int dwc2_core_init(struct dwc2_hsotg * hsotg, bool initial_setup)
```

```json
{
  "name": "dwc2_core_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_core_init",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2075",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587297836,
      "name": "dwc2_core_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071587282848,
      "name": "dwc2_core_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 799
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
int dwc2_core_init(struct dwc2_hsotg * hsotg, bool initial_setup)
```

```json
{
  "name": "dwc2_core_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_core_init",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2075",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588153137,
      "name": "dwc2_core_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071588138752,
      "name": "dwc2_core_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
int dwc2_core_init(struct dwc2_hsotg * hsotg, bool initial_setup)
```

```json
{
  "name": "dwc2_core_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_core_init",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2076",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591557032,
      "name": "dwc2_core_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071588179280,
      "name": "dwc2_core_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
int dwc2_core_init(struct dwc2_hsotg * hsotg, bool initial_setup)
```

```json
{
  "name": "dwc2_core_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_core_init",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2074",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc_handle_gpwrdn_disc_det",
        "drivers/usb/dwc2/core_intr.c:dwc_handle_gpwrdn_disc_det",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591499066,
      "name": "dwc2_core_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071588056288,
      "name": "dwc2_core_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 820
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
int dwc2_core_init(struct dwc2_hsotg * hsotg, bool initial_setup)
```

```json
{
  "name": "dwc2_core_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_core_init",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2074",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592588320,
      "name": "dwc2_core_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
    },
    {
      "addr": 18446744071588681792,
      "name": "dwc2_core_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 972
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
int dwc2_core_init(struct dwc2_hsotg * hsotg, bool initial_setup)
```

```json
{
  "name": "dwc2_core_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_core_init",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2070",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594469112,
      "name": "dwc2_core_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
    },
    {
      "addr": 18446744071590100080,
      "name": "dwc2_core_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1007
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
int dwc2_core_init(struct dwc2_hsotg * hsotg, bool initial_setup)
```

```json
{
  "name": "dwc2_core_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_core_init",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2041",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596285787,
      "name": "dwc2_core_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 402
    },
    {
      "addr": 18446744071591711280,
      "name": "dwc2_core_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1067
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
int dwc2_core_init(struct dwc2_hsotg * hsotg, bool initial_setup)
```

```json
{
  "name": "dwc2_core_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_core_init",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2041",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596815662,
      "name": "dwc2_core_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
    },
    {
      "addr": 18446744071592134688,
      "name": "dwc2_core_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1049
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
int dwc2_core_init(struct dwc2_hsotg * hsotg, bool initial_setup)
```

```json
{
  "name": "dwc2_core_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_core_init",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2041",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597739269,
      "name": "dwc2_core_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
    },
    {
      "addr": 18446744071592875216,
      "name": "dwc2_core_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1049
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
int dwc2_core_init(struct dwc2_hsotg * hsotg, bool initial_setup)
```

```json
{
  "name": "dwc2_core_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500397656,
      "name": "dwc2_core_init",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2075",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500397656,
      "name": "dwc2_core_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 964
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
int dwc2_core_init(struct dwc2_hsotg * hsotg, bool initial_setup)
```

```json
{
  "name": "dwc2_core_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232853560,
      "name": "dwc2_core_init",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2075",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232853560,
      "name": "dwc2_core_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 992
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
int dwc2_core_init(struct dwc2_hsotg * hsotg, bool initial_setup)
```

```json
{
  "name": "dwc2_core_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293728160,
      "name": "dwc2_core_init",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2075",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293728160,
      "name": "dwc2_core_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1692
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
int dwc2_core_init(struct dwc2_hsotg * hsotg, bool initial_setup)
```

```json
{
  "name": "dwc2_core_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277286234,
      "name": "dwc2_core_init",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2075",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277286234,
      "name": "dwc2_core_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1312
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
int dwc2_core_init(struct dwc2_hsotg * hsotg, bool initial_setup)
```

```json
{
  "name": "dwc2_core_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_core_init",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2075",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587003916,
      "name": "dwc2_core_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071586988928,
      "name": "dwc2_core_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 799
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
int dwc2_core_init(struct dwc2_hsotg * hsotg, bool initial_setup)
```

```json
{
  "name": "dwc2_core_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_core_init",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2075",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587252396,
      "name": "dwc2_core_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071587237408,
      "name": "dwc2_core_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 799
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
int dwc2_core_init(struct dwc2_hsotg * hsotg, bool initial_setup)
```

```json
{
  "name": "dwc2_core_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_core_init",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:2075",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587359164,
      "name": "dwc2_core_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071587344176,
      "name": "dwc2_core_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 799
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool initial_setup</code>
</li>
<li>
<b>Param removed. </b>
<code>bool select_phy</code>
</li>
<li>
<b>Param removed. </b>
<code>int irq</code>
</li>
</ul>
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
int dwc2_core_init(struct dwc2_hsotg * hsotg, bool initial_setup)
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
