# Function: <code>set_attention_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
int set_attention_status(struct hotplug_slot * hotplug_slot, u8 status)
```

```json
{
  "name": "set_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583353728,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:192",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583362928,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:148",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583374208,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:170",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583353728,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071583362928,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071583374208,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
int set_attention_status(struct hotplug_slot * hotplug_slot, u8 status)
```

```json
{
  "name": "set_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583666848,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:192",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583676176,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:148",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583687552,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:170",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583666848,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071583676176,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071583687552,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
int set_attention_status(struct hotplug_slot * hotplug_slot, u8 status)
```

```json
{
  "name": "set_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583805072,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:192",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583814384,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:150",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583825840,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:170",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583805072,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071583814384,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071583825840,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
int set_attention_status(struct hotplug_slot * hotplug_slot, u8 status)
```

```json
{
  "name": "set_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583848096,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:193",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583857344,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:150",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583868688,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:170",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583848096,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071583857344,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071583868688,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
int set_attention_status(struct hotplug_slot * hotplug_slot, u8 status)
```

```json
{
  "name": "set_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584111664,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:193",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584120928,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:150",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584132304,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:170",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584111664,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584120928,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071584132304,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
int set_attention_status(struct hotplug_slot * hotplug_slot, u8 status)
```

```json
{
  "name": "set_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584312304,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:179",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584321440,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:142",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584332224,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:180",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584348480,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:156",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584312304,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584321440,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071584332224,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071584348480,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
int set_attention_status(struct hotplug_slot * hotplug_slot, u8 status)
```

```json
{
  "name": "set_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584408208,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:158",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584416464,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:102",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584427824,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:146",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584443552,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:156",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584408208,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584416464,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071584427824,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071584443552,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int set_attention_status(struct hotplug_slot * hotplug_slot, u8 status)
```

```json
{
  "name": "set_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584604400,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:158",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584612688,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:100",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:146",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584640224,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:156",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584604400,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584612688,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071584624416,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071584625793,
      "name": "set_attention_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584640224,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int set_attention_status(struct hotplug_slot * hotplug_slot, u8 status)
```

```json
{
  "name": "set_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584742192,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:158",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584750480,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:100",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:146",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584777904,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:156",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584742192,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584750480,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071584762112,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071584763489,
      "name": "set_attention_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584777904,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int set_attention_status(struct hotplug_slot * hotplug_slot, u8 status)
```

```json
{
  "name": "set_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585432752,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:158",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585441184,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:100",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:146",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585469264,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:156",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585432752,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585441184,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071585453392,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071585454830,
      "name": "set_attention_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585469264,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int set_attention_status(struct hotplug_slot * hotplug_slot, u8 status)
```

```json
{
  "name": "set_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585584480,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:158",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585590784,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:100",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:146",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585611136,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:156",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585584480,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585590784,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071585601296,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071591412551,
      "name": "set_attention_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585611136,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int set_attention_status(struct hotplug_slot * hotplug_slot, u8 status)
```

```json
{
  "name": "set_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585463024,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:158",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585469248,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:100",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:146",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585489584,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:156",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585463024,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585469248,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071585479712,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071591354930,
      "name": "set_attention_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585489584,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int set_attention_status(struct hotplug_slot * hotplug_slot, u8 status)
```

```json
{
  "name": "set_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585929280,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:158",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585935488,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:100",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:146",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585956512,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:156",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585929280,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585935488,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071585946080,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071592382613,
      "name": "set_attention_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071585956512,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int set_attention_status(struct hotplug_slot * hotplug_slot, u8 status)
```

```json
{
  "name": "set_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587131552,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:158",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587138240,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:100",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:146",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587161024,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:156",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587131552,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587138240,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071587149872,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071594246449,
      "name": "set_attention_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071587161024,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int set_attention_status(struct hotplug_slot * hotplug_slot, u8 status)
```

```json
{
  "name": "set_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588331744,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:158",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588340896,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:100",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:146",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588373392,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:156",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588331744,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588340896,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071588355200,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    },
    {
      "addr": 18446744071596210567,
      "name": "set_attention_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588373392,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int set_attention_status(struct hotplug_slot * hotplug_slot, u8 status)
```

```json
{
  "name": "set_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588607840,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:158",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588616992,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:100",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:145",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588649344,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:155",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588607840,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588616992,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071588631312,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    },
    {
      "addr": 18446744071596735719,
      "name": "set_attention_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588649344,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int set_attention_status(struct hotplug_slot * hotplug_slot, u8 status)
```

```json
{
  "name": "set_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588907920,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:158",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588917120,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:101",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:145",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588949744,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:154",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588907920,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588917120,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071588931536,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    },
    {
      "addr": 18446744071597644303,
      "name": "set_attention_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588949744,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
int set_attention_status(struct hotplug_slot * hotplug_slot, u8 status)
```

```json
{
  "name": "set_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497004672,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:158",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497013592,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:100",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497026128,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:146",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497043320,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:156",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497004672,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446603336497013592,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446603336497026128,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446603336497043320,
      "name": "set_attention_status",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int set_attention_status(struct hotplug_slot * hotplug_slot, u8 status)
```

```json
{
  "name": "set_attention_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291078992,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:158",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291078992,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision ❓</summary>

```c
int set_attention_status(struct hotplug_slot * hotplug_slot, u8 status)
```

```json
{
  "name": "set_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275667260,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:158",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275673928,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:100",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275684338,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:146",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275667260,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446743936275673928,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446743936275684338,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Transformation ❓</summary>

```c
int set_attention_status(struct hotplug_slot * hotplug_slot, u8 status)
```

```json
{
  "name": "set_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584691008,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:158",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584699296,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:100",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:146",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584726720,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:156",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584691008,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584699296,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071584710928,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071584712305,
      "name": "set_attention_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584726720,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Transformation ❓</summary>

```c
int set_attention_status(struct hotplug_slot * hotplug_slot, u8 status)
```

```json
{
  "name": "set_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584621776,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:158",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584630064,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:100",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:146",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584657488,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:156",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584621776,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584630064,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071584641696,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071584643073,
      "name": "set_attention_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584657488,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Transformation ❓</summary>

```c
int set_attention_status(struct hotplug_slot * hotplug_slot, u8 status)
```

```json
{
  "name": "set_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584692352,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:158",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584700640,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:100",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:146",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584728064,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:156",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584692352,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584700640,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071584712272,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071584713649,
      "name": "set_attention_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584728064,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Transformation ❓</summary>

```c
int set_attention_status(struct hotplug_slot * hotplug_slot, u8 status)
```

```json
{
  "name": "set_attention_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584800000,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:158",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584808288,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:100",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:146",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584835632,
      "name": "set_attention_status",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:156",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584800000,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584808288,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071584819856,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071584821233,
      "name": "set_attention_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584835632,
      "name": "set_attention_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
int set_attention_status(struct hotplug_slot * hotplug_slot, u8 status)
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
