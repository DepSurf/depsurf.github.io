# Function: <code>get_attention_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int get_attention_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583351592,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:82",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583353696,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:183",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583362960,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:180",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583374048,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:216",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583353696,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071583362960,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071583374048,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
int get_attention_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583664696,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:82",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583666816,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:183",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583676208,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:180",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583687392,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:216",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583666816,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071583676208,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071583687392,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int get_attention_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583802920,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:79",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583805040,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:183",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583814416,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:182",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583825680,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:216",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583805040,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071583814416,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071583825680,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int get_attention_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583845960,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:79",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583848064,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:184",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583857376,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:182",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583868544,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:216",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583848064,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071583857376,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071583868544,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
int get_attention_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584109496,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:79",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584111632,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:184",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584120960,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:182",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584132144,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:216",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584111632,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071584120960,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584132144,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
int get_attention_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584309960,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:65",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584312272,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:170",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584321472,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:174",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584332608,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:228",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe"
      ]
    },
    {
      "addr": 18446744071584348320,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:202",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584312272,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071584321472,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584332608,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071584348320,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
int get_attention_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584405976,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:63",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584408176,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:149",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584428080,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:194",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584443392,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:202",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584408176,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071584428080,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071584443392,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
int get_attention_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584602104,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:63",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584604368,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:149",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:194",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584640064,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:202",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584604368,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071584624576,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071584625901,
      "name": "get_attention_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584640064,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int get_attention_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584739928,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:63",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584742160,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:149",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:194",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584777744,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:202",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584742160,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071584762272,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071584763597,
      "name": "get_attention_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584777744,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int get_attention_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585430376,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:63",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585432720,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:149",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:194",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ]
    },
    {
      "addr": 18446744071585469104,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:202",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585432720,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071585453552,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071585454938,
      "name": "get_attention_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585469104,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int get_attention_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585582312,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:63",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585584448,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:149",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:194",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ]
    },
    {
      "addr": 18446744071585610976,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:202",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585584448,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071585601456,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071591412659,
      "name": "get_attention_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585610976,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int get_attention_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585460872,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:63",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585462992,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:149",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:194",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ]
    },
    {
      "addr": 18446744071585489424,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:202",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585462992,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071585479872,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071591355038,
      "name": "get_attention_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585489424,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int get_attention_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585926568,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:63",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585929248,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:149",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:194",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ]
    },
    {
      "addr": 18446744071585956352,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:202",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585929248,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071585946272,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071592382765,
      "name": "get_attention_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071585956352,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int get_attention_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587128604,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:63",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587131504,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:149",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:194",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ]
    },
    {
      "addr": 18446744071587160864,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:202",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587131504,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071587150096,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071594246601,
      "name": "get_attention_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071587160864,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
int get_attention_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588328332,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:63",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588331680,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:149",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:194",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ]
    },
    {
      "addr": 18446744071588373216,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:202",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588331680,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071588355552,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071596210609,
      "name": "get_attention_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588373216,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
int get_attention_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588604428,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:63",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588607776,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:149",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:193",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ]
    },
    {
      "addr": 18446744071588649168,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:201",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588607776,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071588631664,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071596735761,
      "name": "get_attention_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588649168,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
int get_attention_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588904508,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:63",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588907856,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:149",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:193",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ]
    },
    {
      "addr": 18446744071588949568,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:200",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588907856,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071588931888,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071597644345,
      "name": "get_attention_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588949568,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
int get_attention_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497002348,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:63",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497004608,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:149",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497026432,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:194",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497043136,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:202",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497004608,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446603336497026432,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446603336497043136,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int get_attention_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291075440,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:63",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291078912,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:149",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291078912,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
int get_attention_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275665366,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:63",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275667204,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:149",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275684590,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:194",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275667204,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446743936275684590,
      "name": "get_attention_status",
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
int get_attention_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584688744,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:63",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584690976,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:149",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:194",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584726560,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:202",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584690976,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071584711088,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071584712413,
      "name": "get_attention_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584726560,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int get_attention_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584619512,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:63",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584621744,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:149",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:194",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584657328,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:202",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584621744,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071584641856,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071584643181,
      "name": "get_attention_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584657328,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int get_attention_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584690088,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:63",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584692320,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:149",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:194",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584727904,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:202",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584692320,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071584712432,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071584713757,
      "name": "get_attention_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584727904,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int get_attention_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584797736,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:63",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584799968,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:149",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:194",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584835472,
      "name": "get_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:202",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584799968,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071584820016,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071584821341,
      "name": "get_attention_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584835472,
      "name": "get_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int get_attention_status(struct hotplug_slot * slot, u8 * value)
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
