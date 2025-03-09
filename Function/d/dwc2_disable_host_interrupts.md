# Function: <code>dwc2_disable_host_interrupts</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void dwc2_disable_host_interrupts(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_disable_host_interrupts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585278256,
      "name": "dwc2_disable_host_interrupts",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:875",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585278256,
      "name": "dwc2_disable_host_interrupts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
  "name": "dwc2_disable_host_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585704459,
      "name": "dwc2_disable_host_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:374",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect"
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
  "name": "dwc2_disable_host_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585893166,
      "name": "dwc2_disable_host_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:375",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect"
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
  "name": "dwc2_disable_host_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585975918,
      "name": "dwc2_disable_host_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:391",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect"
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
  "name": "dwc2_disable_host_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586419809,
      "name": "dwc2_disable_host_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:397",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_disable_host_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586682141,
      "name": "dwc2_disable_host_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:410",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect"
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
  "name": "dwc2_disable_host_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586834709,
      "name": "dwc2_disable_host_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:404",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_disable_host_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587091733,
      "name": "dwc2_disable_host_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:214",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_disable_host_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587292229,
      "name": "dwc2_disable_host_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:214",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_disable_host_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588149892,
      "name": "dwc2_disable_host_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:214",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_disable_host_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588190436,
      "name": "dwc2_disable_host_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:214",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_disable_host_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588066228,
      "name": "dwc2_disable_host_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:212",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dwc2_disable_host_interrupts(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_disable_host_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588693673,
      "name": "dwc2_disable_host_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:212",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_stop"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588671728,
      "name": "dwc2_disable_host_interrupts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071592585389,
      "name": "dwc2_disable_host_interrupts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dwc2_disable_host_interrupts(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_disable_host_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590112181,
      "name": "dwc2_disable_host_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:208",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_stop"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590090096,
      "name": "dwc2_disable_host_interrupts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071594465770,
      "name": "dwc2_disable_host_interrupts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dwc2_disable_host_interrupts(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_disable_host_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591724069,
      "name": "dwc2_disable_host_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:179",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_stop"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591700736,
      "name": "dwc2_disable_host_interrupts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071596282696,
      "name": "dwc2_disable_host_interrupts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dwc2_disable_host_interrupts(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_disable_host_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592147445,
      "name": "dwc2_disable_host_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:179",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_stop"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592124112,
      "name": "dwc2_disable_host_interrupts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071596812571,
      "name": "dwc2_disable_host_interrupts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dwc2_disable_host_interrupts(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_disable_host_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592888069,
      "name": "dwc2_disable_host_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:179",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_stop"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592864640,
      "name": "dwc2_disable_host_interrupts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071597736178,
      "name": "dwc2_disable_host_interrupts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void dwc2_disable_host_interrupts(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_disable_host_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500382288,
      "name": "dwc2_disable_host_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:214",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500382288,
      "name": "dwc2_disable_host_interrupts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void dwc2_disable_host_interrupts(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_disable_host_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232838536,
      "name": "dwc2_disable_host_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:214",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232838536,
      "name": "dwc2_disable_host_interrupts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void dwc2_disable_host_interrupts(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_disable_host_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293703568,
      "name": "dwc2_disable_host_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:214",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293703568,
      "name": "dwc2_disable_host_interrupts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
void dwc2_disable_host_interrupts(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_disable_host_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277268440,
      "name": "dwc2_disable_host_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:214",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277268440,
      "name": "dwc2_disable_host_interrupts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_disable_host_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586998309,
      "name": "dwc2_disable_host_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:214",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect"
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_disable_host_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587246789,
      "name": "dwc2_disable_host_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:214",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_disable_host_interrupts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587353557,
      "name": "dwc2_disable_host_interrupts",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:214",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void dwc2_disable_host_interrupts(struct dwc2_hsotg * hsotg)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void dwc2_disable_host_interrupts(struct dwc2_hsotg * hsotg)
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void dwc2_disable_host_interrupts(struct dwc2_hsotg * hsotg)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void dwc2_disable_host_interrupts(struct dwc2_hsotg * hsotg)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void dwc2_disable_host_interrupts(struct dwc2_hsotg * hsotg)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void dwc2_disable_host_interrupts(struct dwc2_hsotg * hsotg)
```
</details>
</li>
</ul>
