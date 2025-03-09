# Function: <code>get_power_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int get_power_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_power_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583351768,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:81",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:power_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583353456,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:174",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583362848,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:172",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583373856,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:194",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583353456,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071583362848,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071583373856,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int get_power_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_power_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583664872,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:81",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:power_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583666576,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:174",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583676096,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:172",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583687216,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:194",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583666576,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071583676096,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071583687216,
      "name": "get_power_status",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int get_power_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_power_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583803096,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:78",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:power_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583804800,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:174",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583814304,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:174",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583825504,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:194",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583804800,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071583814304,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071583825504,
      "name": "get_power_status",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int get_power_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_power_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583846136,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:78",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:power_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583847824,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:175",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583857264,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:174",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583868368,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:194",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583847824,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071583857264,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071583868368,
      "name": "get_power_status",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int get_power_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_power_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584109688,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:78",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:power_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584111392,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:175",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584120848,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:174",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584131968,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:194",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584111392,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071584120848,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584131968,
      "name": "get_power_status",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int get_power_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_power_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584310152,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:64",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:power_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584312064,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:161",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584321328,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:166",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584332464,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:213",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe"
      ]
    },
    {
      "addr": 18446744071584348144,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:180",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584312064,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584321328,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584332464,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071584348144,
      "name": "get_power_status",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int get_power_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_power_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584406152,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:62",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:power_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584407968,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:140",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584416704,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:113",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584427952,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:179",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584443712,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:180",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584407968,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584416704,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071584427952,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071584443712,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int get_power_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_power_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584602280,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:62",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:power_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584604160,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:140",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584612928,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:111",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:179",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584640384,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:180",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584604160,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584612928,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071584624496,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071584625847,
      "name": "get_power_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584640384,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int get_power_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_power_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584740104,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:62",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:power_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584741952,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:140",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584750768,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:116",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:179",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584778064,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:180",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584741952,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584750768,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071584762192,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071584763543,
      "name": "get_power_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584778064,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int get_power_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_power_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585430552,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:62",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:power_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585432512,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:140",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585441472,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:116",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:179",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ]
    },
    {
      "addr": 18446744071585469424,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:180",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585432512,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071585441472,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071585453472,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071585454884,
      "name": "get_power_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585469424,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int get_power_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_power_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585582488,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:62",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:power_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585584240,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:140",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585591072,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:116",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:179",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ]
    },
    {
      "addr": 18446744071585611296,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:180",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585584240,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071585591072,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071585601376,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071591412605,
      "name": "get_power_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585611296,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int get_power_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_power_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585461048,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:62",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:power_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585462784,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:140",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585469536,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:116",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:179",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ]
    },
    {
      "addr": 18446744071585489744,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:180",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585462784,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071585469536,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071585479792,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071591354984,
      "name": "get_power_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585489744,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int get_power_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_power_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585926744,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:62",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:power_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585929040,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:140",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585935776,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:116",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:179",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ]
    },
    {
      "addr": 18446744071585956672,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:180",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585929040,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071585935776,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071585946176,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071592382690,
      "name": "get_power_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071585956672,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int get_power_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_power_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587128796,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:62",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:power_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587131264,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:140",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587138528,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:116",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:179",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ]
    },
    {
      "addr": 18446744071587161184,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:180",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587131264,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071587138528,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071587149984,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071594246526,
      "name": "get_power_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071587161184,
      "name": "get_power_status",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int get_power_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_power_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588328540,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:62",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:power_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588331344,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:140",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588341232,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:116",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:179",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ]
    },
    {
      "addr": 18446744071588373568,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:180",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588331344,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071588341232,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071588355376,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071596210588,
      "name": "get_power_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588373568,
      "name": "get_power_status",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int get_power_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_power_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588604636,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:62",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:power_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588607440,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:140",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588617328,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:116",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:178",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ]
    },
    {
      "addr": 18446744071588649520,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:179",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588607440,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071588617328,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071588631488,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071596735740,
      "name": "get_power_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588649520,
      "name": "get_power_status",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int get_power_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_power_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588904716,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:62",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:power_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588907520,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:140",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588917456,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:117",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:178",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ]
    },
    {
      "addr": 18446744071588949920,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:178",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588907520,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071588917456,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071588931712,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071597644324,
      "name": "get_power_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588949920,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
int get_power_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_power_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497002548,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:62",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:power_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497004280,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:140",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497013904,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:116",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497026272,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:179",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497043504,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:180",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497004280,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446603336497013904,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446603336497026272,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446603336497043504,
      "name": "get_power_status",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
int get_power_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_power_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291075712,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:62",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:power_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291078528,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:140",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291078528,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
int get_power_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_power_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275665512,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:62",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:power_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275666932,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:140",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275674216,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:116",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275684460,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:179",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275666932,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446743936275674216,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446743936275684460,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int get_power_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_power_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584688920,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:62",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:power_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584690768,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:140",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584699584,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:116",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:179",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584726880,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:180",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584690768,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584699584,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071584711008,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071584712359,
      "name": "get_power_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584726880,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int get_power_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_power_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584619688,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:62",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:power_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584621536,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:140",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584630352,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:116",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:179",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584657648,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:180",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584621536,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584630352,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071584641776,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071584643127,
      "name": "get_power_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584657648,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int get_power_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_power_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584690264,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:62",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:power_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584692112,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:140",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584700928,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:116",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:179",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584728224,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:180",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584692112,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584700928,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071584712352,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071584713703,
      "name": "get_power_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584728224,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int get_power_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_power_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584797912,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:62",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:power_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584799760,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:140",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584808576,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:116",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:179",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584835792,
      "name": "get_power_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:180",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584799760,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584808576,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071584819936,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071584821287,
      "name": "get_power_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584835792,
      "name": "get_power_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int get_power_status(struct hotplug_slot * slot, u8 * value)
```
</details>
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
