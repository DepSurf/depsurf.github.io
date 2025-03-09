# Function: <code>xhci_create_intel_xhci_sw_pdev</code>

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
  "name": "xhci_create_intel_xhci_sw_pdev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586868475,
      "name": "xhci_create_intel_xhci_sw_pdev",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.c:19",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
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
  "name": "xhci_create_intel_xhci_sw_pdev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587023786,
      "name": "xhci_create_intel_xhci_sw_pdev",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.c:19",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
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
  "name": "xhci_create_intel_xhci_sw_pdev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587285504,
      "name": "xhci_create_intel_xhci_sw_pdev",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.c:19",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
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
  "name": "xhci_create_intel_xhci_sw_pdev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587486208,
      "name": "xhci_create_intel_xhci_sw_pdev",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.c:28",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int xhci_create_intel_xhci_sw_pdev(struct xhci_hcd * xhci, u32 cap_offset)
```

```json
{
  "name": "xhci_create_intel_xhci_sw_pdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_create_intel_xhci_sw_pdev",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.c:28",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588348368,
      "name": "xhci_create_intel_xhci_sw_pdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
    },
    {
      "addr": 18446744071588348827,
      "name": "xhci_create_intel_xhci_sw_pdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
int xhci_create_intel_xhci_sw_pdev(struct xhci_hcd * xhci, u32 cap_offset)
```

```json
{
  "name": "xhci_create_intel_xhci_sw_pdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_create_intel_xhci_sw_pdev",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.c:28",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588379392,
      "name": "xhci_create_intel_xhci_sw_pdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    },
    {
      "addr": 18446744071591565402,
      "name": "xhci_create_intel_xhci_sw_pdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
int xhci_create_intel_xhci_sw_pdev(struct xhci_hcd * xhci, u32 cap_offset)
```

```json
{
  "name": "xhci_create_intel_xhci_sw_pdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_create_intel_xhci_sw_pdev",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.c:28",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588261776,
      "name": "xhci_create_intel_xhci_sw_pdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071591508229,
      "name": "xhci_create_intel_xhci_sw_pdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
int xhci_create_intel_xhci_sw_pdev(struct xhci_hcd * xhci, u32 cap_offset)
```

```json
{
  "name": "xhci_create_intel_xhci_sw_pdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_create_intel_xhci_sw_pdev",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.c:28",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588912640,
      "name": "xhci_create_intel_xhci_sw_pdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071592609663,
      "name": "xhci_create_intel_xhci_sw_pdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
int xhci_create_intel_xhci_sw_pdev(struct xhci_hcd * xhci, u32 cap_offset)
```

```json
{
  "name": "xhci_create_intel_xhci_sw_pdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_create_intel_xhci_sw_pdev",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.c:28",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590342144,
      "name": "xhci_create_intel_xhci_sw_pdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
    },
    {
      "addr": 18446744071594492722,
      "name": "xhci_create_intel_xhci_sw_pdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
int xhci_create_intel_xhci_sw_pdev(struct xhci_hcd * xhci, u32 cap_offset)
```

```json
{
  "name": "xhci_create_intel_xhci_sw_pdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591970800,
      "name": "xhci_create_intel_xhci_sw_pdev",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.c:28",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591970800,
      "name": "xhci_create_intel_xhci_sw_pdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
int xhci_create_intel_xhci_sw_pdev(struct xhci_hcd * xhci, u32 cap_offset)
```

```json
{
  "name": "xhci_create_intel_xhci_sw_pdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592391856,
      "name": "xhci_create_intel_xhci_sw_pdev",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.c:28",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592391856,
      "name": "xhci_create_intel_xhci_sw_pdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 443
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
int xhci_create_intel_xhci_sw_pdev(struct xhci_hcd * xhci, u32 cap_offset)
```

```json
{
  "name": "xhci_create_intel_xhci_sw_pdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593134800,
      "name": "xhci_create_intel_xhci_sw_pdev",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.c:28",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593134800,
      "name": "xhci_create_intel_xhci_sw_pdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 443
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_create_intel_xhci_sw_pdev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500624116,
      "name": "xhci_create_intel_xhci_sw_pdev",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.c:28",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "xhci_create_intel_xhci_sw_pdev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233083360,
      "name": "xhci_create_intel_xhci_sw_pdev",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.c:28",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "xhci_create_intel_xhci_sw_pdev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294040096,
      "name": "xhci_create_intel_xhci_sw_pdev",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.c:28",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_create_intel_xhci_sw_pdev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277490706,
      "name": "xhci_create_intel_xhci_sw_pdev",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.c:28",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_create_intel_xhci_sw_pdev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587192240,
      "name": "xhci_create_intel_xhci_sw_pdev",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.c:28",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_create_intel_xhci_sw_pdev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586950992,
      "name": "xhci_create_intel_xhci_sw_pdev",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.c:28",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_create_intel_xhci_sw_pdev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587440768,
      "name": "xhci_create_intel_xhci_sw_pdev",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.c:28",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
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
  "name": "xhci_create_intel_xhci_sw_pdev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587547744,
      "name": "xhci_create_intel_xhci_sw_pdev",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.c:28",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int xhci_create_intel_xhci_sw_pdev(struct xhci_hcd * xhci, u32 cap_offset)
```
</details>
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
