# Function: <code>get_latch_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int get_latch_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_latch_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583351416,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:83",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583353552,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:205",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583362992,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:188",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583373760,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:240",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583353552,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071583362992,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071583373760,
      "name": "get_latch_status",
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
int get_latch_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_latch_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583664520,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:83",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583666672,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:205",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583676240,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:188",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583687120,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:240",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583666672,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071583676240,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071583687120,
      "name": "get_latch_status",
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
int get_latch_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_latch_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583802744,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:80",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583804896,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:205",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583814448,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:190",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583825408,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:240",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583804896,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071583814448,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071583825408,
      "name": "get_latch_status",
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
int get_latch_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_latch_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583845784,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:80",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583847920,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:206",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583857408,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:190",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583868272,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:240",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583847920,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071583857408,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071583868272,
      "name": "get_latch_status",
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
int get_latch_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_latch_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584109304,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:80",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584111488,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:206",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584120992,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:190",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584131872,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:240",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584111488,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071584120992,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584131872,
      "name": "get_latch_status",
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
int get_latch_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_latch_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584309768,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:66",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584312160,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:192",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584321504,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:182",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584332752,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:243",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe"
      ]
    },
    {
      "addr": 18446744071584348048,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:226",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584312160,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071584321504,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584332752,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071584348048,
      "name": "get_latch_status",
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
int get_latch_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_latch_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584405800,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:64",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584408064,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:173",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584416624,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:124",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584428208,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:209",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584443312,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:226",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584408064,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584416624,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071584428208,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071584443312,
      "name": "get_latch_status",
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
int get_latch_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_latch_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584601928,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:64",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584604256,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:173",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584612848,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:122",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:209",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584639984,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:226",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584604256,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584612848,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071584624656,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071584625955,
      "name": "get_latch_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584639984,
      "name": "get_latch_status",
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
int get_latch_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_latch_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584739752,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:64",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584742048,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:173",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584750688,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:127",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:209",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584777664,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:226",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584742048,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584750688,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071584762352,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071584763651,
      "name": "get_latch_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584777664,
      "name": "get_latch_status",
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
int get_latch_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_latch_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585430200,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:64",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585432608,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:173",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585441392,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:127",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:209",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ]
    },
    {
      "addr": 18446744071585469024,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:226",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585432608,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071585441392,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071585453632,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071585454992,
      "name": "get_latch_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585469024,
      "name": "get_latch_status",
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
int get_latch_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_latch_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585582136,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:64",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585584336,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:173",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585590992,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:127",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:209",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ]
    },
    {
      "addr": 18446744071585610896,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:226",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585584336,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071585590992,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071585601536,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071591412713,
      "name": "get_latch_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585610896,
      "name": "get_latch_status",
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
int get_latch_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_latch_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585460696,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:64",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585462880,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:173",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585469456,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:127",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:209",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ]
    },
    {
      "addr": 18446744071585489344,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:226",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585462880,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071585469456,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071585479952,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071591355092,
      "name": "get_latch_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585489344,
      "name": "get_latch_status",
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
int get_latch_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_latch_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585926392,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:64",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585929136,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:173",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585935696,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:127",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:209",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ]
    },
    {
      "addr": 18446744071585956272,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:226",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585929136,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071585935696,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071585946368,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071592382840,
      "name": "get_latch_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071585956272,
      "name": "get_latch_status",
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
int get_latch_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_latch_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587128412,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:64",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587131376,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:173",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587138448,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:127",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:209",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ]
    },
    {
      "addr": 18446744071587160768,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:226",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587131376,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071587138448,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071587150208,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071594246676,
      "name": "get_latch_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071587160768,
      "name": "get_latch_status",
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
int get_latch_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_latch_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588328124,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:64",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588331488,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:173",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588341136,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:127",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:209",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ]
    },
    {
      "addr": 18446744071588373104,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:226",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588331488,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071588341136,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071588355728,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071596210630,
      "name": "get_latch_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588373104,
      "name": "get_latch_status",
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
int get_latch_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_latch_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588604220,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:64",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588607584,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:173",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588617232,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:127",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:208",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ]
    },
    {
      "addr": 18446744071588649056,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:225",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588607584,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071588617232,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071588631840,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071596735782,
      "name": "get_latch_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588649056,
      "name": "get_latch_status",
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
int get_latch_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_latch_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588904300,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:64",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588907664,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:173",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588917360,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:128",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:208",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ]
    },
    {
      "addr": 18446744071588949456,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:224",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588907664,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071588917360,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071588932064,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071597644366,
      "name": "get_latch_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588949456,
      "name": "get_latch_status",
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
int get_latch_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_latch_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497002148,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:64",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497004424,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:173",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497013808,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:127",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497026592,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:209",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497042992,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:226",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497004424,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446603336497013808,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446603336497026592,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446603336497042992,
      "name": "get_latch_status",
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
int get_latch_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_latch_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291075168,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:64",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291078688,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:173",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291078688,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
int get_latch_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_latch_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275665220,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:64",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275667050,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:173",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275674130,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:127",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275684720,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:209",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275667050,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446743936275674130,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446743936275684720,
      "name": "get_latch_status",
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
int get_latch_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_latch_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584688568,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:64",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584690864,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:173",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584699504,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:127",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:209",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584726480,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:226",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584690864,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584699504,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071584711168,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071584712467,
      "name": "get_latch_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584726480,
      "name": "get_latch_status",
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
int get_latch_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_latch_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584619336,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:64",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584621632,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:173",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584630272,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:127",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:209",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584657248,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:226",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584621632,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584630272,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071584641936,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071584643235,
      "name": "get_latch_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584657248,
      "name": "get_latch_status",
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
int get_latch_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_latch_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584689912,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:64",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584692208,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:173",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584700848,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:127",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:209",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584727824,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:226",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584692208,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584700848,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071584712512,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071584713811,
      "name": "get_latch_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584727824,
      "name": "get_latch_status",
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
int get_latch_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_latch_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584797560,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:64",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584799856,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:173",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584808496,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:127",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:209",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584835392,
      "name": "get_latch_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:226",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584799856,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584808496,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071584820096,
      "name": "get_latch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071584821395,
      "name": "get_latch_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584835392,
      "name": "get_latch_status",
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
int get_latch_status(struct hotplug_slot * slot, u8 * value)
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
