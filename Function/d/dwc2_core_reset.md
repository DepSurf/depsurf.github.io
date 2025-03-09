# Function: <code>dwc2_core_reset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dwc2_core_reset(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_core_reset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585274800,
      "name": "dwc2_core_reset",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:484",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_core_init",
        "drivers/usb/dwc2/core.c:dwc2_core_init",
        "drivers/usb/dwc2/core.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585274800,
      "name": "dwc2_core_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
int dwc2_core_reset(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_core_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585669024,
      "name": "dwc2_core_reset",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:245",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_core_reset_and_force_dr_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585669024,
      "name": "dwc2_core_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int dwc2_core_reset(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_core_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585856976,
      "name": "dwc2_core_reset",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:316",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_core_reset_and_force_dr_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585856976,
      "name": "dwc2_core_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
int dwc2_core_reset(struct dwc2_hsotg * hsotg, bool skip_wait)
```

```json
{
  "name": "dwc2_core_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585943456,
      "name": "dwc2_core_reset",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:316",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_core_reset_and_force_dr_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585943456,
      "name": "dwc2_core_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
int dwc2_core_reset(struct dwc2_hsotg * hsotg, bool skip_wait)
```

```json
{
  "name": "dwc2_core_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586386560,
      "name": "dwc2_core_reset",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:317",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_core_reset_and_force_dr_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586386560,
      "name": "dwc2_core_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
int dwc2_core_reset(struct dwc2_hsotg * hsotg, bool skip_wait)
```

```json
{
  "name": "dwc2_core_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586644848,
      "name": "dwc2_core_reset",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:495",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586644848,
      "name": "dwc2_core_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
int dwc2_core_reset(struct dwc2_hsotg * hsotg, bool skip_wait)
```

```json
{
  "name": "dwc2_core_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586796320,
      "name": "dwc2_core_reset",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:495",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586796320,
      "name": "dwc2_core_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
int dwc2_core_reset(struct dwc2_hsotg * hsotg, bool skip_wait)
```

```json
{
  "name": "dwc2_core_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_core_reset",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:495",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587054372,
      "name": "dwc2_core_reset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071587052448,
      "name": "dwc2_core_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
int dwc2_core_reset(struct dwc2_hsotg * hsotg, bool skip_wait)
```

```json
{
  "name": "dwc2_core_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_core_reset",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:495",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587254734,
      "name": "dwc2_core_reset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071587252848,
      "name": "dwc2_core_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
int dwc2_core_reset(struct dwc2_hsotg * hsotg, bool skip_wait)
```

```json
{
  "name": "dwc2_core_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588105728,
      "name": "dwc2_core_reset",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:495",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_hs_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_fs_phy_init",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588105728,
      "name": "dwc2_core_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
int dwc2_core_reset(struct dwc2_hsotg * hsotg, bool skip_wait)
```

```json
{
  "name": "dwc2_core_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588147488,
      "name": "dwc2_core_reset",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:495",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_hs_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_fs_phy_init",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588147488,
      "name": "dwc2_core_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
int dwc2_core_reset(struct dwc2_hsotg * hsotg, bool skip_wait)
```

```json
{
  "name": "dwc2_core_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588028960,
      "name": "dwc2_core_reset",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:423",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_hs_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_fs_phy_init",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588028960,
      "name": "dwc2_core_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 518
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
int dwc2_core_reset(struct dwc2_hsotg * hsotg, bool skip_wait)
```

```json
{
  "name": "dwc2_core_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_core_reset",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:423",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_hs_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_fs_phy_init",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592575834,
      "name": "dwc2_core_reset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
    },
    {
      "addr": 18446744071588646736,
      "name": "dwc2_core_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 732
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
int dwc2_core_reset(struct dwc2_hsotg * hsotg, bool skip_wait)
```

```json
{
  "name": "dwc2_core_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_core_reset",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:423",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_hs_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_fs_phy_init",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594455728,
      "name": "dwc2_core_reset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
    },
    {
      "addr": 18446744071590063536,
      "name": "dwc2_core_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 662
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
int dwc2_core_reset(struct dwc2_hsotg * hsotg, bool skip_wait)
```

```json
{
  "name": "dwc2_core_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_core_reset",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:393",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_hs_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_fs_phy_init",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596274801,
      "name": "dwc2_core_reset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
    },
    {
      "addr": 18446744071591671024,
      "name": "dwc2_core_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 665
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
int dwc2_core_reset(struct dwc2_hsotg * hsotg, bool skip_wait)
```

```json
{
  "name": "dwc2_core_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_core_reset",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:393",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_hs_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_fs_phy_init",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596804641,
      "name": "dwc2_core_reset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
    },
    {
      "addr": 18446744071592093856,
      "name": "dwc2_core_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 665
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
int dwc2_core_reset(struct dwc2_hsotg * hsotg, bool skip_wait)
```

```json
{
  "name": "dwc2_core_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_core_reset",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:393",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_hs_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_fs_phy_init",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597728248,
      "name": "dwc2_core_reset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
    },
    {
      "addr": 18446744071592834288,
      "name": "dwc2_core_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 665
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
int dwc2_core_reset(struct dwc2_hsotg * hsotg, bool skip_wait)
```

```json
{
  "name": "dwc2_core_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500362136,
      "name": "dwc2_core_reset",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:495",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500362136,
      "name": "dwc2_core_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
int dwc2_core_reset(struct dwc2_hsotg * hsotg, bool skip_wait)
```

```json
{
  "name": "dwc2_core_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232818192,
      "name": "dwc2_core_reset",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:495",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232818192,
      "name": "dwc2_core_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int dwc2_core_reset(struct dwc2_hsotg * hsotg, bool skip_wait)
```

```json
{
  "name": "dwc2_core_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293673792,
      "name": "dwc2_core_reset",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:495",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293673792,
      "name": "dwc2_core_reset",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int dwc2_core_reset(struct dwc2_hsotg * hsotg, bool skip_wait)
```

```json
{
  "name": "dwc2_core_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277246576,
      "name": "dwc2_core_reset",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:495",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277246576,
      "name": "dwc2_core_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
int dwc2_core_reset(struct dwc2_hsotg * hsotg, bool skip_wait)
```

```json
{
  "name": "dwc2_core_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_core_reset",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:495",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586960814,
      "name": "dwc2_core_reset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071586958928,
      "name": "dwc2_core_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
int dwc2_core_reset(struct dwc2_hsotg * hsotg, bool skip_wait)
```

```json
{
  "name": "dwc2_core_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_core_reset",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:495",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587209294,
      "name": "dwc2_core_reset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071587207408,
      "name": "dwc2_core_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
int dwc2_core_reset(struct dwc2_hsotg * hsotg, bool skip_wait)
```

```json
{
  "name": "dwc2_core_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_core_reset",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:495",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587316366,
      "name": "dwc2_core_reset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071587314480,
      "name": "dwc2_core_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool skip_wait</code>
</li>
</ul>
</details>
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
int dwc2_core_reset(struct dwc2_hsotg * hsotg, bool skip_wait)
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
