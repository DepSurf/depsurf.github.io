# Function: <code>xhci_ext_cap_init</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int xhci_ext_cap_init(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_ext_cap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586868240,
      "name": "xhci_ext_cap_init",
      "external": true,
      "loc": "drivers/usb/host/xhci-ext-caps.c:64",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586868240,
      "name": "xhci_ext_cap_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 517
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
int xhci_ext_cap_init(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_ext_cap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587023552,
      "name": "xhci_ext_cap_init",
      "external": true,
      "loc": "drivers/usb/host/xhci-ext-caps.c:64",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587023552,
      "name": "xhci_ext_cap_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
int xhci_ext_cap_init(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_ext_cap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_ext_cap_init",
      "external": true,
      "loc": "drivers/usb/host/xhci-ext-caps.c:64",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587285671,
      "name": "xhci_ext_cap_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071587285264,
      "name": "xhci_ext_cap_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 407
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
int xhci_ext_cap_init(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_ext_cap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_ext_cap_init",
      "external": true,
      "loc": "drivers/usb/host/xhci-ext-caps.c:83",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587486408,
      "name": "xhci_ext_cap_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071587485968,
      "name": "xhci_ext_cap_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int xhci_ext_cap_init(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_ext_cap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588348656,
      "name": "xhci_ext_cap_init",
      "external": true,
      "loc": "drivers/usb/host/xhci-ext-caps.c:83",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588348656,
      "name": "xhci_ext_cap_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int xhci_ext_cap_init(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_ext_cap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588379680,
      "name": "xhci_ext_cap_init",
      "external": true,
      "loc": "drivers/usb/host/xhci-ext-caps.c:83",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588379680,
      "name": "xhci_ext_cap_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int xhci_ext_cap_init(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_ext_cap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588262064,
      "name": "xhci_ext_cap_init",
      "external": true,
      "loc": "drivers/usb/host/xhci-ext-caps.c:84",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588262064,
      "name": "xhci_ext_cap_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int xhci_ext_cap_init(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_ext_cap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588912928,
      "name": "xhci_ext_cap_init",
      "external": true,
      "loc": "drivers/usb/host/xhci-ext-caps.c:84",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588912928,
      "name": "xhci_ext_cap_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int xhci_ext_cap_init(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_ext_cap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590342448,
      "name": "xhci_ext_cap_init",
      "external": true,
      "loc": "drivers/usb/host/xhci-ext-caps.c:84",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590342448,
      "name": "xhci_ext_cap_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
int xhci_ext_cap_init(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_ext_cap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591971264,
      "name": "xhci_ext_cap_init",
      "external": true,
      "loc": "drivers/usb/host/xhci-ext-caps.c:84",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591971264,
      "name": "xhci_ext_cap_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
int xhci_ext_cap_init(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_ext_cap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592392320,
      "name": "xhci_ext_cap_init",
      "external": true,
      "loc": "drivers/usb/host/xhci-ext-caps.c:84",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592392320,
      "name": "xhci_ext_cap_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
int xhci_ext_cap_init(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_ext_cap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593135264,
      "name": "xhci_ext_cap_init",
      "external": true,
      "loc": "drivers/usb/host/xhci-ext-caps.c:84",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593135264,
      "name": "xhci_ext_cap_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
int xhci_ext_cap_init(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_ext_cap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500623720,
      "name": "xhci_ext_cap_init",
      "external": true,
      "loc": "drivers/usb/host/xhci-ext-caps.c:83",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500623720,
      "name": "xhci_ext_cap_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
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
int xhci_ext_cap_init(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_ext_cap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233083024,
      "name": "xhci_ext_cap_init",
      "external": true,
      "loc": "drivers/usb/host/xhci-ext-caps.c:83",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233083024,
      "name": "xhci_ext_cap_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 736
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
int xhci_ext_cap_init(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_ext_cap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294039472,
      "name": "xhci_ext_cap_init",
      "external": true,
      "loc": "drivers/usb/host/xhci-ext-caps.c:83",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294039472,
      "name": "xhci_ext_cap_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1236
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
int xhci_ext_cap_init(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_ext_cap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277490604,
      "name": "xhci_ext_cap_init",
      "external": true,
      "loc": "drivers/usb/host/xhci-ext-caps.c:83",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277490604,
      "name": "xhci_ext_cap_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 632
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
int xhci_ext_cap_init(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_ext_cap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_ext_cap_init",
      "external": true,
      "loc": "drivers/usb/host/xhci-ext-caps.c:83",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587192440,
      "name": "xhci_ext_cap_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071587192000,
      "name": "xhci_ext_cap_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int xhci_ext_cap_init(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_ext_cap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_ext_cap_init",
      "external": true,
      "loc": "drivers/usb/host/xhci-ext-caps.c:83",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586951192,
      "name": "xhci_ext_cap_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071586950752,
      "name": "xhci_ext_cap_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int xhci_ext_cap_init(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_ext_cap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_ext_cap_init",
      "external": true,
      "loc": "drivers/usb/host/xhci-ext-caps.c:83",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587440968,
      "name": "xhci_ext_cap_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071587440528,
      "name": "xhci_ext_cap_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int xhci_ext_cap_init(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_ext_cap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_ext_cap_init",
      "external": true,
      "loc": "drivers/usb/host/xhci-ext-caps.c:83",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587547944,
      "name": "xhci_ext_cap_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071587547504,
      "name": "xhci_ext_cap_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int xhci_ext_cap_init(struct xhci_hcd * xhci)
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
