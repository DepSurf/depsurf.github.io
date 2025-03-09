# Function: <code>usb_disconnect</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void usb_disconnect(struct usb_device * * pdev)
```

```json
{
  "name": "usb_disconnect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585168912,
      "name": "usb_disconnect",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2156",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585168912,
      "name": "usb_disconnect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 638
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
void usb_disconnect(struct usb_device * * pdev)
```

```json
{
  "name": "usb_disconnect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585561328,
      "name": "usb_disconnect",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2153",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585561328,
      "name": "usb_disconnect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
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
void usb_disconnect(struct usb_device * * pdev)
```

```json
{
  "name": "usb_disconnect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585749008,
      "name": "usb_disconnect",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2072",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585749008,
      "name": "usb_disconnect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
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
void usb_disconnect(struct usb_device * * pdev)
```

```json
{
  "name": "usb_disconnect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585836128,
      "name": "usb_disconnect",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2094",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585836128,
      "name": "usb_disconnect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 607
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
void usb_disconnect(struct usb_device * * pdev)
```

```json
{
  "name": "usb_disconnect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586275488,
      "name": "usb_disconnect",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2094",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586275488,
      "name": "usb_disconnect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 610
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
void usb_disconnect(struct usb_device * * pdev)
```

```json
{
  "name": "usb_disconnect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586533056,
      "name": "usb_disconnect",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2118",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586533056,
      "name": "usb_disconnect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
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
void usb_disconnect(struct usb_device * * pdev)
```

```json
{
  "name": "usb_disconnect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586681856,
      "name": "usb_disconnect",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2129",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586681856,
      "name": "usb_disconnect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 599
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
void usb_disconnect(struct usb_device * * pdev)
```

```json
{
  "name": "usb_disconnect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586935408,
      "name": "usb_disconnect",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2169",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586935408,
      "name": "usb_disconnect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 613
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
void usb_disconnect(struct usb_device * * pdev)
```

```json
{
  "name": "usb_disconnect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587134000,
      "name": "usb_disconnect",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2180",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587134000,
      "name": "usb_disconnect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 613
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
void usb_disconnect(struct usb_device * * pdev)
```

```json
{
  "name": "usb_disconnect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_disconnect",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2187",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587996612,
      "name": "usb_disconnect.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
    },
    {
      "addr": 18446744071587983600,
      "name": "usb_disconnect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void usb_disconnect(struct usb_device * * pdev)
```

```json
{
  "name": "usb_disconnect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_disconnect",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2188",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591538410,
      "name": "usb_disconnect.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
    },
    {
      "addr": 18446744071588043264,
      "name": "usb_disconnect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void usb_disconnect(struct usb_device * * pdev)
```

```json
{
  "name": "usb_disconnect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_disconnect",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2195",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591480664,
      "name": "usb_disconnect.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
    },
    {
      "addr": 18446744071587925216,
      "name": "usb_disconnect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void usb_disconnect(struct usb_device * * pdev)
```

```json
{
  "name": "usb_disconnect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_disconnect",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2198",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592557832,
      "name": "usb_disconnect.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
    },
    {
      "addr": 18446744071588535280,
      "name": "usb_disconnect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void usb_disconnect(struct usb_device * * pdev)
```

```json
{
  "name": "usb_disconnect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589943696,
      "name": "usb_disconnect",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2198",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589943696,
      "name": "usb_disconnect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 728
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void usb_disconnect(struct usb_device * * pdev)
```

```json
{
  "name": "usb_disconnect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591526480,
      "name": "usb_disconnect",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2208",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/port.c:disable_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591526480,
      "name": "usb_disconnect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 728
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void usb_disconnect(struct usb_device * * pdev)
```

```json
{
  "name": "usb_disconnect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591948384,
      "name": "usb_disconnect",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2223",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/port.c:disable_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591948384,
      "name": "usb_disconnect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 715
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void usb_disconnect(struct usb_device * * pdev)
```

```json
{
  "name": "usb_disconnect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592688176,
      "name": "usb_disconnect",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2237",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/port.c:disable_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592688176,
      "name": "usb_disconnect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 747
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
void usb_disconnect(struct usb_device * * pdev)
```

```json
{
  "name": "usb_disconnect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500210520,
      "name": "usb_disconnect",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2180",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500210520,
      "name": "usb_disconnect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 812
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
void usb_disconnect(struct usb_device * * pdev)
```

```json
{
  "name": "usb_disconnect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232689544,
      "name": "usb_disconnect",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2180",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232689544,
      "name": "usb_disconnect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 628
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
void usb_disconnect(struct usb_device * * pdev)
```

```json
{
  "name": "usb_disconnect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293498848,
      "name": "usb_disconnect",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2180",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293498848,
      "name": "usb_disconnect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1020
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
void usb_disconnect(struct usb_device * * pdev)
```

```json
{
  "name": "usb_disconnect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277134196,
      "name": "usb_disconnect",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2180",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277134196,
      "name": "usb_disconnect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 660
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
void usb_disconnect(struct usb_device * * pdev)
```

```json
{
  "name": "usb_disconnect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586840080,
      "name": "usb_disconnect",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2180",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586840080,
      "name": "usb_disconnect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 613
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void usb_disconnect(struct usb_device * * pdev)
```

```json
{
  "name": "usb_disconnect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586781840,
      "name": "usb_disconnect",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2180",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586781840,
      "name": "usb_disconnect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 607
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void usb_disconnect(struct usb_device * * pdev)
```

```json
{
  "name": "usb_disconnect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587088560,
      "name": "usb_disconnect",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2180",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587088560,
      "name": "usb_disconnect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 613
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
void usb_disconnect(struct usb_device * * pdev)
```

```json
{
  "name": "usb_disconnect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587195712,
      "name": "usb_disconnect",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2180",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587195712,
      "name": "usb_disconnect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 688
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
