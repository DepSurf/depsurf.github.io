# Function: <code>pcie_shutdown_notification</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_shutdown_notification",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583373340,
      "name": "pcie_shutdown_notification",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:733",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl"
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
  "name": "pcie_shutdown_notification",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583686700,
      "name": "pcie_shutdown_notification",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:737",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl"
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
  "name": "pcie_shutdown_notification",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583824988,
      "name": "pcie_shutdown_notification",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:773",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl"
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
  "name": "pcie_shutdown_notification",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583867852,
      "name": "pcie_shutdown_notification",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:781",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl"
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
  "name": "pcie_shutdown_notification",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584131452,
      "name": "pcie_shutdown_notification",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:777",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void pcie_shutdown_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_shutdown_notification",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584330976,
      "name": "pcie_shutdown_notification",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:761",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584330976,
      "name": "pcie_shutdown_notification",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void pcie_shutdown_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_shutdown_notification",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584426592,
      "name": "pcie_shutdown_notification",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:811",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584426592,
      "name": "pcie_shutdown_notification",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void pcie_shutdown_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_shutdown_notification",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584622864,
      "name": "pcie_shutdown_notification",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:813",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584622864,
      "name": "pcie_shutdown_notification",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void pcie_shutdown_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_shutdown_notification",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584760560,
      "name": "pcie_shutdown_notification",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:827",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584760560,
      "name": "pcie_shutdown_notification",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void pcie_shutdown_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_shutdown_notification",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585451744,
      "name": "pcie_shutdown_notification",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:877",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585451744,
      "name": "pcie_shutdown_notification",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void pcie_shutdown_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_shutdown_notification",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585600048,
      "name": "pcie_shutdown_notification",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:880",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585600048,
      "name": "pcie_shutdown_notification",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void pcie_shutdown_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_shutdown_notification",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585478464,
      "name": "pcie_shutdown_notification",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:916",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585478464,
      "name": "pcie_shutdown_notification",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void pcie_shutdown_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_shutdown_notification",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_shutdown_notification",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:917",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592382533,
      "name": "pcie_shutdown_notification.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585944768,
      "name": "pcie_shutdown_notification",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void pcie_shutdown_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_shutdown_notification",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_shutdown_notification",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:945",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594246369,
      "name": "pcie_shutdown_notification.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587148464,
      "name": "pcie_shutdown_notification",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void pcie_shutdown_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_shutdown_notification",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_shutdown_notification",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:947",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596210546,
      "name": "pcie_shutdown_notification.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588353680,
      "name": "pcie_shutdown_notification",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void pcie_shutdown_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_shutdown_notification",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_shutdown_notification",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:938",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596735698,
      "name": "pcie_shutdown_notification.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588629808,
      "name": "pcie_shutdown_notification",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void pcie_shutdown_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_shutdown_notification",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_shutdown_notification",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:939",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597644282,
      "name": "pcie_shutdown_notification.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588929984,
      "name": "pcie_shutdown_notification",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void pcie_shutdown_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_shutdown_notification",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497024888,
      "name": "pcie_shutdown_notification",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:827",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497024888,
      "name": "pcie_shutdown_notification",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void pcie_shutdown_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_shutdown_notification",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275683146,
      "name": "pcie_shutdown_notification",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:827",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275683146,
      "name": "pcie_shutdown_notification",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void pcie_shutdown_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_shutdown_notification",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584709376,
      "name": "pcie_shutdown_notification",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:827",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584709376,
      "name": "pcie_shutdown_notification",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void pcie_shutdown_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_shutdown_notification",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584640144,
      "name": "pcie_shutdown_notification",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:827",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584640144,
      "name": "pcie_shutdown_notification",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void pcie_shutdown_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_shutdown_notification",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584710720,
      "name": "pcie_shutdown_notification",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:827",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584710720,
      "name": "pcie_shutdown_notification",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void pcie_shutdown_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_shutdown_notification",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584818304,
      "name": "pcie_shutdown_notification",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:827",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584818304,
      "name": "pcie_shutdown_notification",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void pcie_shutdown_notification(struct controller * ctrl)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void pcie_shutdown_notification(struct controller * ctrl)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void pcie_shutdown_notification(struct controller * ctrl)
```
</details>
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
