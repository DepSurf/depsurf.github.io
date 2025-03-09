# Function: <code>get_adapter_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int get_adapter_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_adapter_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583351240,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:84",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583353520,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:198",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583362624,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:196",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583373664,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:260",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583353520,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071583362624,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071583373664,
      "name": "get_adapter_status",
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
int get_adapter_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_adapter_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583664344,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:84",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583666640,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:198",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583675872,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:196",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583687024,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:260",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583666640,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071583675872,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071583687024,
      "name": "get_adapter_status",
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
int get_adapter_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_adapter_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583802568,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:81",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583804864,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:198",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583814080,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:198",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583825312,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:260",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583804864,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071583814080,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071583825312,
      "name": "get_adapter_status",
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
int get_adapter_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_adapter_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583845608,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:81",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583847888,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:199",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583857040,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:198",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583868176,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:260",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583847888,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071583857040,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071583868176,
      "name": "get_adapter_status",
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
int get_adapter_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_adapter_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584109112,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:81",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584111456,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:199",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584120624,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:198",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584131776,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:260",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584111456,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071584120624,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584131776,
      "name": "get_adapter_status",
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
int get_adapter_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_adapter_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584309576,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:67",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584312128,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:185",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584321104,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:190",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584332896,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:258",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe"
      ]
    },
    {
      "addr": 18446744071584347952,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:246",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584312128,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071584321104,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584332896,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071584347952,
      "name": "get_adapter_status",
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
int get_adapter_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_adapter_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584405624,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:65",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584408032,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:164",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584416544,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:135",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584428336,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:224",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584443232,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:246",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584408032,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584416544,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071584428336,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071584443232,
      "name": "get_adapter_status",
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
int get_adapter_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_adapter_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584601752,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:65",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584604224,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:164",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584612768,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:133",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:224",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584639904,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:246",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584604224,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584612768,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071584624736,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071584626009,
      "name": "get_adapter_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584639904,
      "name": "get_adapter_status",
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
int get_adapter_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_adapter_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584739576,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:65",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584742016,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:164",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584750592,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:138",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:224",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584777584,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:246",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584742016,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584750592,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071584762432,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071584763705,
      "name": "get_adapter_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584777584,
      "name": "get_adapter_status",
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
int get_adapter_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_adapter_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585430024,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:65",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585432576,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:164",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585441296,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:138",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:224",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ]
    },
    {
      "addr": 18446744071585468944,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:246",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585432576,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585441296,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071585453712,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071585455046,
      "name": "get_adapter_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585468944,
      "name": "get_adapter_status",
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
int get_adapter_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_adapter_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585581960,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:65",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585584304,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:164",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585590896,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:138",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:224",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ]
    },
    {
      "addr": 18446744071585610816,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:246",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585584304,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585590896,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071585601616,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071591412767,
      "name": "get_adapter_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585610816,
      "name": "get_adapter_status",
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
int get_adapter_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_adapter_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585460520,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:65",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585462848,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:164",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585469360,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:138",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:224",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ]
    },
    {
      "addr": 18446744071585489264,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:246",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585462848,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585469360,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071585480032,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071591355146,
      "name": "get_adapter_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585489264,
      "name": "get_adapter_status",
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
int get_adapter_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_adapter_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585926216,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:65",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585929104,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:164",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585935600,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:138",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:224",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ]
    },
    {
      "addr": 18446744071585956192,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:246",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585929104,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585935600,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071585946464,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071592382915,
      "name": "get_adapter_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071585956192,
      "name": "get_adapter_status",
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
int get_adapter_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_adapter_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587128220,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:65",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587131344,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:164",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587138352,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:138",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:224",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ]
    },
    {
      "addr": 18446744071587160672,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:246",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587131344,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587138352,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071587150320,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071594246751,
      "name": "get_adapter_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071587160672,
      "name": "get_adapter_status",
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
int get_adapter_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_adapter_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588327916,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:65",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588331440,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:164",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588341024,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:138",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:224",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ]
    },
    {
      "addr": 18446744071588372992,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:246",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588331440,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588341024,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071588355904,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071596210651,
      "name": "get_adapter_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588372992,
      "name": "get_adapter_status",
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
int get_adapter_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_adapter_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588604012,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:65",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588607536,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:164",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588617120,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:138",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:223",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ]
    },
    {
      "addr": 18446744071588648944,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:245",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588607536,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588617120,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071588632016,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071596735803,
      "name": "get_adapter_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588648944,
      "name": "get_adapter_status",
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
int get_adapter_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_adapter_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588904092,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:65",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588907616,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:164",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588917248,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:139",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:223",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ]
    },
    {
      "addr": 18446744071588949344,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:244",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588907616,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588917248,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071588932240,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071597644387,
      "name": "get_adapter_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588949344,
      "name": "get_adapter_status",
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
int get_adapter_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_adapter_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497001948,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:65",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497004368,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:164",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497013704,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:138",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497026752,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:224",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497042856,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:246",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497004368,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446603336497013704,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446603336497026752,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446603336497042856,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
int get_adapter_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_adapter_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291074896,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:65",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291078656,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:164",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291078656,
      "name": "get_adapter_status",
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
int get_adapter_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_adapter_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275665074,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:65",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275666998,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:164",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275674034,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:138",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275684850,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:224",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275666998,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446743936275674034,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446743936275684850,
      "name": "get_adapter_status",
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
int get_adapter_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_adapter_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584688392,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:65",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584690832,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:164",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584699408,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:138",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:224",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584726400,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:246",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584690832,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584699408,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071584711248,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071584712521,
      "name": "get_adapter_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584726400,
      "name": "get_adapter_status",
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
int get_adapter_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_adapter_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584619160,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:65",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584621600,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:164",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584630176,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:138",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:224",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584657168,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:246",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584621600,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584630176,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071584642016,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071584643289,
      "name": "get_adapter_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584657168,
      "name": "get_adapter_status",
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
int get_adapter_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_adapter_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584689736,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:65",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584692176,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:164",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584700752,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:138",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:224",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584727744,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:246",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584692176,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584700752,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071584712592,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071584713865,
      "name": "get_adapter_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584727744,
      "name": "get_adapter_status",
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
int get_adapter_status(struct hotplug_slot * slot, u8 * value)
```

```json
{
  "name": "get_adapter_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584797384,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:65",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584799824,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:164",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584808400,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:138",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:224",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584835312,
      "name": "get_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:246",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584799824,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584808400,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071584820176,
      "name": "get_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071584821449,
      "name": "get_adapter_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584835312,
      "name": "get_adapter_status",
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
int get_adapter_status(struct hotplug_slot * slot, u8 * value)
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
