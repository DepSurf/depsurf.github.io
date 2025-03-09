# Function: <code>__pcie_print_link_status</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void __pcie_print_link_status(struct pci_dev * dev, bool verbose)
```

```json
{
  "name": "__pcie_print_link_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584304896,
      "name": "__pcie_print_link_status",
      "external": true,
      "loc": "drivers/pci/pci.c:5641",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/pci.c:pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584304896,
      "name": "__pcie_print_link_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 505
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
void __pcie_print_link_status(struct pci_dev * dev, bool verbose)
```

```json
{
  "name": "__pcie_print_link_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pcie_print_link_status",
      "external": true,
      "loc": "drivers/pci/pci.c:5737",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584501211,
      "name": "__pcie_print_link_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
    },
    {
      "addr": 18446744071584498624,
      "name": "__pcie_print_link_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void __pcie_print_link_status(struct pci_dev * dev, bool verbose)
```

```json
{
  "name": "__pcie_print_link_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pcie_print_link_status",
      "external": true,
      "loc": "drivers/pci/pci.c:5867",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584637133,
      "name": "__pcie_print_link_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
    },
    {
      "addr": 18446744071584634528,
      "name": "__pcie_print_link_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void __pcie_print_link_status(struct pci_dev * dev, bool verbose)
```

```json
{
  "name": "__pcie_print_link_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585317392,
      "name": "__pcie_print_link_status",
      "external": true,
      "loc": "drivers/pci/pci.c:5888",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585317392,
      "name": "__pcie_print_link_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
void __pcie_print_link_status(struct pci_dev * dev, bool verbose)
```

```json
{
  "name": "__pcie_print_link_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585472368,
      "name": "__pcie_print_link_status",
      "external": true,
      "loc": "drivers/pci/pci.c:5962",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585472368,
      "name": "__pcie_print_link_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
void __pcie_print_link_status(struct pci_dev * dev, bool verbose)
```

```json
{
  "name": "__pcie_print_link_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585352224,
      "name": "__pcie_print_link_status",
      "external": true,
      "loc": "drivers/pci/pci.c:6011",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585352224,
      "name": "__pcie_print_link_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
void __pcie_print_link_status(struct pci_dev * dev, bool verbose)
```

```json
{
  "name": "__pcie_print_link_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585811216,
      "name": "__pcie_print_link_status",
      "external": true,
      "loc": "drivers/pci/pci.c:6201",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585811216,
      "name": "__pcie_print_link_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
void __pcie_print_link_status(struct pci_dev * dev, bool verbose)
```

```json
{
  "name": "__pcie_print_link_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587000224,
      "name": "__pcie_print_link_status",
      "external": true,
      "loc": "drivers/pci/pci.c:6297",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587000224,
      "name": "__pcie_print_link_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
void __pcie_print_link_status(struct pci_dev * dev, bool verbose)
```

```json
{
  "name": "__pcie_print_link_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588168800,
      "name": "__pcie_print_link_status",
      "external": true,
      "loc": "drivers/pci/pci.c:6244",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588168800,
      "name": "__pcie_print_link_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
void __pcie_print_link_status(struct pci_dev * dev, bool verbose)
```

```json
{
  "name": "__pcie_print_link_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588444848,
      "name": "__pcie_print_link_status",
      "external": true,
      "loc": "drivers/pci/pci.c:6366",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588444848,
      "name": "__pcie_print_link_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
void __pcie_print_link_status(struct pci_dev * dev, bool verbose)
```

```json
{
  "name": "__pcie_print_link_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588741712,
      "name": "__pcie_print_link_status",
      "external": true,
      "loc": "drivers/pci/pci.c:6510",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588741712,
      "name": "__pcie_print_link_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
void __pcie_print_link_status(struct pci_dev * dev, bool verbose)
```

```json
{
  "name": "__pcie_print_link_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496881184,
      "name": "__pcie_print_link_status",
      "external": true,
      "loc": "drivers/pci/pci.c:5867",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496881184,
      "name": "__pcie_print_link_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
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
void __pcie_print_link_status(struct pci_dev * dev, bool verbose)
```

```json
{
  "name": "__pcie_print_link_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230158224,
      "name": "__pcie_print_link_status",
      "external": true,
      "loc": "drivers/pci/pci.c:5867",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230158224,
      "name": "__pcie_print_link_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
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
void __pcie_print_link_status(struct pci_dev * dev, bool verbose)
```

```json
{
  "name": "__pcie_print_link_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290965968,
      "name": "__pcie_print_link_status",
      "external": true,
      "loc": "drivers/pci/pci.c:5867",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290965968,
      "name": "__pcie_print_link_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 668
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
void __pcie_print_link_status(struct pci_dev * dev, bool verbose)
```

```json
{
  "name": "__pcie_print_link_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275579016,
      "name": "__pcie_print_link_status",
      "external": true,
      "loc": "drivers/pci/pci.c:5867",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275579016,
      "name": "__pcie_print_link_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
void __pcie_print_link_status(struct pci_dev * dev, bool verbose)
```

```json
{
  "name": "__pcie_print_link_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pcie_print_link_status",
      "external": true,
      "loc": "drivers/pci/pci.c:5867",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584589293,
      "name": "__pcie_print_link_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
    },
    {
      "addr": 18446744071584586688,
      "name": "__pcie_print_link_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void __pcie_print_link_status(struct pci_dev * dev, bool verbose)
```

```json
{
  "name": "__pcie_print_link_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pcie_print_link_status",
      "external": true,
      "loc": "drivers/pci/pci.c:5867",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584517421,
      "name": "__pcie_print_link_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
    },
    {
      "addr": 18446744071584514816,
      "name": "__pcie_print_link_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void __pcie_print_link_status(struct pci_dev * dev, bool verbose)
```

```json
{
  "name": "__pcie_print_link_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pcie_print_link_status",
      "external": true,
      "loc": "drivers/pci/pci.c:5867",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584587293,
      "name": "__pcie_print_link_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
    },
    {
      "addr": 18446744071584584688,
      "name": "__pcie_print_link_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void __pcie_print_link_status(struct pci_dev * dev, bool verbose)
```

```json
{
  "name": "__pcie_print_link_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pcie_print_link_status",
      "external": true,
      "loc": "drivers/pci/pci.c:5867",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584694989,
      "name": "__pcie_print_link_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
    },
    {
      "addr": 18446744071584692352,
      "name": "__pcie_print_link_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void __pcie_print_link_status(struct pci_dev * dev, bool verbose)
```
</details>
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
