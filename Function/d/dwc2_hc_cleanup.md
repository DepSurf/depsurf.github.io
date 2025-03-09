# Function: <code>dwc2_hc_cleanup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void dwc2_hc_cleanup(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan)
```

```json
{
  "name": "dwc2_hc_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585279408,
      "name": "dwc2_hc_cleanup",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:1556",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585279408,
      "name": "dwc2_hc_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void dwc2_hc_cleanup(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan)
```

```json
{
  "name": "dwc2_hc_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585681825,
      "name": "dwc2_hc_cleanup",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:1074",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585693104,
      "name": "dwc2_hc_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void dwc2_hc_cleanup(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan)
```

```json
{
  "name": "dwc2_hc_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585870796,
      "name": "dwc2_hc_cleanup",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:1104",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585882080,
      "name": "dwc2_hc_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void dwc2_hc_cleanup(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan)
```

```json
{
  "name": "dwc2_hc_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585953448,
      "name": "dwc2_hc_cleanup",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:1121",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585964800,
      "name": "dwc2_hc_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void dwc2_hc_cleanup(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan)
```

```json
{
  "name": "dwc2_hc_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586396955,
      "name": "dwc2_hc_cleanup",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:1127",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586408512,
      "name": "dwc2_hc_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void dwc2_hc_cleanup(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan)
```

```json
{
  "name": "dwc2_hc_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586660145,
      "name": "dwc2_hc_cleanup",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:1162",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586669200,
      "name": "dwc2_hc_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void dwc2_hc_cleanup(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan)
```

```json
{
  "name": "dwc2_hc_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586822576,
      "name": "dwc2_hc_cleanup",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:1155",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586822576,
      "name": "dwc2_hc_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void dwc2_hc_cleanup(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan)
```

```json
{
  "name": "dwc2_hc_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587080864,
      "name": "dwc2_hc_cleanup",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:965",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587080864,
      "name": "dwc2_hc_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void dwc2_hc_cleanup(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan)
```

```json
{
  "name": "dwc2_hc_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587281344,
      "name": "dwc2_hc_cleanup",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:965",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587281344,
      "name": "dwc2_hc_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void dwc2_hc_cleanup(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan)
```

```json
{
  "name": "dwc2_hc_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588136768,
      "name": "dwc2_hc_cleanup",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:965",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_cleanup_channels",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588136768,
      "name": "dwc2_hc_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void dwc2_hc_cleanup(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan)
```

```json
{
  "name": "dwc2_hc_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588177360,
      "name": "dwc2_hc_cleanup",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:965",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_cleanup_channels",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588177360,
      "name": "dwc2_hc_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dwc2_hc_cleanup(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan)
```

```json
{
  "name": "dwc2_hc_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588053027,
      "name": "dwc2_hc_cleanup",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:963",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_reinit"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588055488,
      "name": "dwc2_hc_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void dwc2_hc_cleanup(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan)
```

```json
{
  "name": "dwc2_hc_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hc_cleanup",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:963",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_reinit",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592587905,
      "name": "dwc2_hc_cleanup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071588679904,
      "name": "dwc2_hc_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void dwc2_hc_cleanup(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan)
```

```json
{
  "name": "dwc2_hc_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hc_cleanup",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:959",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_reinit",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594468625,
      "name": "dwc2_hc_cleanup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071590098144,
      "name": "dwc2_hc_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void dwc2_hc_cleanup(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan)
```

```json
{
  "name": "dwc2_hc_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hc_cleanup",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:930",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_reinit",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596285347,
      "name": "dwc2_hc_cleanup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071591709184,
      "name": "dwc2_hc_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void dwc2_hc_cleanup(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan)
```

```json
{
  "name": "dwc2_hc_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hc_cleanup",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:930",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_reinit",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596815222,
      "name": "dwc2_hc_cleanup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071592132592,
      "name": "dwc2_hc_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void dwc2_hc_cleanup(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan)
```

```json
{
  "name": "dwc2_hc_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_hc_cleanup",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:930",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_reinit",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597738829,
      "name": "dwc2_hc_cleanup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071592873120,
      "name": "dwc2_hc_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void dwc2_hc_cleanup(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan)
```

```json
{
  "name": "dwc2_hc_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500395560,
      "name": "dwc2_hc_cleanup",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:965",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500395560,
      "name": "dwc2_hc_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void dwc2_hc_cleanup(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan)
```

```json
{
  "name": "dwc2_hc_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232851720,
      "name": "dwc2_hc_cleanup",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:965",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232851720,
      "name": "dwc2_hc_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
void dwc2_hc_cleanup(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan)
```

```json
{
  "name": "dwc2_hc_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293725248,
      "name": "dwc2_hc_cleanup",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:965",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293725248,
      "name": "dwc2_hc_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void dwc2_hc_cleanup(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan)
```

```json
{
  "name": "dwc2_hc_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277284170,
      "name": "dwc2_hc_cleanup",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:965",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277284170,
      "name": "dwc2_hc_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void dwc2_hc_cleanup(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan)
```

```json
{
  "name": "dwc2_hc_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586987424,
      "name": "dwc2_hc_cleanup",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:965",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586987424,
      "name": "dwc2_hc_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void dwc2_hc_cleanup(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan)
```

```json
{
  "name": "dwc2_hc_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587235904,
      "name": "dwc2_hc_cleanup",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:965",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587235904,
      "name": "dwc2_hc_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void dwc2_hc_cleanup(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan)
```

```json
{
  "name": "dwc2_hc_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587342672,
      "name": "dwc2_hc_cleanup",
      "external": true,
      "loc": "drivers/usb/dwc2/hcd.c:965",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587342672,
      "name": "dwc2_hc_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void dwc2_hc_cleanup(struct dwc2_hsotg * hsotg, struct dwc2_host_chan * chan)
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
