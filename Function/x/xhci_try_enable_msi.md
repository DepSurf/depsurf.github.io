# Function: <code>xhci_try_enable_msi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_try_enable_msi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585451782,
      "name": "xhci_try_enable_msi",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:367",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_run"
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
  "name": "xhci_try_enable_msi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585847350,
      "name": "xhci_try_enable_msi",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:369",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_run"
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
  "name": "xhci_try_enable_msi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586036502,
      "name": "xhci_try_enable_msi",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:373",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_run"
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
  "name": "xhci_try_enable_msi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586120305,
      "name": "xhci_try_enable_msi",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:337",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_run"
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
  "name": "xhci_try_enable_msi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586563121,
      "name": "xhci_try_enable_msi",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:327",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_run"
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
  "name": "xhci_try_enable_msi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586827796,
      "name": "xhci_try_enable_msi",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:404",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_run"
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
  "name": "xhci_try_enable_msi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586984436,
      "name": "xhci_try_enable_msi",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:405",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_run"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int xhci_try_enable_msi(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_try_enable_msi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_try_enable_msi",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:403",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587243056,
      "name": "xhci_try_enable_msi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 779
    },
    {
      "addr": 18446744071587265404,
      "name": "xhci_try_enable_msi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
int xhci_try_enable_msi(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_try_enable_msi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_try_enable_msi",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:403",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587435168,
      "name": "xhci_try_enable_msi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 771
    },
    {
      "addr": 18446744071587465308,
      "name": "xhci_try_enable_msi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
int xhci_try_enable_msi(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_try_enable_msi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_try_enable_msi",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:403",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588296544,
      "name": "xhci_try_enable_msi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
    },
    {
      "addr": 18446744071588327372,
      "name": "xhci_try_enable_msi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
int xhci_try_enable_msi(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_try_enable_msi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_try_enable_msi",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:403",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588330704,
      "name": "xhci_try_enable_msi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
    },
    {
      "addr": 18446744071591561721,
      "name": "xhci_try_enable_msi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
int xhci_try_enable_msi(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_try_enable_msi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_try_enable_msi",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:406",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588213376,
      "name": "xhci_try_enable_msi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 780
    },
    {
      "addr": 18446744071591504509,
      "name": "xhci_try_enable_msi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
int xhci_try_enable_msi(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_try_enable_msi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_try_enable_msi",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:406",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588855360,
      "name": "xhci_try_enable_msi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 780
    },
    {
      "addr": 18446744071592605436,
      "name": "xhci_try_enable_msi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
int xhci_try_enable_msi(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_try_enable_msi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_try_enable_msi",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:407",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590281264,
      "name": "xhci_try_enable_msi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 803
    },
    {
      "addr": 18446744071594488276,
      "name": "xhci_try_enable_msi.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int xhci_try_enable_msi(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_try_enable_msi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591903216,
      "name": "xhci_try_enable_msi",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:409",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591903216,
      "name": "xhci_try_enable_msi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 889
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int xhci_try_enable_msi(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_try_enable_msi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500565968,
      "name": "xhci_try_enable_msi",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:403",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500565968,
      "name": "xhci_try_enable_msi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 820
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
int xhci_try_enable_msi(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_try_enable_msi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233029692,
      "name": "xhci_try_enable_msi",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:403",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233029692,
      "name": "xhci_try_enable_msi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 828
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
int xhci_try_enable_msi(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_try_enable_msi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293966400,
      "name": "xhci_try_enable_msi",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:403",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293966400,
      "name": "xhci_try_enable_msi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1088
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
int xhci_try_enable_msi(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_try_enable_msi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277441620,
      "name": "xhci_try_enable_msi",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:403",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277441620,
      "name": "xhci_try_enable_msi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 720
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
int xhci_try_enable_msi(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_try_enable_msi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_try_enable_msi",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:403",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587141248,
      "name": "xhci_try_enable_msi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 771
    },
    {
      "addr": 18446744071587171340,
      "name": "xhci_try_enable_msi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int xhci_try_enable_msi(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_try_enable_msi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_try_enable_msi",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:403",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586899856,
      "name": "xhci_try_enable_msi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 771
    },
    {
      "addr": 18446744071586930082,
      "name": "xhci_try_enable_msi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int xhci_try_enable_msi(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_try_enable_msi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_try_enable_msi",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:403",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587389728,
      "name": "xhci_try_enable_msi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 771
    },
    {
      "addr": 18446744071587419868,
      "name": "xhci_try_enable_msi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
int xhci_try_enable_msi(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_try_enable_msi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_try_enable_msi",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:403",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587495936,
      "name": "xhci_try_enable_msi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 771
    },
    {
      "addr": 18446744071587526597,
      "name": "xhci_try_enable_msi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
int xhci_try_enable_msi(struct usb_hcd * hcd)
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int xhci_try_enable_msi(struct usb_hcd * hcd)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
