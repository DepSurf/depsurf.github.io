# Function: <code>pci_d3cold_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_d3cold_disable(struct pci_dev * dev)
```

```json
{
  "name": "pci_d3cold_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583569760,
      "name": "pci_d3cold_disable",
      "external": true,
      "loc": "drivers/pci/pci.c:2329",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:d3cold_allowed_store",
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583569760,
      "name": "pci_d3cold_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void pci_d3cold_disable(struct pci_dev * dev)
```

```json
{
  "name": "pci_d3cold_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583712912,
      "name": "pci_d3cold_disable",
      "external": true,
      "loc": "drivers/pci/pci.c:2367",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:d3cold_allowed_store",
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583712912,
      "name": "pci_d3cold_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void pci_d3cold_disable(struct pci_dev * dev)
```

```json
{
  "name": "pci_d3cold_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583754064,
      "name": "pci_d3cold_disable",
      "external": true,
      "loc": "drivers/pci/pci.c:2384",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:d3cold_allowed_store",
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583754064,
      "name": "pci_d3cold_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void pci_d3cold_disable(struct pci_dev * dev)
```

```json
{
  "name": "pci_d3cold_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584013088,
      "name": "pci_d3cold_disable",
      "external": true,
      "loc": "drivers/pci/pci.c:2393",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:d3cold_allowed_store",
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584013088,
      "name": "pci_d3cold_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void pci_d3cold_disable(struct pci_dev * dev)
```

```json
{
  "name": "pci_d3cold_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584208720,
      "name": "pci_d3cold_disable",
      "external": true,
      "loc": "drivers/pci/pci.c:2468",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:d3cold_allowed_store",
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584208720,
      "name": "pci_d3cold_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void pci_d3cold_disable(struct pci_dev * dev)
```

```json
{
  "name": "pci_d3cold_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584296592,
      "name": "pci_d3cold_disable",
      "external": true,
      "loc": "drivers/pci/pci.c:2658",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:d3cold_allowed_store",
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584296592,
      "name": "pci_d3cold_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void pci_d3cold_disable(struct pci_dev * dev)
```

```json
{
  "name": "pci_d3cold_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584491008,
      "name": "pci_d3cold_disable",
      "external": true,
      "loc": "drivers/pci/pci.c:2773",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:d3cold_allowed_store",
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584491008,
      "name": "pci_d3cold_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void pci_d3cold_disable(struct pci_dev * dev)
```

```json
{
  "name": "pci_d3cold_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584626592,
      "name": "pci_d3cold_disable",
      "external": true,
      "loc": "drivers/pci/pci.c:2769",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:d3cold_allowed_store",
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584626592,
      "name": "pci_d3cold_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void pci_d3cold_disable(struct pci_dev * dev)
```

```json
{
  "name": "pci_d3cold_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585309440,
      "name": "pci_d3cold_disable",
      "external": true,
      "loc": "drivers/pci/pci.c:2839",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:d3cold_allowed_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585309440,
      "name": "pci_d3cold_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void pci_d3cold_disable(struct pci_dev * dev)
```

```json
{
  "name": "pci_d3cold_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585466208,
      "name": "pci_d3cold_disable",
      "external": true,
      "loc": "drivers/pci/pci.c:3006",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:d3cold_allowed_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585466208,
      "name": "pci_d3cold_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void pci_d3cold_disable(struct pci_dev * dev)
```

```json
{
  "name": "pci_d3cold_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585346416,
      "name": "pci_d3cold_disable",
      "external": true,
      "loc": "drivers/pci/pci.c:3036",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:d3cold_allowed_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585346416,
      "name": "pci_d3cold_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void pci_d3cold_disable(struct pci_dev * dev)
```

```json
{
  "name": "pci_d3cold_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585805584,
      "name": "pci_d3cold_disable",
      "external": true,
      "loc": "drivers/pci/pci.c:3078",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:d3cold_allowed_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585805584,
      "name": "pci_d3cold_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void pci_d3cold_disable(struct pci_dev * dev)
```

```json
{
  "name": "pci_d3cold_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586994016,
      "name": "pci_d3cold_disable",
      "external": true,
      "loc": "drivers/pci/pci.c:3165",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:d3cold_allowed_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586994016,
      "name": "pci_d3cold_disable",
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
void pci_d3cold_disable(struct pci_dev * dev)
```

```json
{
  "name": "pci_d3cold_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588161648,
      "name": "pci_d3cold_disable",
      "external": true,
      "loc": "drivers/pci/pci.c:3115",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:d3cold_allowed_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588161648,
      "name": "pci_d3cold_disable",
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
void pci_d3cold_disable(struct pci_dev * dev)
```

```json
{
  "name": "pci_d3cold_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588437168,
      "name": "pci_d3cold_disable",
      "external": true,
      "loc": "drivers/pci/pci.c:3153",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:d3cold_allowed_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588437168,
      "name": "pci_d3cold_disable",
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
void pci_d3cold_disable(struct pci_dev * dev)
```

```json
{
  "name": "pci_d3cold_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588734000,
      "name": "pci_d3cold_disable",
      "external": true,
      "loc": "drivers/pci/pci.c:3266",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588734000,
      "name": "pci_d3cold_disable",
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
void pci_d3cold_disable(struct pci_dev * dev)
```

```json
{
  "name": "pci_d3cold_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496871296,
      "name": "pci_d3cold_disable",
      "external": true,
      "loc": "drivers/pci/pci.c:2769",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:d3cold_allowed_store",
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496871296,
      "name": "pci_d3cold_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void pci_d3cold_disable(struct pci_dev * dev)
```

```json
{
  "name": "pci_d3cold_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230148724,
      "name": "pci_d3cold_disable",
      "external": true,
      "loc": "drivers/pci/pci.c:2769",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230148724,
      "name": "pci_d3cold_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void pci_d3cold_disable(struct pci_dev * dev)
```

```json
{
  "name": "pci_d3cold_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290953600,
      "name": "pci_d3cold_disable",
      "external": true,
      "loc": "drivers/pci/pci.c:2769",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290953600,
      "name": "pci_d3cold_disable",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void pci_d3cold_disable(struct pci_dev * dev)
```

```json
{
  "name": "pci_d3cold_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275570266,
      "name": "pci_d3cold_disable",
      "external": true,
      "loc": "drivers/pci/pci.c:2769",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275570266,
      "name": "pci_d3cold_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void pci_d3cold_disable(struct pci_dev * dev)
```

```json
{
  "name": "pci_d3cold_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584578752,
      "name": "pci_d3cold_disable",
      "external": true,
      "loc": "drivers/pci/pci.c:2769",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:d3cold_allowed_store",
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584578752,
      "name": "pci_d3cold_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void pci_d3cold_disable(struct pci_dev * dev)
```

```json
{
  "name": "pci_d3cold_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584506880,
      "name": "pci_d3cold_disable",
      "external": true,
      "loc": "drivers/pci/pci.c:2769",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:d3cold_allowed_store",
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584506880,
      "name": "pci_d3cold_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void pci_d3cold_disable(struct pci_dev * dev)
```

```json
{
  "name": "pci_d3cold_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584576752,
      "name": "pci_d3cold_disable",
      "external": true,
      "loc": "drivers/pci/pci.c:2769",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:d3cold_allowed_store",
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584576752,
      "name": "pci_d3cold_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void pci_d3cold_disable(struct pci_dev * dev)
```

```json
{
  "name": "pci_d3cold_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584684464,
      "name": "pci_d3cold_disable",
      "external": true,
      "loc": "drivers/pci/pci.c:2769",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:d3cold_allowed_store",
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584684464,
      "name": "pci_d3cold_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void pci_d3cold_disable(struct pci_dev * dev)
```
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
