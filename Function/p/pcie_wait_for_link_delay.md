# Function: <code>pcie_wait_for_link_delay</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
bool pcie_wait_for_link_delay(struct pci_dev * pdev, bool active, int delay)
```

```json
{
  "name": "pcie_wait_for_link_delay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_wait_for_link_delay",
      "external": false,
      "loc": "drivers/pci/pci.c:4615",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci.c:pcie_wait_for_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584610224,
      "name": "pcie_wait_for_link_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    },
    {
      "addr": 18446744071584636037,
      "name": "pcie_wait_for_link_delay.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
bool pcie_wait_for_link_delay(struct pci_dev * pdev, bool active, int delay)
```

```json
{
  "name": "pcie_wait_for_link_delay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_wait_for_link_delay",
      "external": false,
      "loc": "drivers/pci/pci.c:4645",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci.c:pcie_wait_for_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585287776,
      "name": "pcie_wait_for_link_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    },
    {
      "addr": 18446744071585319426,
      "name": "pcie_wait_for_link_delay.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
bool pcie_wait_for_link_delay(struct pci_dev * pdev, bool active, int delay)
```

```json
{
  "name": "pcie_wait_for_link_delay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585442448,
      "name": "pcie_wait_for_link_delay",
      "external": false,
      "loc": "drivers/pci/pci.c:4720",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci.c:pcie_wait_for_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585442448,
      "name": "pcie_wait_for_link_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
bool pcie_wait_for_link_delay(struct pci_dev * pdev, bool active, int delay)
```

```json
{
  "name": "pcie_wait_for_link_delay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585322608,
      "name": "pcie_wait_for_link_delay",
      "external": false,
      "loc": "drivers/pci/pci.c:4769",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci.c:pcie_wait_for_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585322608,
      "name": "pcie_wait_for_link_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
bool pcie_wait_for_link_delay(struct pci_dev * pdev, bool active, int delay)
```

```json
{
  "name": "pcie_wait_for_link_delay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585779008,
      "name": "pcie_wait_for_link_delay",
      "external": false,
      "loc": "drivers/pci/pci.c:4821",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci.c:pcie_wait_for_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585779008,
      "name": "pcie_wait_for_link_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
bool pcie_wait_for_link_delay(struct pci_dev * pdev, bool active, int delay)
```

```json
{
  "name": "pcie_wait_for_link_delay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586966752,
      "name": "pcie_wait_for_link_delay",
      "external": false,
      "loc": "drivers/pci/pci.c:4917",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci.c:pcie_wait_for_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586966752,
      "name": "pcie_wait_for_link_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
bool pcie_wait_for_link_delay(struct pci_dev * pdev, bool active, int delay)
```

```json
{
  "name": "pcie_wait_for_link_delay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588131088,
      "name": "pcie_wait_for_link_delay",
      "external": false,
      "loc": "drivers/pci/pci.c:4860",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci.c:pcie_wait_for_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588131088,
      "name": "pcie_wait_for_link_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
bool pcie_wait_for_link_delay(struct pci_dev * pdev, bool active, int delay)
```

```json
{
  "name": "pcie_wait_for_link_delay",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588441397,
      "name": "pcie_wait_for_link_delay",
      "external": false,
      "loc": "drivers/pci/pci.c:4967",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pcie_wait_for_link"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588410048,
      "name": "pcie_wait_for_link_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
bool pcie_wait_for_link_delay(struct pci_dev * pdev, bool active, int delay)
```

```json
{
  "name": "pcie_wait_for_link_delay",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588738261,
      "name": "pcie_wait_for_link_delay",
      "external": false,
      "loc": "drivers/pci/pci.c:5077",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pcie_wait_for_link"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588705328,
      "name": "pcie_wait_for_link_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
bool pcie_wait_for_link_delay(struct pci_dev * pdev, bool active, int delay)
```

```json
{
  "name": "pcie_wait_for_link_delay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496849480,
      "name": "pcie_wait_for_link_delay",
      "external": false,
      "loc": "drivers/pci/pci.c:4615",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci.c:pcie_wait_for_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496849480,
      "name": "pcie_wait_for_link_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
bool pcie_wait_for_link_delay(struct pci_dev * pdev, bool active, int delay)
```

```json
{
  "name": "pcie_wait_for_link_delay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230129884,
      "name": "pcie_wait_for_link_delay",
      "external": false,
      "loc": "drivers/pci/pci.c:4615",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci.c:pcie_wait_for_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230129884,
      "name": "pcie_wait_for_link_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
bool pcie_wait_for_link_delay(struct pci_dev * pdev, bool active, int delay)
```

```json
{
  "name": "pcie_wait_for_link_delay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290927520,
      "name": "pcie_wait_for_link_delay",
      "external": false,
      "loc": "drivers/pci/pci.c:4615",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci.c:pcie_wait_for_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290927520,
      "name": "pcie_wait_for_link_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
bool pcie_wait_for_link_delay(struct pci_dev * pdev, bool active, int delay)
```

```json
{
  "name": "pcie_wait_for_link_delay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275553550,
      "name": "pcie_wait_for_link_delay",
      "external": false,
      "loc": "drivers/pci/pci.c:4615",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci.c:pcie_wait_for_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275553550,
      "name": "pcie_wait_for_link_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
bool pcie_wait_for_link_delay(struct pci_dev * pdev, bool active, int delay)
```

```json
{
  "name": "pcie_wait_for_link_delay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_wait_for_link_delay",
      "external": false,
      "loc": "drivers/pci/pci.c:4615",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci.c:pcie_wait_for_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584562384,
      "name": "pcie_wait_for_link_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    },
    {
      "addr": 18446744071584588197,
      "name": "pcie_wait_for_link_delay.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
bool pcie_wait_for_link_delay(struct pci_dev * pdev, bool active, int delay)
```

```json
{
  "name": "pcie_wait_for_link_delay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_wait_for_link_delay",
      "external": false,
      "loc": "drivers/pci/pci.c:4615",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci.c:pcie_wait_for_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584490544,
      "name": "pcie_wait_for_link_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    },
    {
      "addr": 18446744071584516325,
      "name": "pcie_wait_for_link_delay.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
bool pcie_wait_for_link_delay(struct pci_dev * pdev, bool active, int delay)
```

```json
{
  "name": "pcie_wait_for_link_delay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_wait_for_link_delay",
      "external": false,
      "loc": "drivers/pci/pci.c:4615",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci.c:pcie_wait_for_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584560384,
      "name": "pcie_wait_for_link_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    },
    {
      "addr": 18446744071584586197,
      "name": "pcie_wait_for_link_delay.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
bool pcie_wait_for_link_delay(struct pci_dev * pdev, bool active, int delay)
```

```json
{
  "name": "pcie_wait_for_link_delay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_wait_for_link_delay",
      "external": false,
      "loc": "drivers/pci/pci.c:4615",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci.c:pcie_wait_for_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584668128,
      "name": "pcie_wait_for_link_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    },
    {
      "addr": 18446744071584693893,
      "name": "pcie_wait_for_link_delay.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
bool pcie_wait_for_link_delay(struct pci_dev * pdev, bool active, int delay)
```
</details>
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
