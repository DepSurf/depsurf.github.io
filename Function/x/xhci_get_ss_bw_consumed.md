# Function: <code>xhci_get_ss_bw_consumed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_get_ss_bw_consumed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585444891,
      "name": "xhci_get_ss_bw_consumed",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2372",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table",
        "drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_get_ss_bw_consumed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585854599,
      "name": "xhci_get_ss_bw_consumed",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2350",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table",
        "drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table"
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
  "name": "xhci_get_ss_bw_consumed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586043431,
      "name": "xhci_get_ss_bw_consumed",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2339",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table",
        "drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table"
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
  "name": "xhci_get_ss_bw_consumed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586112111,
      "name": "xhci_get_ss_bw_consumed",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2283",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "xhci_get_ss_bw_consumed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586556575,
      "name": "xhci_get_ss_bw_consumed",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2294",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info * ep_bw)
```

```json
{
  "name": "xhci_get_ss_bw_consumed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586817072,
      "name": "xhci_get_ss_bw_consumed",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2420",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586817072,
      "name": "xhci_get_ss_bw_consumed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info * ep_bw)
```

```json
{
  "name": "xhci_get_ss_bw_consumed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586973632,
      "name": "xhci_get_ss_bw_consumed",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2437",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586973632,
      "name": "xhci_get_ss_bw_consumed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info * ep_bw)
```

```json
{
  "name": "xhci_get_ss_bw_consumed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587234336,
      "name": "xhci_get_ss_bw_consumed",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2466",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587234336,
      "name": "xhci_get_ss_bw_consumed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info * ep_bw)
```

```json
{
  "name": "xhci_get_ss_bw_consumed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587434416,
      "name": "xhci_get_ss_bw_consumed",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2475",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587434416,
      "name": "xhci_get_ss_bw_consumed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_get_ss_bw_consumed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588300768,
      "name": "xhci_get_ss_bw_consumed",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2478",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table",
        "drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588300768,
      "name": "xhci_get_ss_bw_consumed.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_get_ss_bw_consumed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588335728,
      "name": "xhci_get_ss_bw_consumed",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2611",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table",
        "drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table",
        "drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table",
        "drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588335728,
      "name": "xhci_get_ss_bw_consumed.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
  "name": "xhci_get_ss_bw_consumed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588218368,
      "name": "xhci_get_ss_bw_consumed",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2606",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table",
        "drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588218368,
      "name": "xhci_get_ss_bw_consumed.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info * ep_bw)
```

```json
{
  "name": "xhci_get_ss_bw_consumed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_get_ss_bw_consumed",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2618",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table",
        "drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table",
        "drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table",
        "drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588854352,
      "name": "xhci_get_ss_bw_consumed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071592605346,
      "name": "xhci_get_ss_bw_consumed.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info * ep_bw)
```

```json
{
  "name": "xhci_get_ss_bw_consumed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_get_ss_bw_consumed",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2656",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table",
        "drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table",
        "drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table",
        "drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590280160,
      "name": "xhci_get_ss_bw_consumed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071594488186,
      "name": "xhci_get_ss_bw_consumed.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info * ep_bw)
```

```json
{
  "name": "xhci_get_ss_bw_consumed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_get_ss_bw_consumed",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2654",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table",
        "drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table",
        "drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table",
        "drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591902048,
      "name": "xhci_get_ss_bw_consumed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071596299791,
      "name": "xhci_get_ss_bw_consumed.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info * ep_bw)
```

```json
{
  "name": "xhci_get_ss_bw_consumed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_get_ss_bw_consumed",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2494",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table",
        "drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table",
        "drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table",
        "drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592325360,
      "name": "xhci_get_ss_bw_consumed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071596829461,
      "name": "xhci_get_ss_bw_consumed.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info * ep_bw)
```

```json
{
  "name": "xhci_get_ss_bw_consumed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_get_ss_bw_consumed",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2530",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table",
        "drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table",
        "drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table",
        "drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593066784,
      "name": "xhci_get_ss_bw_consumed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071597753112,
      "name": "xhci_get_ss_bw_consumed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info * ep_bw)
```

```json
{
  "name": "xhci_get_ss_bw_consumed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500565072,
      "name": "xhci_get_ss_bw_consumed",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2475",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500565072,
      "name": "xhci_get_ss_bw_consumed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info * ep_bw)
```

```json
{
  "name": "xhci_get_ss_bw_consumed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233027960,
      "name": "xhci_get_ss_bw_consumed",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2475",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table",
        "drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233027960,
      "name": "xhci_get_ss_bw_consumed",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info * ep_bw)
```

```json
{
  "name": "xhci_get_ss_bw_consumed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293963760,
      "name": "xhci_get_ss_bw_consumed",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2475",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table",
        "drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table",
        "drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table",
        "drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293963760,
      "name": "xhci_get_ss_bw_consumed",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info * ep_bw)
```

```json
{
  "name": "xhci_get_ss_bw_consumed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277439818,
      "name": "xhci_get_ss_bw_consumed",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2475",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table",
        "drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table",
        "drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table",
        "drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277439818,
      "name": "xhci_get_ss_bw_consumed",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info * ep_bw)
```

```json
{
  "name": "xhci_get_ss_bw_consumed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587140496,
      "name": "xhci_get_ss_bw_consumed",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2475",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587140496,
      "name": "xhci_get_ss_bw_consumed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info * ep_bw)
```

```json
{
  "name": "xhci_get_ss_bw_consumed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586899104,
      "name": "xhci_get_ss_bw_consumed",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2475",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586899104,
      "name": "xhci_get_ss_bw_consumed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info * ep_bw)
```

```json
{
  "name": "xhci_get_ss_bw_consumed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587388976,
      "name": "xhci_get_ss_bw_consumed",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2475",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587388976,
      "name": "xhci_get_ss_bw_consumed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info * ep_bw)
```

```json
{
  "name": "xhci_get_ss_bw_consumed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587495184,
      "name": "xhci_get_ss_bw_consumed",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2475",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587495184,
      "name": "xhci_get_ss_bw_consumed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info * ep_bw)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info * ep_bw)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info * ep_bw)
```
</details>
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
