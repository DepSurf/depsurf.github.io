# Function: <code>pcie_wait_for_link</code>

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
bool pcie_wait_for_link(struct pci_dev * pdev, bool active)
```

```json
{
  "name": "pcie_wait_for_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584212704,
      "name": "pcie_wait_for_link",
      "external": true,
      "loc": "drivers/pci/pci.c:4248",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_fatal_recovery",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584212704,
      "name": "pcie_wait_for_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
bool pcie_wait_for_link(struct pci_dev * pdev, bool active)
```

```json
{
  "name": "pcie_wait_for_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584302192,
      "name": "pcie_wait_for_link",
      "external": true,
      "loc": "drivers/pci/pci.c:4520",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584302192,
      "name": "pcie_wait_for_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
bool pcie_wait_for_link(struct pci_dev * pdev, bool active)
```

```json
{
  "name": "pcie_wait_for_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_wait_for_link",
      "external": true,
      "loc": "drivers/pci/pci.c:4617",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584501170,
      "name": "pcie_wait_for_link.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071584495936,
      "name": "pcie_wait_for_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
bool pcie_wait_for_link(struct pci_dev * pdev, bool active)
```

```json
{
  "name": "pcie_wait_for_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584631552,
      "name": "pcie_wait_for_link",
      "external": true,
      "loc": "drivers/pci/pci.c:4667",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584631552,
      "name": "pcie_wait_for_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool pcie_wait_for_link(struct pci_dev * pdev, bool active)
```

```json
{
  "name": "pcie_wait_for_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585314592,
      "name": "pcie_wait_for_link",
      "external": true,
      "loc": "drivers/pci/pci.c:4697",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585314592,
      "name": "pcie_wait_for_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool pcie_wait_for_link(struct pci_dev * pdev, bool active)
```

```json
{
  "name": "pcie_wait_for_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585469472,
      "name": "pcie_wait_for_link",
      "external": true,
      "loc": "drivers/pci/pci.c:4770",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585469472,
      "name": "pcie_wait_for_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool pcie_wait_for_link(struct pci_dev * pdev, bool active)
```

```json
{
  "name": "pcie_wait_for_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585349280,
      "name": "pcie_wait_for_link",
      "external": true,
      "loc": "drivers/pci/pci.c:4819",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585349280,
      "name": "pcie_wait_for_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool pcie_wait_for_link(struct pci_dev * pdev, bool active)
```

```json
{
  "name": "pcie_wait_for_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585808512,
      "name": "pcie_wait_for_link",
      "external": true,
      "loc": "drivers/pci/pci.c:4871",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585808512,
      "name": "pcie_wait_for_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool pcie_wait_for_link(struct pci_dev * pdev, bool active)
```

```json
{
  "name": "pcie_wait_for_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586997344,
      "name": "pcie_wait_for_link",
      "external": true,
      "loc": "drivers/pci/pci.c:4967",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586997344,
      "name": "pcie_wait_for_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool pcie_wait_for_link(struct pci_dev * pdev, bool active)
```

```json
{
  "name": "pcie_wait_for_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588165664,
      "name": "pcie_wait_for_link",
      "external": true,
      "loc": "drivers/pci/pci.c:4910",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588165664,
      "name": "pcie_wait_for_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool pcie_wait_for_link(struct pci_dev * pdev, bool active)
```

```json
{
  "name": "pcie_wait_for_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588441392,
      "name": "pcie_wait_for_link",
      "external": true,
      "loc": "drivers/pci/pci.c:5016",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588441392,
      "name": "pcie_wait_for_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
bool pcie_wait_for_link(struct pci_dev * pdev, bool active)
```

```json
{
  "name": "pcie_wait_for_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588738256,
      "name": "pcie_wait_for_link",
      "external": true,
      "loc": "drivers/pci/pci.c:5126",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588738256,
      "name": "pcie_wait_for_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
bool pcie_wait_for_link(struct pci_dev * pdev, bool active)
```

```json
{
  "name": "pcie_wait_for_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496877880,
      "name": "pcie_wait_for_link",
      "external": true,
      "loc": "drivers/pci/pci.c:4667",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496877880,
      "name": "pcie_wait_for_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
bool pcie_wait_for_link(struct pci_dev * pdev, bool active)
```

```json
{
  "name": "pcie_wait_for_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230154996,
      "name": "pcie_wait_for_link",
      "external": true,
      "loc": "drivers/pci/pci.c:4667",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:dpc_reset_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230154996,
      "name": "pcie_wait_for_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool pcie_wait_for_link(struct pci_dev * pdev, bool active)
```

```json
{
  "name": "pcie_wait_for_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290961776,
      "name": "pcie_wait_for_link",
      "external": true,
      "loc": "drivers/pci/pci.c:4667",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290961776,
      "name": "pcie_wait_for_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
bool pcie_wait_for_link(struct pci_dev * pdev, bool active)
```

```json
{
  "name": "pcie_wait_for_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275576120,
      "name": "pcie_wait_for_link",
      "external": true,
      "loc": "drivers/pci/pci.c:4667",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275576120,
      "name": "pcie_wait_for_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
bool pcie_wait_for_link(struct pci_dev * pdev, bool active)
```

```json
{
  "name": "pcie_wait_for_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584583712,
      "name": "pcie_wait_for_link",
      "external": true,
      "loc": "drivers/pci/pci.c:4667",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584583712,
      "name": "pcie_wait_for_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool pcie_wait_for_link(struct pci_dev * pdev, bool active)
```

```json
{
  "name": "pcie_wait_for_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584511840,
      "name": "pcie_wait_for_link",
      "external": true,
      "loc": "drivers/pci/pci.c:4667",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584511840,
      "name": "pcie_wait_for_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool pcie_wait_for_link(struct pci_dev * pdev, bool active)
```

```json
{
  "name": "pcie_wait_for_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584581712,
      "name": "pcie_wait_for_link",
      "external": true,
      "loc": "drivers/pci/pci.c:4667",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584581712,
      "name": "pcie_wait_for_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool pcie_wait_for_link(struct pci_dev * pdev, bool active)
```

```json
{
  "name": "pcie_wait_for_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584689424,
      "name": "pcie_wait_for_link",
      "external": true,
      "loc": "drivers/pci/pci.c:4667",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584689424,
      "name": "pcie_wait_for_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool pcie_wait_for_link(struct pci_dev * pdev, bool active)
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
