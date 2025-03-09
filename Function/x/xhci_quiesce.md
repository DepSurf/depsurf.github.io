# Function: <code>xhci_quiesce</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xhci_quiesce(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_quiesce",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585451440,
      "name": "xhci_quiesce",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:83",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585451440,
      "name": "xhci_quiesce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void xhci_quiesce(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_quiesce",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585847008,
      "name": "xhci_quiesce",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:84",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585847008,
      "name": "xhci_quiesce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void xhci_quiesce(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_quiesce",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586036244,
      "name": "xhci_quiesce",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:84",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_halt"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586036160,
      "name": "xhci_quiesce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void xhci_quiesce(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_quiesce",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586119876,
      "name": "xhci_quiesce",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:84",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_halt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586119792,
      "name": "xhci_quiesce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void xhci_quiesce(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_quiesce",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586562692,
      "name": "xhci_quiesce",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:74",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_halt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586562608,
      "name": "xhci_quiesce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void xhci_quiesce(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_quiesce",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586827352,
      "name": "xhci_quiesce",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:89",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_halt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586827264,
      "name": "xhci_quiesce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void xhci_quiesce(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_quiesce",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586983992,
      "name": "xhci_quiesce",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:89",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_halt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586983904,
      "name": "xhci_quiesce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xhci_quiesce(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_quiesce",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587245364,
      "name": "xhci_quiesce",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:87",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_halt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587245280,
      "name": "xhci_quiesce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xhci_quiesce(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_quiesce",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587445812,
      "name": "xhci_quiesce",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:87",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_halt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587445728,
      "name": "xhci_quiesce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xhci_quiesce(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_quiesce",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588309764,
      "name": "xhci_quiesce",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:87",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_halt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588309680,
      "name": "xhci_quiesce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xhci_quiesce(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_quiesce",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588344484,
      "name": "xhci_quiesce",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:87",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_halt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588344400,
      "name": "xhci_quiesce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void xhci_quiesce(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_quiesce",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588227188,
      "name": "xhci_quiesce",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:86",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_halt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588227104,
      "name": "xhci_quiesce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xhci_quiesce(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_quiesce",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588870884,
      "name": "xhci_quiesce",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:86",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_halt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588870800,
      "name": "xhci_quiesce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xhci_quiesce(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_quiesce",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590297668,
      "name": "xhci_quiesce",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:86",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_halt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590297568,
      "name": "xhci_quiesce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xhci_quiesce(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_quiesce",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591921636,
      "name": "xhci_quiesce",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:86",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_halt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591921520,
      "name": "xhci_quiesce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xhci_quiesce(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_quiesce",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592343652,
      "name": "xhci_quiesce",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:87",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_halt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592343536,
      "name": "xhci_quiesce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xhci_quiesce(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_quiesce",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593085220,
      "name": "xhci_quiesce",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:110",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_halt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593085104,
      "name": "xhci_quiesce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void xhci_quiesce(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_quiesce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500580296,
      "name": "xhci_quiesce",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:87",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_halt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500580296,
      "name": "xhci_quiesce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void xhci_quiesce(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_quiesce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233041916,
      "name": "xhci_quiesce",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:87",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_halt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233041916,
      "name": "xhci_quiesce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void xhci_quiesce(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_quiesce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293983728,
      "name": "xhci_quiesce",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:87",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_halt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293983728,
      "name": "xhci_quiesce",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void xhci_quiesce(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_quiesce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277452360,
      "name": "xhci_quiesce",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:87",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_halt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277452360,
      "name": "xhci_quiesce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void xhci_quiesce(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_quiesce",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587151876,
      "name": "xhci_quiesce",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:87",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_halt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587151792,
      "name": "xhci_quiesce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void xhci_quiesce(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_quiesce",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586910484,
      "name": "xhci_quiesce",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:87",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_halt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586910400,
      "name": "xhci_quiesce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void xhci_quiesce(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_quiesce",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587400372,
      "name": "xhci_quiesce",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:87",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_halt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587400288,
      "name": "xhci_quiesce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void xhci_quiesce(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_quiesce",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587506804,
      "name": "xhci_quiesce",
      "external": true,
      "loc": "drivers/usb/host/xhci.c:87",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_halt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587506720,
      "name": "xhci_quiesce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
